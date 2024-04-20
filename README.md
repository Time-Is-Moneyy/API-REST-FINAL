API de Gerenciamento de Produtos, Usuários e Pedidos


Este projeto consiste em uma API desenvolvida em Python utilizando o framework Flask, que permite o gerenciamento de produtos, usuários e pedidos em um sistema de comércio eletrônico.

____________________________________________________________________________________________________________________________________________________________________________________________
Estrutura do Projeto

app.py: Arquivo principal que contém a implementação da API utilizando Flask e Flask-Restful.

models.py: Definição dos modelos de dados utilizando Flask-SQLAlchemy para interagir com o banco de dados SQLite.

GET.py: Exemplo de como realizar solicitações GET para a API.

POST_PRODUCTS.py: Como adicionar produtos via solicitações POST.

POST_USUARIO.py: Como adicionar usuários via solicitações POST.

POST_PEDIDOS.py: Como adicionar pedidos via solicitações POST.

products.db: Banco de dados SQLite contendo os dados dos produtos.

user.db: Banco de dados SQLite contendo os dados dos usuários.

pedidos.db: Banco de dados SQLite contendo os dados dos pedidos.

____________________________________________________________________________________________________________________________________________________________________________________________
Funcionalidades Principais

A API oferece as seguintes funcionalidades:

Gerenciamento de produtos: adição, remoção, atualização e listagem de produtos.

Gerenciamento de usuários: adição, remoção, atualização e listagem de usuários.

Gerenciamento de pedidos: adição, remoção, atualização e listagem de pedidos.

____________________________________________________________________________________________________________________________________________________________________________________________
Uso da API
Clone o repositório: git clone https://github.com/seu-usuario/nome-do-repositorio.git

Navegue até o diretório do projeto: cd nome-do-repositorio

Execute o arquivo app.py para iniciar o servidor da API: python app.py

Acesse a API em http://127.0.0.1:5000/

____________________________________________________________________________________________________________________________________________________________________________________________
Observações
Certifique-se de ter o Python e as bibliotecas listadas no arquivo requirements.txt instaladas em seu ambiente.

Os arquivos .txt necessários para os exemplos de uso devem estar presentes no diretório do projeto.
