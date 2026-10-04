# MODELAGEM DE BANCO DE DADOS

## LOJA DE MATERIAIS — PERSONAL PISOS

**Universidade:** Universidade Cidade de São Paulo (UNICID)  
**Curso:** Engenharia de Software  
**Semestre:** 1º Semestre  
**Disciplina:** Modelagem de Banco de Dados  
**Professor:** Clóvis José Ramos Ferraro  
**Local:** São Paulo — SP  
**Ano:** 2026

---

## RELATÓRIO DA ENTREGA 1

Relatório da Entrega 1 apresentado na disciplina de Modelagem de Banco de Dados como parte dos requisitos de avaliação do primeiro semestre, sob orientação do professor Clóvis José Ramos Ferraro.

---

# ETAPA 1 — ESCOLHA E CARACTERIZAÇÃO DA EMPRESA

## 1.1 Identificação da Empresa

**Nome:** Personal Pisos

**Segmento:** Design de Interiores e Acabamentos.

### O que a empresa vende?

A Personal Pisos oferece soluções completas para ambientação, abrangendo:

- Revestimentos de piso, como vinílicos, laminados e porcelanatos;
- Proteção solar, como persianas e cortinas sob medida;
- Papel de parede;
- Tapetes;
- Painéis;
- Elementos de decoração em geral.

O foco da empresa é transformar ambientes residenciais com praticidade e sofisticação.

### Principais Clientes

Os principais clientes são:

- Pessoas físicas que estão reformando ou construindo a casa própria;
- Arquitetos e designers de interiores parceiros, que especificam produtos para seus clientes finais;
- Pequenos construtores.

---

## 1.2 Setores da Empresa

### Marketing

Responsável pela atração de clientes por meio de:

- Redes sociais;
- Parcerias com arquitetos;
- Tráfego pago;
- Divulgação dos produtos e serviços.

### Vendas

Responsável pelo atendimento consultivo, realizado:

- Presencialmente na loja física;
- Online, por meio de WhatsApp e Instagram;
- Elaboração de orçamentos;
- Fechamento de pedidos.

### Gerência

Responsável por:

- Tomada de decisões estratégicas;
- Gestão da equipe;
- Controle de qualidade;
- Autorização de determinadas operações.

### Finanças e Contabilidade

Responsável por:

- Gestão do fluxo de caixa;
- Contas a pagar e receber;
- Emissão de notas fiscais;
- Apuração de resultados;
- Controle financeiro das vendas.

### Recursos Humanos

Responsável por:

- Contratação de funcionários;
- Treinamento de vendedores;
- Suporte à equipe.

### Logística e Instalação

Setor essencial para o segmento, responsável por:

- Entrega dos materiais;
- Organização da logística;
- Agendamento de instalações;
- Mão de obra especializada para aplicação de pisos, persianas e demais produtos.

---

## 1.3 Funcionamento Operacional

### Modelo de Negócio

A Personal Pisos possui atuação híbrida, combinando atendimento digital e atendimento presencial.

O atendimento digital é utilizado principalmente para:

- Captação de clientes;
- Primeiro contato;
- Solicitação de informações;
- Orçamentos iniciais.

O showroom físico permite que o cliente:

- Visualize os produtos;
- Toque nas texturas;
- Compare materiais;
- Tire dúvidas com os consultores;
- Escolha os produtos desejados.

### Fluxo do Pedido

O fluxo operacional pode ser representado da seguinte forma:

**Captação do cliente → Visita técnica ou envio de medidas → Orçamento → Fechamento → Faturamento → Logística de entrega → Agendamento da instalação → Instalação**

---

## 1.4 Dados Utilizados pela Empresa

### Dados do Cliente

- Nome completo;
- CPF/CNPJ;
- Telefone/WhatsApp;
- E-mail;
- Data de nascimento;
- CEP;
- Endereço.

### Dados Logísticos

- Endereço completo de entrega;
- Data prevista de entrega;
- Data de instalação.

### Dados Técnicos

- Medidas exatas do ambiente;
- Metragem quadrada do piso;
- Medidas dos vãos de janelas;
- Especificações do produto;
- Marca;
- Cor;
- Lote;
- Referência.

### Dados Financeiros

- Valor total;
- Forma de pagamento;
- Status da transação;
- Valor do sinal;
- Parcelamento.

---

# ETAPA 2 — JUSTIFICATIVA DA ESCOLHA DA EMPRESA

## Por que essa empresa foi escolhida para o projeto?

O grupo escolheu a Personal Pisos porque a empresa já possui um site, porém identificou-se que ele não era bem estruturado e necessitava de melhorias.

Também foi identificada a necessidade de um banco de dados para organizar melhor as informações utilizadas no site e nos processos internos da empresa.

Outro fator que facilitou a escolha foi a possibilidade de contato com a empresa, pois uma das integrantes do grupo participa ativamente das ações da organização, facilitando a obtenção das informações necessárias para o desenvolvimento do projeto.

---

