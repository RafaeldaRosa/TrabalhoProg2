#Trabalho de Programação 2 Unisul
##Requisitos:
1. O sistema deve armazenar todas informações em 
memória de modo que seja utilizada a estrutura 
de dados mais adequada para as operações em 
questão;
2. O sistema deve permitir o cadastro de alunos;
3. O sistema deve permitir o cadastro de professores
 1. Tanto alunos como professores devem ser mantidos na 
mesma estrutura;
 2. A forma de consulta de ambos é via sua matricula
4. O sistema deve permitir o cadastro de livros;
 1. Não são permitidos  o cadastro de livros permitidos;
 2. Um livro deve ter uma lista de Exemplares;
5. O sistema deve permitir o vínculo de um exemplar com um usuário(aluno ou professor) da biblioteca
 1. Cada usuário pode ter até 5 livros emprestados simultaneamente(não é permitido pegar mais de um exemplar do mesmo livro)
6. Características do aluno:
 1. Matrícula;
 2. Nome;
 3. Nome do curso;
 4. Exemplares pegos;
7. Características do professor:
 1. Matrícula;
 2. Nome;
 3. Lista de cursos que participa;
 4. Exemplares pegos;
8. Características do livro:
 1. Titulo;
 2. Autor;
 3. Lista exemplares;
9. Características do exemplar;
 1. Código
 2. Localização
 3. Edição
10. O sistema deve possuir uma interface(menu) para navegar entre as opções de operações; 
11. Outras operações permitidas (além do cadastro):
 1. Fazer uma consulta por livro e/ou exemplar;
 2. A partir da visualização da consultar o usuário pode fazer as seguintes operações:
  - Alterar os dados do objeto;
  - Excluir o objeto da estrutura de dados;