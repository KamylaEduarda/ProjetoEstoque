O código é um sistema simples de gerenciamento de estoque escrito em Python.

Ele faz três coisas principais:

Guarda os Dados: Usa um banco de dados SQLite para armazenar informações de produtos (nome, categoria, preço e quantidade) de forma permanente no arquivo estoque.db.

Oferece um Menu: Permite que o usuário interaja com o sistema através de 5 opções no menu (Cadastrar, Excluir, Relatório, Gráfico, Sair).

Gera um Gráfico: Usa a biblioteca Matplotlib para visualizar as quantidades de produtos em estoque, agrupadas por categoria.

Resumo das ações:

1- Cadastrar: Permite que o usuário cadastre um item no estoque.

2- Excluir: Permite que o usuário exclua um item existente no estoque.

3- Relatório: Lista todos os produtos e alerta caso o estoque esteja baixo.

4- Gráfico: Mostra um gráfico de barras comparando a quantidade de itens em cada categoria.

5- Sair: Encerra o programa e fecha conexão com o banco de dados.
