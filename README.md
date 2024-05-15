Versão Final do Projeto da Pós Graduação em Desenvolvimento Web Full Stack.

Projeto de Cadastro de Livros/Autores

Rotas: Livros e Autores
Funcionalidades da Rota de Livro: (1)Listar Livros, (2)Listar Livros por ID, (3)Cadastrar Livros, (4) Autualizar Livros, (5)Excluir Livro, (6)Listar Livro por Filtro.
Obs: 
No banco foi definido duas editoras "Classicos" e "Netflix" então sempre que for cadastrar algum livro e for adicionar uma editora, utilize uma dessas editoras.
É possível filtrar os livros utlizando a Editora como paramentro de busca. Ex: http://localhost:3000/livros/busca?editora=Classicos
Para cadatrar um livro é necessário cadastrar um "Autor" em seguida utilize o "ID do Autor" para cadastrar o "Livro" 
Ex: 

{
    "nome": "nome do autor",
    "nacionalidade": "nacionalidade do autor"
}

 em seguida cadastre o Livro:

 {
    "titulo": "nome do livro",
    "autor": "id do autor",
    "editora": "Netflix",
    "numeroPaginas": 200
}



Foi utilizado o MongoDB para fazer a conexão com o banco de dados.
Foi definido a quantidade de Livros/Autores que serão exibidos por páginas.

 
