---
title: Épicos, Features e Estórias de usuários
sections:
    - Introducao
    - Epicos
    - Features
    - Estoria de usuarios
    - Backlog do produto
---

## Introdução {#introducao}

Neste documento iremos abordar assuntos relacionados a documentação dos requisitos levantados anteriormente usando técnicas como estórias de usuários, épicos,
features e backlog do produto.

### Épicos {#epicos}

É uma grande estória de usuário, dividido em pedaços menores (estórias de Usuários menores) de forma que possam ser estimadas, priorizados e desenvolvidos em um Sprint.

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Código | Nome |
|--|--|
| EP1 | Acesso ao sistema |
| EP2 | Contribuir com artigos |
| EP3 | Acessar artigos |
| EP4 | Gerenciamento de configurações |

</div>

### Features

O objetivo de uma Feature é realizar um Épico, podem haver 1 ou mais features agrupados sob um Épico. Uma Feature agrupa 1 ou muitas User Stories (estórias equivalem a requisitos funcionais) que estão no contexto da Feature.

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Código Épico | Código da Feature | Nome |
|--|--|--|
| EP1 | FE1 | Cadastro no sistema |
| EP1 | FE2 | Login no sistema |
| EP2 | FE3 | Contribuir em artigos |
| EP3 | FE4 | Acessar artigos |
| EP3 | FE5 | Acompanhar artigos |
| EP4 | FE6 | Logout |
| EP4 | FE7 | Alterar configurações do sistema |

</div>

### Estórias de usuários {#estoria-de-usuarios}

Uma estória de usuário é uma curta e simples descrição de uma tarefa expressa na perspectiva da pessoa que deseja essa nova funcionalidade, normalmente um usuário ou cliente do sistema (Wiegers e Beatty, 2013).

Serão escritos da seguinte forma:

Eu, como um < TIPO DE USUÁRIO >, desejo < OBJETIVO > para que eu consiga < UMA RAZÃO >

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Código da estória de usuário | Descrição | Critérios de aceitação |
|--|--|--|
| US1 | Como usuário, eu quero realizar o meu cadastro no app, para que eu possa usufruir todas as funcionalidades do app. | **A aplicação deve:**<br>- Mostrar o formulário de submissão |
| US2 | Como usuário, eu quero fazer login, para que eu possa usufruir todas as funcionalidades do app. | **A aplicação deve:**<br>- Mostrar formulário de login<br>- Mostrar opção de esqueci minha senha<br>- Mostrar opção de cadastrar-se |
| US3 | Como usuário, eu quero fazer contribuições em artigos que eu possua conhecimento, para que eu possa compartilhar conhecimento com outros | **O artigo deve:**<br>- Ser colaborativo<br>**O usuário deve:**<br>- Possuir ranking suficiente para o artigo em questão |
| US4 | Como usuário, eu quero acessar as edições que realizei, para facilitar o acesso a estes artigos | **O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US5 | Como usuário, eu quero receber notificações sobre minhas edições, para que eu possa saber sobre o andamento delas |**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US6 | Como usuário, eu quero criar tópicos de discussões sobre temas de meu interesse, para que eu possa debater junto aos demais usuários assuntos pertinentes de algum tema |**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US7 | Como usuário, eu quero buscar artigos de meu interesse, para que eu possa acessá-los | **A aplicação deve:**<br>- Fornecer uma barra de busca |
| US8 | Como usuário, eu quero ter acesso a listagens de artigos relevantes para mim, para que eu possa acessar artigos rapidamente | **A aplicação deve:**<br>- Mostrar artigos mais buscados<br>- Mostrar artigos semelhantes aos buscados pelo usuário<br>- Mostrar artigos aleatórios<br>- Mostrar artigos de temas atuais |
| US9 | Como usuário, eu quero compartilhar artigos que eu li com outras pessoas, para que eu possa divulgar temas de meu interesse | **A aplicação deve:**<br>- Mostrar opção de compartilhar |
| US10 | Como usuário, eu quero acessar o histórico de artigos que eu li, para que eu possa retornar a um artigo facilmente | **A aplicação deve:**<br>- Mostrar opção de acessar histórico de leituras |
| US11 | Como usuário, eu quero salvar artigos de meu interesse, para que eu possa acessá-los novamente | **A aplicação deve:**<br>- Mostrar opção de salvar artigo<br>**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US12 | Como usuário, eu quero criar listas de artigos para agrupar artigos de meu interesse, para que eu possa melhor organizar os meus artigos salvos |  **A aplicação deve:**<br>- Mostrar opção de salvar artigo<br>- Mostrar opção de criar lista<br>- Mostrar opção de definir nome da lista<br>- Mostrar opção de definir descrição da lista<br>**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US13 | Como usuário, eu quero sincronizar minhas listas de artigos entre meus dispositivos de acesso e ter maior praticidade | **A aplicação deve:**<br>- Possuir armazenamento de listas em nuvem.<br>**O usuário deve:**<br>- Possuir conta no sistema<br>- Estar logado |
| US14 | Como usuário, eu quero fazer logout, para que eu possa utilizar outra conta e ter mais segurança e privacidade. | **A aplicação deve:**<br>- Possuir opção para sair da conta. |
| US15 | Como usuário, eu quero editar o tema de cores do app, para que esteja da maneira que mais me agrade | **A aplicação deve:**<br>- Possuir diferentes temas para o usuário |
| US16 | Como usuário, eu quero editar a linguagem do aplicativo, para que eu possa escolher em qual idioma ler | **A aplicação deve:**<br>- Disponibilizar os idiomas para que o usuário escolha |

