Versão Final do Projeto da Pós Graduação em Desenvolvimento Web Full Stack.

Projeto de Cadastro de Livros/Autores

Rotas: Livros e Autores
Funcionalidades das Rotas de Livro/Autor: (1)Listar/Autor Livros, (2)Listar Livros/Autor por ID, (3)Cadastrar Livros/Autor, (4) Autualizar Livros/Autor, (5)Excluir Livro/Autor, (6)Listar Livro por Filtro.
Obs: 
No banco foi definido duas editoras "Classicos" e "Netflix" então sempre que for cadastrar algum livro e for adicionar uma editora, utilize uma dessas editoras.
É possível filtrar os livros utlizando a Editora como paramentro de busca. Ex: http://BANCODEDADOS/livros/busca?editora=Classicos
Para cadatrar um livro é necessário cadastrar um "Autor" em seguida utilize o "ID do Autor" para cadastrar o "Livro" 
Ex: 

Cadastrar Autor:

{
    "nome": "nome do autor",
    "nacionalidade": "nacionalidade do autor"
}

 em seguida cadastre o Livro:

 {
    "titulo": "nome do livro",
    "autor": "id do autor",
    "editora": "Netflix" ou "Classicos",
    "numeroPaginas": 200
}



Foi utilizado o MongoDB para fazer a conexão com o banco de dados.
Foi definida a quantidade de Livros/Autores que serão exibidos por páginas.

 
