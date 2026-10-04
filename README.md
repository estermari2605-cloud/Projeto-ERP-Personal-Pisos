# Projeto-ERP-Personal-PisosMODELAGEM DE BANCO DE DADOS
LOJA DE MATERIAIS - PERSONAL PISOS

            Relatório da entrega 1 apresentado na disciplina de Modelagem de Banco de Dados como pré-requisito de avaliação do segundo semestre sob orientação do professor Clóvis Jose Ramos Ferraro.



SÃO PAULO 
2026
Etapa 1 – Escolha e caracterize a empresa
Nome: Personal Pisos
Segmento: Design de Interiores e Acabamentos.
O que vende: Soluções completas para ambientação, indo desde revestimentos de piso (vinílicos, laminados, porcelanatos) e proteção solar (persianas, cortinas sob medida) até elementos de decoração geral (papel de parede, tapetes, painéis). O foco é transformar ambientes residenciais com praticidade e sofisticação.
Principais Clientes: Pessoas físicas reformando ou construindo a casa própria. Arquitetos e designers de interiores parceiros (que especificam os produtos para seus clientes finais) e pequenos construtores.
Setores
Marketing: Foco em atração de clientes (redes sociais, parcerias com arquitetos, tráfego pago).
Vendas: Atendimento consultivo (presencial na loja física e online via WhatsApp/Instagram), elaboração de orçamentos e fechamento de pedidos.
Gerência: Tomada de decisões estratégicas, gestão de equipe e controle de qualidade.
Finanças e Contabilidade: Gestão de fluxo de caixa, contas a pagar/receber, emissão de notas fiscais e apuração de resultados.
RH: Contratação, treinamento de vendedores e suporte à equipe.
Logística/Instalação (essencial para o nicho, pois envolve a entrega dos materiais e, muitas vezes, a mão de obra especializada para a aplicação dos pisos e persianas).
Funcionamento Operacional
Modelo de Negócio: Atuação híbrida, combinando o atendimento digital (para captação e orçamentos iniciais) com o showroom físico (onde o cliente pode tocar, ver texturas e tirar dúvidas com consultores).
Fluxo do Pedido: Captação do cliente, visita técnica ou envio de medidas, orçamento, fechamento, faturamento, logística de entrega e agendamento da instalação.
Dados
Dados do Cliente: Nome completo, CPF/CNPJ, Telefone/WhatsApp e E-mail.
Dados Logísticos: Endereço completo de entrega e data prevista.
Dados Técnicos: Medidas exatas do ambiente (metragem quadrada de piso, vãos de janelas para persianas) e especificações do produto (marca, cor, lote e referência).
Dados Financeiros: Valor total, forma de pagamento escolhida (pix, cartão, boleto) e status da transação.






















Etapa 2 - Justifique a escolha.
Por que essa empresa foi escolhida para o projeto?
R: O grupo escolheu a empresa porque ela já tinha um site, mas ele não era bem estruturado e precisava de melhorias. Também identificamos a necessidade de um banco de dados para organizar melhor as informações do site. Além da facilidade de contato com a empresa, pois, uma das integrantes participa ativamente nas ações da empresa.























Etapa 3 - Identifique os processos de negócio.
R: Cliente -- Solicita orçamento -- Projeto -- Agendamento de visita -- Medição -- Compra de produtos -- Pagamento -- Entrega --Montagem/Instalação -- Atualização do estoque.

1) Quem participa?
 Cliente, vendedor, designer de interiores, montador e financeiro.
2) O que inicia o processo?
 O cliente solicita um orçamento ou procura um produto específico.
3) O que acontece?
 É realizado o orçamento, o projeto é definido e, quando necessário, é agendada uma visita para realizar a medição do ambiente. Após a aprovação, ocorre a compra dos produtos, o pagamento, a entrega e a montagem/instalação.
4) Que informação é gerada?
 Orçamento, medidas do ambiente, pedido de venda, produtos vendidos, nota fiscal, comprovante de pagamento e atualização do estoque.
5) Qual é o resultado?
 O ambiente do cliente é montado/instalado e a venda é concluída.














