Desafio (Back)

Para que possamos conhecer um pouco mais sobre o seu trabalho, e mais especificamente sobre as suas
habilidades de desenvolvimento de software, preparamos essa atividade bem simples, que poderá nos mostrar
um pouco sobre a maneira que você organiza o seu código, a legibilidade dele, etc.]

1. Você deve criar uma aplicação back end, atendendo os requisitos técnicos propostos.
2. Hospedar seu código no GitHub.

Requisitos Técnicos:
 Criar um sistema batch, em Java ou Python.
 Persistir os dados em uma base de dados SQL Server ou similar.

A ideia é basicamente a seguinte:
- Vamos criar uma tabela na base de dados chamada tb_customer_account.
id_customer – Identificação unica do cliente.
cpf_cnpj – CPF ou CNPJ do Cliente
nm_customer – Nome do Cliente
is_active – Indica se o cliente está ativo ou não
vl_total – Mostra quando que o cliente possui de saldo.

- Na sua aplicação, insira ‘N’ registros na tabela tb_customer_account
- Após a inserção, percorra os objetos e calcule a média do campo vl_total apenas para os itens que este valor
seja maior que 560 e o campo id_customer esteja entre 1500 e 2700.
- Exiba a média final
- Imprima cada um dos clientes utilizados para o cálculo da média, ordenando do maior para o menor saldo.
