# Refinando e Modelando Banco de Dados

Repositorio criado com objetivo de cumprir os deasfios de projeto propostos por Juliana Mascarenhas no bootcamp Geração Tech Unimed-BH - Ciência de Dados disponibilizado pela Digital Innovation One (DIO). Foram 2 desafios de projetos o primeiro foi "Refinando um Projeto Conceitual de Banco da Dados - E-COMMERCE" e o segundo "Construindo um Esquema Conceitual para Banco De dados".

## DESAFIO DE PROJETO : "Refinando um Projeto Conceitual de Banco da Dados - E-COMMERCE

### Narrativa: Escopo de E-commerce

#### Narrativa - Produto
#####   Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
#####   Cada produto possui um fornecedor
#####   Um ou mais produtos podem compor um pedido

#### Narrativa - Cliente
#####   O cliente pode se cadastrat no site com seu CPF ou CNPJ
#####   O endereço do cliente irá determinar o valor do frete
#####   Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto

#### Narrativa - Pedido
#####   Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
#####   Um produto ou mais compoem o pedido
#####   O pedido pode ser cancelado

### Objetivo: Refine o modelo apresentado acrescentando os seguintes pontos:
#####   Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
#####   Pagamento – Pode ter cadastrado mais de uma forma de pagamento
#####   Entrega – Possui status e código de rastreio


## DESAFIO DE PROJETO: "Construindo um Esquema Conceitual para Banco De dados"

### Objetivo: Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

#### Narrativa:
#####   Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
#####   Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
#####   Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega
#####   A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
#####   O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
#####   A mesma equipe avalia e executa os serviços
#####   Os mecânicos possuem código, nome, endereço e especialidade
#####   Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