# ETAPA 3 — IDENTIFICAÇÃO DOS PROCESSOS DE NEGÓCIO

## Processo principal

**Cliente → Solicita orçamento → Projeto → Agendamento de visita → Medição → Compra de produtos → Pagamento → Entrega → Montagem/Instalação → Atualização do estoque**

---

## 3.1 Quem participa?

Participam do processo:

- Cliente;
- Vendedor;
- Designer de interiores;
- Montador;
- Setor financeiro.

---

## 3.2 O que inicia o processo?

O processo é iniciado quando:

- O cliente solicita um orçamento; ou
- O cliente procura um produto específico.

---

## 3.3 O que acontece?

Inicialmente é realizado o orçamento. Em seguida, o projeto é definido e, quando necessário, é agendada uma visita para realizar a medição do ambiente.

Após a aprovação do orçamento pelo cliente, ocorre:

1. Compra dos produtos;
2. Pagamento;
3. Entrega;
4. Montagem/instalação;
5. Atualização do estoque.

---

## 3.4 Que informação é gerada?

Durante o processo são geradas as seguintes informações:

- Orçamento;
- Medidas do ambiente;
- Pedido de venda;
- Produtos vendidos;
- Nota fiscal;
- Comprovante de pagamento;
- Atualização do estoque.

---

## 3.5 Qual é o resultado?

O ambiente do cliente é montado e/ou instalado e a venda é concluída.

---

# ETAPA 4 — IDENTIFICAÇÃO DOS PROBLEMAS E NECESSIDADES

## 4.1 Onde existe retrabalho?

Existem situações de retrabalho:

- Nas obras, quando ocorre algum problema de instalação ou serviço que não foi identificado durante a visita técnica realizada no período pré-obra;
- Na administração ou nas vendas, quando todos os processos necessários não são seguidos corretamente.

---

## 4.2 Existem informações duplicadas?

Existem poucas informações duplicadas, pois a loja está passando por um processo de reestruturação do sistema.

---

## 4.3 Existem informações perdidas?

Às vezes ocorre perda de informações. Por esse motivo, a loja está modernizando seus sistemas.

---

## 4.4 A empresa utiliza planilhas?

Sim. A empresa utiliza planilhas para auxiliar no controle das informações.

---

## 4.5 Existem controles manuais?

Existem poucos controles manuais. A empresa investiu em sistemas ERP e planilhas e atualmente está modernizando seus sistemas.

---

## 4.6 Os setores compartilham informações?

Sim. Os setores compartilham informações entre si.

---

## 4.7 É difícil encontrar informações?

De acordo com as informações fornecidas pelo proprietário, não existe grande dificuldade para encontrar informações.

---

## 4.8 Existem erros de cadastro?

Os erros de cadastro ocorrem raramente.

---

## 4.9 É difícil acompanhar estoque, vendas, clientes ou funcionários?

Não, desde que todas as informações estejam devidamente cadastradas.

Atualmente, o estoque é o setor que apresenta um pouco mais de dificuldade, pois a empresa não possui um colaborador específico responsável por organizar e catalogar os produtos.

---

## 4.10 Existem problemas para gerar relatórios?

Não existem problemas significativos para gerar relatórios.

---

# 4.11 Problemas e Necessidades

| Problema | Consequência |
|---|---|
| Problemas não identificados durante a visita técnica pré-obra | Retrabalho durante a instalação ou execução do serviço |
| Processos administrativos ou de venda não seguidos corretamente | Retrabalho e possíveis atrasos nos processos |
| Informações duplicadas durante a reestruturação do sistema | Necessidade de reorganização e conferência dos dados |
| Possibilidade de perda de informações | Dificuldade para manter todos os dados organizados e disponíveis |
| Uso de planilhas junto aos sistemas | Necessidade de modernização e integração dos controles |
| Controle de estoque sem colaborador específico | Maior dificuldade para acompanhar o estoque |
| Informações dependentes de cadastro correto | Possibilidade de dificuldades no acompanhamento quando há falhas no cadastro |

---

# ETAPA 5 — REQUISITOS FUNCIONAIS

## Requisitos Funcionais

### RF01 — Cadastro de clientes

O sistema deve permitir o cadastro dos dados pessoais do cliente, incluindo:

- E-mail;
- Número de celular;
- Nome completo;
- CPF ou CNPJ;
- Data de nascimento;
- CEP.

O sistema também deverá permitir a verificação em dois fatores.

### RF02 — Emissão de relatórios

O sistema deve permitir a emissão de relatórios relacionados aos dados cadastrados e aos processos da empresa.

### RF03 — Canal de contato

O sistema deve disponibilizar um canal de contato entre cliente e atendente.

### RF04 — Controle de estoque

O sistema deve permitir o controle de estoque dos produtos.

### RF05 — Criação de orçamentos

O sistema deve permitir que o atendente crie orçamentos prévios de serviços para os clientes, informando período e itens desejados, com validade configurável, por exemplo, 7 dias.

### RF06 — Estilo de decoração