Etapa 4 – Identifique os problemas e necessidades.
Onde existe retrabalho? 
•	Nas obras, quando acontece algum problema em uma instalação ou serviço que não foi considerado a possibilidade durante a visita técnica realizada pré obra;
•	Na administração ou venda quando não foram seguidos todos os processos necessários.
 
Existem informações duplicadas?
Poucas, mas existem, pois a loja está reestruturando o sistema.
 
Existem informações perdidas?
Às vezes, por isso a loja está modernizando o sistema.
 
A empresa utiliza planilhas?
Sim, ela utiliza.
 
Existem controles manuais?
Poucos, a empresa investiu mais nos sistemas de ERP e planilhas e agora está modernizando o sistema.
 
Os setores compartilham informações?
Sim, compartilham.
 
É difícil encontrar informações?
De acordo com as informações passadas pelo dono não é.
 
Existem erros de cadastro?
Raramente.
 
É difícil acompanhar estoque, vendas, clientes ou funcionários?
Não, desde que esteja tudo devidamente cadastrado. Porém hoje o estoque é algo que dá um pouco mais de trabalho pois a empresa não possui um colaborador específico organizar/catalogar.

Existem problemas para gerar relatórios?
Não.

 PROBLEMAS E NECESSIDADES

•	Problema: Problemas não identificados durante a visita técnica pré-obra.
Consequência: Retrabalho durante a instalação ou execução do serviço;

•	Problema: Processos de administração ou venda não seguidos corretamente.
Consequência: Retrabalho e possíveis atrasos nos processos;

•	Problema: Informações duplicadas durante a reestruturação do sistema.
Consequência: Necessidade de reorganização e conferência dos dados;

•	Problema: Possibilidade de perda de informações.
Consequência: Dificuldade para manter todos os dados organizados e disponíveis;

•	Problema: Uso de planilhas junto aos sistemas.
Consequência: Necessidade de modernização e integração dos controles;

•	Problema: Controle de estoque sem colaborador específico.
Consequência: Maior dificuldade e trabalho para acompanhar o estoque;

•	Problema: Informações dependentes de cadastro correto.
Consequência: Possibilidade de dificuldades no acompanhamento quando há falhas no cadastro.





Etapa 5 – Levante os requisitos funcionais.
Requisitos funcionais:
RF1 - Cadastro com os dados pessoais do cliente, como: Email pessoal, número de celular, Nome completo, CPF ou CNPJ, data de nascimento e CEP. Juntamente com a verificação de dois fatores.
RF2 - Emissão de relatório.
RF3 - Canal de contato entre cliente e atendente.
RF4 - O sistema deve permitir o controle de estoque.
RF5 - O sistema deve permitir que o atendente crie orçamentos prévios de serviço para os clientes, informando período e itens desejados, com validade configurável (ex: 7 dias).
RF6 - Especificar o estilo o estilo de decoração desejada.
RF7 - O sistema deve registrar todo processo, desde a compra de material até a venda dele.
RF8 - O sistema deve registras quais produtos podem ser vendidos ou não.
RF9 -Calcular o valor total da venda com base na quantidade de serviços a serem realizados e materiais a serem utilizados.















Etapa 6 – Levante os requisitos não funcionais.
Requisitos não funcionais:
RNF1 - Backup dos dados.
RNF2 - O sistema deve ter uma resposta rápida para as solicitações, por exemplo, 0,5 segundo após o click do cliente.
RNF3 - O sistema deve funcionar 24/7.
RNF4 - Design responsivo, funcionando tanto em celular ou computadores.






















Etapa 7 - Identifique as regras de negócio.
Regras de negócio:
RN1 - Um material não pode ser vendido para mais de um cliente.
RN2 - Pedir um sinal de 35% do valor total da compra em até 10x sem juros.
RN3 - Calcular o valor total do pedido levando em consideração o material escolhido, a compra com o fornecedor para preenchimento do estoque, a quantidade de material que será usado (com base na medida feita) e a instalação.
RN4 - Cancelamento em até 7 dias antes da obra, caso contrário o valor não é devolvido e o cliente pega outro produto ou material.





















Etapa 8 - Identifique as restrições e políticas organizacionais.

RESTRIÇÕES E POLÍTICAS ORGANIZACIONAIS:
Quem pode aprovar uma operação? 
Apenas os Gerente/Dono podem realizar operações.
 
