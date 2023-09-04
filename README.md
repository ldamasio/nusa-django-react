# nusa-django-react

### Arquitetura

Basicamente temos um container para o PostgreSQL, dois containers para o backend e um container para o front. 

Os dois containers do backend são: instalação do Django e uma camada Nginx para melhor servir os arquivos estáticos do backend.

O container do frontend contém uma instalação de React, turbinada com o Vite para otimização do processo de build e para renderização ao lado do servidor (SSR).

### Backend em Python utilizando ferramentas Django e Django-Rest-Framework

Dentro do backend, Django-ORM será utilizado para fazer a ponte entre nosso modelo de dados e o banco de dados PostgreSQL.

Além disso, o backend contém o Django Rest Framework (DRF) um conjunto de bibliotecas que, integradadas com o Django Models e com o sistema de autenticação com JWT, nos permitem elegantes automações para rápido e robusto desenvolvimento da API em Python.

### Frontend em Javascript utilizando a biblioteca React

O React traz um conjunto pronto de muitas soluções para o desenvolvimento componentizável de modernas interfaces de usuários, possibilitando tirar proveito das recentes atualizações da linguagem Javascript, proporcionando um código limpo e legível para construção contínua de aplicações web que demandam bastante interação do usuário.