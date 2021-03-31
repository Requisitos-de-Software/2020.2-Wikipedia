---
title: Epicos, Features e Estorias de usuarios
sections:
    - Introducao
    - Epicos
    - Features
    - Estoria de usuarios
---

## Introdução {#introducao}

### Épicos {#epicos}
É uma grande história de usuário, dividido em pedaços menores(Histórias de Usuários menores) de forma que possam ser estimadas, priorizados e desenvolvidos em um Sprint.

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Codigo | Nome |
|--|--|
| EP1 | Acesso ao sistema |
| EP2 | Contribuir com artigos |
| EP3 | Acessar artigos |
| EP4 | Gerenciamento de configurações |

</div>

### Features
O objetivo de uma Feature é realizar um Épico, podem haver 1 ou mais features agrupados sob um Épico. Uma Feature agrupa 1 ou muitas User Stories (histórias equivalem a requisitos funcionais) que estão no contexto da Feature.

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Codigo Epico | Codigo da Feature | Nome |
|--|--|--|
| EP1 | FE1 | Cadastro no sistema |
| EP1 | FE2 | Login no sistema |
| EP2 | FE3 | Contribuir em artigos |
| EP3 | FE4 | Acessar artigos |
| EP3 | FE5 | Acompanhar artigos |
| EP4 | FE6 | Logout |
| EP4 | FE7 | Alterar configurações do sistema |

</div>

### Estórias de usuários {#estorias-de-usuarios}

Uma história de usuário é uma curta e simples descrição de uma tarefa expressa na perspectiva da pessoa que deseja essa nova funcionalidade, normalmente um usuário ou cliente do sistema (Wiegers e Beatty, 2013).

Serão escritos da seguinte forma:

Eu, como um < TIPO DE USUÁRIO >, desejo < OBJETIVO > para que eu consiga < UMA RAZÃO >

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Codigo Epico | Codigo da Feature | Codigo da estória de usuário | Descrição | Critérios de aceitação |
|--|--|--|--|--|
| EP1 | FE1 | US1 | Como usuário, eu quero realizar o meu cadastro no app, para que eu possa usufruir todas as funcionalidades do app. | **A aplicação deve:**<br>- Mostrar o formulário de submição |
| EP1 | FE2 | US2 | Como usuário, eu quero fazer login, para que eu possa usufruir todas as funcionalidades do app. | **A aplicação deve:**<br>- Mostrar formulario de login<br>- Mostrar opção de esqueci minha senha<br>- Mostrar opção de cadastrar-se |
| EP2 | FE3 | US3 | Como usuário, eu quero fazer edições em artigos que eu possua conhecimento, para que eu possa compartilhar conhecimento com outros | **O artigo deve:**<br>- Ser editavel<br>**O usuário deve:**<br>- Possuir conta e estar logado<br>- Possuir ranking suficiente para o artigo em questão |
| EP2 | FE3 | US4 | Como usuário, eu quero acessar as edições que realizei, para facilitar o acesso a estes artigos | **O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| EP2 | FE3 | US5 | Como usuário, eu quero receber notificações sobre minhas edições, para que eu possa saber sobre o andamento delas |**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| EP2 | FE3 | US6 | Como usuário, eu quero criar tópicos de discussões sobre temas de meu interesse, para que eu possa debater junto aos demais usuários assuntos pertinentes de algum tema |**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| EP3 | FE4 | US7 | Como usuário, eu quero buscar artigos de meu interesse, para que eu possa acessá-los | **A aplicação deve:**<br>- Fornecer uma barra de busca |
| EP3 | FE4 | US8 | Como usuário, eu quero ter acesso a listagens de artigos relevantes para mim, para que eu possa acessar artigos rapidamente | **A aplicação deve:**<br>- Mostrar artigos mais buscados<br>- Mostrar artigos semelhantes aos buscados pelo usuário<br>- Mostrar artigos aleatórios<br>- Mostrar artigos de temas atuais |
| EP3 | FE4 | US9 | Como usuário, eu quero compartilhar artigos que eu li com outras pessoas, para que eu possa divulgar temas de meu interesse | **A aplicação deve:**<br>- Mostrar opção de compartilhar |
| EP3 | FE4 | US10 | Como usuário, eu quero acessar o histórico de artigos que eu li, para que eu possa retornar a um artigo facilmente | **A aplicação deve:**<br>- Mostrar opção de acessar histórico de leituras |
| EP3 | FE5 | US11 | Como usuário, eu quero salvar artigos de meu interesse, para que eu possa acessá-los novamente | **A aplicação deve:**<br>- Mostrar opção de salvar artigo<br>**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| EP3 | FE5 | US12 | Como usuário, eu quero criar listas de artigos para agrupar artigos de meu interesse, para que eu possa melhor organizar os meus artigos salvos |  **A aplicação deve:**<br>- Mostrar opção de salvar artigo<br>- Mostrar opção de criar lista<br>- Mostrar opção de definir nome da lista<br>- Mostrar opção de definir descrição da lista<br>**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| EP4 | FE6 | US13 | Como usuário, eu quero fazer logout, para que eu possa utilizar outra conta e ter mais segurança e privacidade. | **A aplicação deve:**<br>- Possuir opção para sair da conta. |
| EP4 | FE7 | US14 | Como usuário, eu quero editar o tema de cores do app, para que esteja da maneira que mais me agrade | **A aplicação deve:**<br>- Possuir diferentes temas para o usuário |
| EP4 | FE7 | US15 | Como usuário, eu quero editar a linguagem do aplicativo, para que eu possa escolher em qual idioma ler | **A aplicação deve:**<br>- Disponibilizar os idiomas para que o usuário escolha |

</div>
