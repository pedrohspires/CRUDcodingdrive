# Laravel 8 CRUD Example by codingdrive.com

Olá. Este é um projeto básico para treianr CRUD com Laravel na versão 8 feito pelo site codingdrive.com. Seguindo o passo a passo, repliquei este projeto para fins de estudos.


## Como rodar na sua maquina
1. Clone o repositório ou baixe e extraia o projeto em um local do seu pc
   >git clone https://github.com/pedrohspires/CRUDcodingdrive.git
2. Com o MySQL, ou outro SGBD de sua preferência, crie uma base de dados com o nome que desejar, aqui no exemplo será CRUD<br>
OBS: o comando abaixo deve ser utilizado no terminal já logado no MySQL com um usuário com permissões. Caso esteja utilizando phpmyadmin ou outro administrador de banco de dados, desconsidere o comando e crie a base de dados por ele.
   >create database CRUD;
3. Configure o banco de dados no arquivo .env em src/.env.example (lembre-se de remover o ".example" e deixar apenas ".env")
4. Com o PHP já instalado e configurado, entre na pasta src/ do projeto clonado e execute o comando abaixo para criar a tabela necessária.
   >php artisan migrate
5. Com tudo configurado, agora basta executar o comando abaixo para iniciar o servidor
   >php artisan serve
6. No navegador, acesse:
   >localhost:8000/posts