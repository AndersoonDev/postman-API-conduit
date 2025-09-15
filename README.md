Olá! Bem-vindo ao meu portfólio de testes de API, onde demonstro minhas habilidades em testar e documentar APIs utilizando o Postman.

Todas as requisições independentes pre-request script

Este repositório é uma vitrine do meu trabalho e conhecimento em engenharia de qualidade e automação de testes.

📚 Sobre a Collection
Este repositório contém uma coleção de arquivos .json exportado do Postman, cada um representando um conjunto de testes para diferentes APIs. 
O foco principal está na API RealWorld (Conduit), uma API de back-end de exemplo para praticar testes e demonstrações.

🔐 Collection: API Conduit
Descrição: Testes para a API do projeto RealWorld, cobrindo uma ampla gama de funcionalidades como autenticação, gerenciamento de perfis, artigos, tags e comentários. 
As requisições estão organizadas em pastas para facilitar a navegação e a execução de testes de ponta a ponta.

Endpoints Testados:
Conduit API Checklist: https://docs.google.com/spreadsheets/d/1xmtF_quCve4se67Ba_q6kEhxYGmtYlIA1SsSRaIgKIM/edit?gid=0#gid=0

Autenticação de usuário:
POST /users/login

Criação de novo usuário:
POST /users

Gerenciamento de perfil:
GET /user
PUT /user

Gerenciamento de artigos:
POST /articles
PUT /articles/:slug
DELETE /articles/:slug

Leitura de artigos:
GET /articles/:slug
GET /articles
GET /articles/feed?limit=10&offset=0
GET /articles?limit=10&tag=:tag:&offset=0

Visualização de perfis:
GET /profiles/:profile

Seguir/deixar de seguir perfis:
POST /profiles/:username:/follow
DELETE /profiles/:username:/follow

Listagem de tags:
GET /tags

Gerenciamento de comentários:
GET /articles/:slug:/comments
POST /articles/:slug:/comments
DELETE /articles/:slug:/comments/:id:

💡 Como Utilizar
Para importar esta collection no Postman e testá-la você mesmo:

1- Clone o Repositório:

Bash
git clone https://github.com/AndersoonDev/postman-API-conduit.git

2- Importe no Postman: Abra o Postman e clique em Import e selecione o arquivo API-Conduit.postman_collection.json que você clonou.

3- Execute as Requisições: A collection está pronta para ser executada. 
Siga a ordem das pastas para um fluxo de teste completo, desde o registro do usuário até a exclusão de um artigo.

🛠️ Habilidades
Testes de API com requisições independentes pre-request script

Postman

RESTful APIs

Documentação de APIs

Análise de Requisitos

Resolução de Problemas

Git & GitHub.