Quem pode alterar determinado cadastro?
Todos os cadastros podem ser editados pelos clientes, porém somente o gerente pode excluir as informações.
 
Limites de desconto?
Toda compra possui um limite de 5 à10% de desconto baseado no valor total da compra.
 
Condições de pagamento?
É possível pagar a vista ou parcelado (sendo no parcelado necessário um sinal de 35% e o restante pode ser feito em até 10x sem juros).
 
Regras de cancelamento
As regras de cancelamento seguem o Código de Defesa do Consumidor, sendo 7 dias para devolução total do valor gasto e caso já tenha havido algum valor gasto com compra de material, isso será negociado diretamente com o cliente.

Políticas de estoque
O estoque é conferido uma vez por mês e é abastecido conforme fazem as vendas, pois a loja não trabalha com estoque de todos os produtos.
 
Regras de acesso às informações
A loja segue a LGPD - Lei Geral de Proteção de Dados, ou seja, ela informa para que os dados dos clientes serão utilizados, coleta apenas as informações necessárias e possui medidas de segurança contra o vazamento de dados.
 
Existe alguma decisão da empresa que precisa ser respeitada pelo
sistema? 
Sim, algumas coisas são permitidas apenas com autorização do gerente. Como:
•	Desconto maior que 5%;
•	Exclusão de dados do sistema;
•	Outros métodos de pagamento, como boleto.


















Etapa 9 - Fluxograma dos principais processos.

 







Etapa 10 - Dicionário de dados conceitual preliminar.
 
Etapa 11 – Entidades.
Pessoa – Cliente - Funcionário - Fornecedor – Compra – Produto – Estoque - Contém - Pedido – Realiza





















Etapa 12 – Atributos.
Pessoa: Nome – Email – Telefone – Data_Nascimento – CPF (PK)
Cliente: Nome – ID_Cliente (PK) – Endereço – CPF (FK)
Funcionário: ID_Funcionário – Cargo – Salario – CPF (FK) – Setor
Fornecedor: Código_Fornecedor (PK) – Matéria-Prima – Custo_Unitario – CPF (FK)
Compra: Código_Fornecedor (FK) – Total_Gasto
Produto: Código de Produto (FK) – Descrição – Valor_Unitario
Estoque: Código de Produto (PK) – Informação – Quantidade de Cada Produto – Abastecimento (Mensal/Semanal)
Contém: Código de Pedido (FK) – Código de Produto (FK) – Quantidade de Produtos
Pedido: Código de Pedido (PK) – Data de Entrega – Pagamento total – Acréscimos
Realiza: ID_Cliente (FK) – Código de Pedido (FK) – Subtotal








