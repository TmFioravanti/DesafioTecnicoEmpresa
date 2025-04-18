# Desafio Técnico, Objetivo:
Implementar um sistema de controle de gastos residenciais com:

*Cadastros de transações;*

*Cadastro de pessoas;*

*Consulta de totais;*

#### Deixar claro qual foi a lógica/função do que foi desenvolvido, através de comentários e documentação no próprio código. 

# Tecnologias:
*.NET com C# para o back-end e React com Typescript para o front-end.*

# Funcionalidades:
*Cadastro de pessoas:*
Deverá ser implementado um cadastro contendo as funcionalidades básicas de gerenciamento: criação, deleção e listagem.
Em casos que se delete uma pessoa, todas a transações dessa pessoa deverão ser apagadas.
O cadastro de pessoa deverá conter:
### Identificador (deve ser um número inteiro sequencial único gerado automaticamente);
### Nome (texto);
### Idade (número inteiro);

*Cadastro de transações:*
Deverá ser implementado um cadastro contendo as funcionalidades básicas de gerenciamento: criação e listagem (não é necessário implementar edição/deleção).
Caso o usuário informe um menor de idade (menor de 18), apenas despesas deverão ser aceitas.

*O cadastro de transação deverá conter:*
### Identificador (deve ser um número inteiro sequencial único gerado automaticamente);
### Descrição (texto);
### Valor (número decimal positivo);
### Tipo (despesa/receita);
### Pessoa (inteiro identificador da pessoa do cadastro anterior);
### Esse valor precisa existir no cadastro de pessoa;

*Consulta de totais:*
Deverá listar todas as pessoas cadastradas, exibindo o total de receitas, despesas e o saldo (receita – despesa) de cada uma.
Ao final da listagem anterior, deverá exibir o total geral de todas as pessoas incluindo o total de receitas, total de despesas e o saldo líquido.