O sistema deve permitir especificar o estilo de decoração desejado pelo cliente.

### RF07 — Registro do processo de compra e venda

O sistema deve registrar todo o processo, desde a compra de materiais até a venda dos produtos ao cliente.

### RF08 — Controle de disponibilidade dos produtos

O sistema deve registrar quais produtos estão disponíveis para venda e quais não estão disponíveis.

### RF09 — Cálculo do valor total

O sistema deve calcular o valor total da venda com base na quantidade de serviços a serem realizados e nos materiais utilizados.

---

# ETAPA 6 — REQUISITOS NÃO FUNCIONAIS

## Requisitos Não Funcionais

### RNF01 — Backup

O sistema deve realizar backup dos dados armazenados.

### RNF02 — Desempenho

O sistema deve apresentar resposta rápida às solicitações, com tempo de resposta de aproximadamente 0,5 segundo após a solicitação do usuário, sempre que possível.

### RNF03 — Disponibilidade

O sistema deve funcionar 24 horas por dia, 7 dias por semana.

### RNF04 — Responsividade

O sistema deve possuir design responsivo, funcionando adequadamente em celulares, tablets e computadores.

---

# ETAPA 7 — REGRAS DE NEGÓCIO

## Regras de Negócio

### RN01 — Exclusividade do material

Um material reservado para um cliente não pode ser simultaneamente reservado para outro cliente.

### RN02 — Sinal de pagamento

Deve ser solicitado um sinal de 35% do valor total da compra. O valor restante poderá ser parcelado em até 10 vezes sem juros, conforme as condições estabelecidas pela empresa.

### RN03 — Cálculo do valor total

O valor total do pedido deve considerar:

- Material escolhido;
- Compra realizada com o fornecedor;
- Quantidade de material necessária;
- Medidas realizadas no ambiente;
- Instalação.

### RN04 — Cancelamento

O cancelamento poderá ocorrer conforme as condições estabelecidas pela empresa e pela legislação aplicável. Em caso de cancelamento próximo à data da obra, valores já utilizados na compra de materiais poderão ser negociados diretamente com o cliente.

---

# ETAPA 8 — RESTRIÇÕES E POLÍTICAS ORGANIZACIONAIS

## 8.1 Quem pode aprovar uma operação?

Apenas o gerente ou proprietário pode realizar determinadas operações que necessitam de autorização.

---

## 8.2 Quem pode alterar determinado cadastro?

Os clientes podem editar seus próprios dados cadastrais.

A exclusão de informações do sistema é permitida somente ao gerente ou proprietário.

---

## 8.3 Limites de desconto

As compras possuem limite de desconto entre 5% e 10%, de acordo com o valor total da compra.

Descontos superiores ao limite estabelecido dependem da autorização do gerente ou proprietário.

---

## 8.4 Condições de pagamento

É possível realizar o pagamento:

- À vista;
- Parcelado.

No pagamento parcelado, é necessário um sinal de 35%, sendo o restante possível de ser parcelado em até 10 vezes sem juros, conforme as condições estabelecidas pela empresa.

---

## 8.5 Regras de cancelamento

As regras de cancelamento devem seguir o Código de Defesa do Consumidor e as condições contratuais aplicáveis.

Em situações envolvendo materiais já adquiridos pela empresa, os valores poderão ser negociados diretamente com o cliente, observando a legislação vigente.

---

## 8.6 Políticas de estoque

O estoque é conferido uma vez por mês e abastecido conforme as vendas realizadas, pois a loja não trabalha com estoque de todos os produtos.

---

## 8.7 Regras de acesso às informações

A empresa segue a LGPD — Lei Geral de Proteção de Dados.

Dessa forma, a empresa:

- Informa aos clientes a finalidade da utilização dos dados;
- Coleta apenas as informações necessárias;
- Adota medidas de segurança para proteção dos dados;
- Busca evitar vazamentos e acessos indevidos.

---

## 8.8 Operações que necessitam de autorização

Algumas operações somente podem ser realizadas mediante autorização do gerente ou proprietário, como:

- Descontos superiores a 5%;
- Exclusão de dados do sistema;
- Utilização de outros métodos de pagamento, como boleto;
- Outras operações administrativas que necessitem de autorização.

---

# ETAPA 9 — FLUXOGRAMA DOS PRINCIPAIS PROCESSOS

O fluxograma representa o processo completo de atendimento e venda da Personal Pisos.

**Fluxo principal:**

```text
Início
  ↓
Cliente solicita orçamento
  ↓
Atendimento inicial
  ↓
Definição do projeto
  ↓
Necessita visita técnica?
  ↓
Sim → Agendamento da visita
  ↓
Medição do ambiente
  ↓
Definição dos produtos
  ↓
Elaboração do orçamento
  ↓
Cliente aprova?
  ↓
Sim
  ↓
Compra dos produtos
  ↓
Pagamento
  ↓
Atualização do estoque
  ↓
Entrega
  ↓
Instalação/Montagem
  ↓
Finalização do pedido
  ↓
Fim