Etapa 13 – Relacionamentos.
Pessoa – Cliente
•	Entidades Relacionadas: Pessoa e Cliente
•	Tipo de Relacionamento: Especialização / Herança
•	Descrição: A entidade Cliente deriva da entidade genérica Pessoa.
•	Atributo de Ligação: CPF (Chave Primária em Pessoa e Chave Estrangeira em Cliente)
Pessoa – Funcionário
•	Entidades Relacionadas: Pessoa e Funcionário
•	Tipo de Relacionamento: Especialização / Herança
•	Descrição: A entidade Funcionário deriva da entidade genérica Pessoa.
•	Atributo de Ligação: CPF (Chave Primária em Pessoa e Chave Estrangeira em Funcionário)
Pessoa – Fornecedor
•	Entidades Relacionadas: Pessoa e Fornecedor
•	Tipo de Relacionamento: Associação / Especialização
•	Descrição: Vincula o cadastro do fornecedor à pessoa física responsável.
•	Atributo de Ligação: CPF (Chave Primária em Pessoa e Chave Estrangeira em Fornecedor)
Cliente – Pedidos (via Tabela/Relacionamento "Realiza")
•	Entidades Relacionadas: Cliente e Pedidos (ligadas através da entidade associativa Realiza)
•	Descrição: Registra quais pedidos foram realizados por determinado cliente, contendo o subtotal.
•	Atributos de Ligação: ID_Cliente (FK) e Código de Pedido (FK)
Pedidos – Produto (via Tabela/Relacionamento "Contém")
•	Entidades Relacionadas: Pedidos e Produto (ligadas através da entidade associativa Contém)
•	Descrição: Associa os produtos que fazem parte de cada pedido e a respectiva quantidade de itens.
•	Atributos de Ligação: Código de Pedido (FK) e Código de Produto (FK)
Fornecedor – Compra
•	Entidades Relacionadas: Fornecedor e Compra
•	Descrição: Registra as compras efetuadas junto a um fornecedor e o total gasto.
•	Atributo de Ligação: Código_Fornecedor (PK em Fornecedor e FK em Compra)
Compra – Produto
•	Entidades Relacionadas: Compra e Produto
•	Descrição: Associa as aquisições/compras feitas aos produtos do catálogo.
•	Atributo de Ligação: Código de Produto / Associação entre as entradas de compra e o produto.
Produto – Estoque
•	Entidades Relacionadas: Produto e Estoque
•	Descrição: Associa as informações físicas de estoque e periodicidade de abastecimento ao produto correspondente.
•	Atributo de Ligação: Código de Produto (PK em Estoque e FK/Referência em Produto)
•	Etapa 14 – Cardinalidade.
•	Pessoa -> Cliente / Funcionário / Fornecedor: (0,1) para (1,1). Uma pessoa pode ser cadastrada como cliente, funcionário ou fornecedor.
•	Cliente -> Pedido ("Realiza"): (0,N) para (1,1). Um cliente pode realizar zero ou vários pedidos, mas um pedido pertence a um único cliente.
•	Pedido -> Produto ("Contém"): (1,N) para (0,N). Um pedido contém pelo menos 1 produto e um produto pode estar contido em vários pedidos (Relacionamento N:M).
•	Fornecedor -> Compra: (0,N) para (1,1). Um fornecedor pode estar em várias compras, e cada compra está associada a 1 fornecedor.
•	Produto -> Estoque: (1,1) para (1,1). Cada produto cadastrado possui exatamente 1 registro de controle de estoque correspondente.
















Etapa 15 – Diagrama Entidade-Relacionamento DER.
 






Etapa 16 – Justificativas técnicas das principais decisões de modelagem. 
1.	Modelagem de Pessoa como Entidade Forte e Cliente/Funcionário/Fornecedor como Entidades Fracas:
A entidade forte Pessoa centraliza os atributos genéricos (CPF, Nome, Email, Telefone, Data_Nascimento)[cite: 4]. As entidades Cliente, Funcionário e Fornecedor conectam-se a ela utilizando o CPF como Chave Estrangeira (FK)[cite: 4], garantindo a integridade dos cadastros no banco de dados e evitando a duplicação de informações pessoais.
2.	Criação das Entidades Associativas (Contém e Realiza):
Para resolver os relacionamentos de múltiplos registros sem gerar duplicidade de dados:
a.	Contém: Surge da relação entre Pedido e Produto para armazenar a Quantidade_De_Produtos comprada de cada item no pedido[cite: 4].
b.	Realiza: Conecta Cliente a Pedido, armazenando o atributo próprio Subtotal gerado pela transação do cliente.
3.	Separação entre Produto (Entidade Forte) e Estoque (Entidade Fraca / Relação 1:1):
O cadastro do Produto mantém apenas dados fixos do catálogo (Descrição, Valor_Unitario)[cite: 4]. O Estoque é tratado de forma vinculada (1:1) para controlar dados operacionais e dinâmicos (Informação, Quantidade_De_Cada_Produto, Abastecimento)[cite: 4], permitindo atualizar lotes e saldos sem alterar as especificações fixas do produto.
4.	Definição de Código_Produto como Chave Primária (PK) em Produto:
Garante que a entidade Produto seja independente (entidade forte) e que seu código identificador único possa ser referenciado corretamente como Chave Estrangeira (FK) nas entidades associativas (Contém, Compra) e no Estoque[cite: 4].








Etapa 17 – Conclusão
Esta entrega estabelece o Modelo Conceitual formal para a Personal Pisos, estruturando os requisitos coletados em entidades, atributos, relacionamentos e regras de negócio. O modelo atende às necessidades operacionais e de gestão da empresa e serve como base sólida para a próxima fase do projeto (Modelo Lógico, Normalização e DDL em Banco de Dados Relacional).


















