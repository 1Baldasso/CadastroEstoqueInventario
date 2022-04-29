# Cadastro Estoque Inventario
Esta planilha feita em VBA tem como objetivo o cadastro fácil de produtos em um estoque ou inventário.
O programa funciona de maneira a facilitar o trabalho de pessoas para o cadastro, deixando as informações sensíveis
(Valores e Custos) para serem cadastradas posteriormente pelas pessoas responsáveis.

# Botões e Macros
Os 3 principais botões são de cadastro, de atualização de valores e de edição de itens
O ultimo botão é o botão de Atualizar Estoque, na última planilha, em que ele popula a última planilha com todos os dados cadastrados até o momento.

# Personalizações
As categorias de cadastro utilizam o nome das primeiras planilhas existentes, sendo a ultima sempre a de Estoque Geral.
É possível adicionar planilhas e consequentemente novas categorias, desde que elas *NÃO* estejam na última.

# Utilidades e facilidades
- Cadastrar um produto sem localização utilizará a última localização da planilha ativa
- O atalho para abrir o formulário de cadastro é Ctrl+Shift+N
- Os códigos são criados a partir do nome da categoria, evitar categorias com iniciais iguais

# Bugs e melhorias a serem implementadas
- O código trava ao utilizar o botão de cadastro de uma categoria para cadastrar outra, ocorre um erro
- O campo Custo Total é salvo como String, ocorrendo um erro na soma dos valores na planilha "Estoque Geral"
- Adicionar senha ao abrir o arquivo para identificar se o usuário deve ter permissões para ver e editar os campos "Custo Unitário" e "Valor Locação"