</div>

## Backlog do produto

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Código Épico | Código da Feature | Código da estória de usuário | Descrição | Prioridade |
|--|--|--|--|--|
| EP1 | FE1 | US1 | Como usuário, eu quero realizar o meu cadastro no app, para que eu possa usufruir todas as funcionalidades do app. | alta |
| EP1 | FE2 | US2 | Como usuário, eu quero fazer login, para que eu possa usufruir todas as funcionalidades do app. | alta |
| EP2 | FE3 | US3 | Como usuário, eu quero fazer edições em artigos que eu possua conhecimento, para que eu possa compartilhar conhecimento com outros | alta |
| EP2 | FE3 | US4 | Como usuário, eu quero acessar as edições que realizei, para facilitar o acesso a estes artigos | baixa |
| EP2 | FE3 | US5 | Como usuário, eu quero receber notificações sobre minhas edições, para que eu possa saber sobre o andamento delas | media |
| EP2 | FE3 | US6 | Como usuário, eu quero criar tópicos de discussões sobre temas de meu interesse, para que eu possa debater junto aos demais usuários assuntos pertinentes de algum tema | media |
| EP3 | FE4 | US7 | Como usuário, eu quero buscar artigos de meu interesse, para que eu possa acessá-los | alta |
| EP3 | FE4 | US8 | Como usuário, eu quero ter acesso a listagens de artigos relevantes para mim, para que eu possa acessar artigos rapidamente | baixa |
| EP3 | FE4 | US9 | Como usuário, eu quero compartilhar artigos que eu li com outras pessoas, para que eu possa divulgar temas de meu interesse | media |
| EP3 | FE4 | US10 | Como usuário, eu quero acessar o histórico de artigos que eu li, para que eu possa retornar a um artigo facilmente | media |
| EP3 | FE5 | US11 | Como usuário, eu quero salvar artigos de meu interesse, para que eu possa acessá-los novamente | media |
| EP3 | FE5 | US12 | Como usuário, eu quero criar listas de artigos para agrupar artigos de meu interesse, para que eu possa melhor organizar os meus artigos salvos | media |
| EP3 | FE5 | US13 | Como usuário, eu quero sincronizar minhas listas de artigos entre meus dispositivos de acesso e ter maior praticidade | media |
| EP4 | FE6 | US14 | Como usuário, eu quero fazer logout, para que eu possa utilizar outra conta e ter mais segurança e privacidade. | alta |
| EP4 | FE7 | US15 | Como usuário, eu quero editar o tema de cores do app, para que esteja da maneira que mais me agrade | media |
| EP4 | FE7 | US16 | Como usuário, eu quero editar a linguagem do aplicativo, para que eu possa escolher em qual idioma ler | alta |

</div>