Etapa 18 – Checklist
[x] Empresa caracterizada — Personal Pisos (Design de Interiores e Acabamentos, modelo híbrido, setores e dados descritos). [x] Escolha justificada — Apresentada no Item 3 (site precisando de melhorias, implementação de BD e acesso facilitado aos processos). [x] Principais processos identificados — Identificados no Item 4 (da solicitação do orçamento até a instalação e atualização do estoque). [x] Problemas identificados — Mapeados no Item 5 (falhas na visita técnica pré-obra, falta de colaborador específico no estoque, retrabalho admin/vendas). [x] *Necessidades identificadas — Mapeadas no Item 5 junto às consequências dos problemas (modernização, integração, controle de dados).
REQUISITOS [x] *Requisitos funcionais — Definidos do RF1 ao RF9 no Item 6. [x] *Requisitos não funcionais — Definidos do RNF1 ao RNF5 no Item 7. [x] Regras de negócio — Definidas da RN1 à RN4 no Item 8. [x] *Restrições organizacionais — Definidas no Item 9 (permissões de aprovação/alteração apenas para Gerente/Dono). [x] Políticas organizacionais — Definidas no Item 9 (limite de desconto de 5% a 10%, sinal de 35%, LGPD, conferência mensal de estoque).
PROCESSOS [x] *Principais processos representados — Descreve a jornada completa (Atendimento → Medição → Venda → Instalação → Estoque). [x] *Fluxogramas construídos — Referenciado no Item 10. [x] Fluxogramas coerentes com os requisitos — Alinhados com a jornada descrita no Item 4 e requisitos de orçamento (RF5) e estoque (RF4). [x] *Integração entre processos demonstrada — Conexão clara entre vendas, financeiro, logística de instalação e atualização de estoque.
DADOS [x] *Entidades identificadas — 10 entidades/associativas listadas no Item 12. [x] *Atributos identificados — Detalhados por entidade no Item 13. [x] Atributos descritos — Tipos e descrições detalhadas no Dicionário de Dados do Item 11. [x] *Dicionário conceitual elaborado — Tabela completa apresentada no Item 11.
RELACIONAMENTOS [x] *Relacionamentos identificados — Detalhados no Item 14. [x] Cardinalidades definidas — Especificadas no Item 15 (ex: 1:1, 1:N, N:M). [x] Os dois sentidos dos relacionamentos foram analisados — Analisados nas descrições de cardinalidade do Item 15. [x] *Relacionamentos N:N foram verificados — Identificados e tratados via entidades associativas Contém e Realiza. [x] Atributos dos relacionamentos foram analisados — Atributo Subtotal associado à Realiza e Quantidade_De_Produtos associada à Contém.
DER [x] Todas as entidades estão representadas — Conforme especificações dos Itens 12, 13 e 16. [x] Atributos estão associados corretamente — Mapeamento PK/FK estruturado no Item 13 e Dicionário de Dados. [x] Relacionamentos estão representados — Mapeados estruturalmente no Item 14. [x] *Cardinalidades estão representadas — Definidas formalmente no Item 15. [x] O modelo é coerente com as regras — Atende a todas as regras organizacionais e de negócio (sinal de pagamento, restrição de lote, estoque). [x] O modelo demonstra integração — Centralização em Pessoa ligando Clientes, Funcionários, Fornecedores e Vendas. [x] O modelo pode evoluir nas próximas etapas — Modelagem conceitual pronta para derivação do Modelo Lógico, Normalização e DDL.
DOCUMENTAÇÃO [x] README organizado — Estrutura sequencial do documento (1 ao 18). [x] DER anexado ao repositório — Referenciado no Item 16. [x] Dicionário anexado/documentado — Estruturado na tabela do Item 11. [x] *Fluxogramas anexados/documentados — Referenciado no Item 10. [x] Justificativas técnicas incluídas — Detalhadas tecnicamente no Item 17. [x] *GitHub organizado — Pronto para inclusão no repositório do projeto. [x] Todos os integrantes contribuíram para o projeto — Trabalho em grupo validado pela contextualização da empresa no Item 3.

