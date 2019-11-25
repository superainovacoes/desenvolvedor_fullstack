# Resumo

O teste consiste na criação de um website composto por uma tela de login (autenticando via api) e um CRUD de produtos.

As informações de acesso à API de login serão enviadas momentos antes de iniciar o teste.

As ferramentas e tecnologias necessárias para realização do teste:
 - Sql Server 2014 ou superior
 - C# .net framework 4.5 ou .net core;
 - EntityFramework 6 ou core;
 - Html, Css e javascript;
 - Angular 6+;

# Detalhes

## Login
A tela de autenticação deve ser apenas composta pelos campos login e senha. Quando o usuário informar esses dados você deverá verificar se os dados são válidos realizando um post para a API "http://dev.sitemercado.com.br/api/login" e o retorno deverá ser tratado conforme o JSON na imagem abaixo. Se o usário e senha forem válidos, você deverá redirecionar o usuário para a tela de cadastro de produtos, caso contrário, retornar a mensagem retornada pela API para o usuário.

API de login:
 - Verbo: POST
 - Encoding: UTF8
 - Autenticação: HTTP Basic Authentication

## Produtos
Na funcionalidade de produtos, você deverá desenvolver todas as funções de manutenção do cadastro (CRUD), inserção, edição, exclusão e listagem. Para o cadastro do produto apenas os seguintes campos são necessários: Nome do Produto, Valor de Venda e Imagem.

Você deverá criar um banco de dados SQL Server com uma tabela chamada produto, composta pelos campos necessários para atender a tela.

No final você deverá enviar o script de criação do banco e o projeto.sln.

# Critérios de avaliação

Entendimento da solução: o que foi desenvolvido está adequado ao solicitado;
Domínio das plataformas: os recursos providos pela plataforma foram utilizados da maneira correta;
Legibilidade de código: deve ser limpo e seguir padrões SOLID;
Utilização de patterns: utilizar patterns nos lugares corretos e com a finalidade adequada;


