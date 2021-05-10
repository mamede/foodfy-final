
<h1 align="center">
FOODFY
<br>  
 DESAFIO FINAL
</h1>

<p align="center">Projeto desenvolvido para o projeto final do bootcamp launchbase da Rocketseat.</p>
<hr />

## Resumo
O projeto tem a base de um site de receitas com os conceitos aprendidos durante o curso sendo aplicados no projeto.
O mesmo tem cadastros de receitas, sessões de usuários entre outras coisas.

## Tecnologias

- NodeJS
- PostgreSQL
- Nunjucks

## Como utilizar o projeto localmente.

1 - ``` Clone o repositório ```

2 - Execute ```npm install``` para instalar as dependências do projeto;

3 - Configure as credenciais do banco de dados(Postgres) no caminho src/app/config/db.js. 
 - 3.1 - Caso não tenha o banco configurado localmente, rode os comandos sql do arquivo `db.sql`

4 - Popule o banco de dados com o arquivo seed.js, utilize o comando ```node seed.js``` e aguarde.;

5 - Execute o comando ```npm start```.

## Observações

Para realizar o login, escolha algum usuário na tabela 'users', copie o e-mail e utilize a senha padrão '1'.

Para utilizar a recuperação de senha configure o mailtrap no arquivo src/lib/mailer.js.
