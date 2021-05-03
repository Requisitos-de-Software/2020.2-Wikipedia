---
title: >
sections:
   - Personas
   - Introspeccao
   - Questionario
   - Brainstorm
   - Lista Completa de Requisitos Elicitados
   - Referencias
   - Historico de Versao
---

## Personas

O desenvolvimento das personas está no início do projeto, pois as personas podem informar a funcionalidade do site, ajudar a descobrir lacunas ou destacar novas oportunidades.
Personas são arquétipos, personagens ficcionais, concebidos a partir da síntese de comportamentos observados entre consumidores com perfis extremos. Representam as motivações, desejos, expectativas e necessidades, reunindo características significativas de um grupo mais abrangente.

Com as seguintes etapas realizamos as personas:
1. Condense a pesquisa: procure temas/características que sejam específicos, relevantes e universais para o sistema e seus usuários.

2. Brainstorm: Organize os elementos em grupos de persona que representam seus usuários-alvo. Nomeie ou classifique cada grupo.

3. Refinar: Combine e priorize as personas rudes. Separe-os em categorias primárias, secundárias e, se necessário, complementares. Você deve ter cerca de 3-5 personas e suas características identificadas.

4. Torne-os realistas: desenvolva as descrições apropriadas do histórico, motivações e expectativas de cada persona. Não inclua muitas informações pessoais. Seja relevante e sério; o humor não é apropriado. [[1]](#label1)

O resultado foi as personas abaixo:

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **Persona 1:** | João Alves Cardoso
|-|
| **Foto:** | ![Persona 1](assets/images/personas/Persona1.jpeg) | 
| **Idade:** | 25 anos
| **Ocupação:** | Desempregado
| **Objetivo(s):** | Terminou sua faculdade e tem vontade de compartilhar o conhecimento que adquiriu.
| **Habilidade(s):** | Física e inglês técnico.
| **Tarefas(s):** | Deseja escrever e revisar artigos sobre física.
| **Relacionamento(s):** | Solteiro
| **Expectativas** | Espera poder escrever sobre o conhecimento que adquiriu na faculdade. <br>Espera poder visualisar a mudanças que outros voluntários tenha feito em páginas que ele contribuiu.

</div>

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **Persona 2:** | Aline Souza Martinz
|-|
| **Foto:** | ![Persona 2](assets/images/personas/Persona2.jpeg) | 
| **Idade:** | 14 anos
| **Ocupação:** | Estudante
| **Objetivo(s):** | Deseja ser uma grande youtuber com um canal de curiosidades.
| **Habilidades(s):** | Inglês básico, edição de vídeos.
| **Tarefas(s):** | Procurar conteúdo de curiosidades para realizar um vídeo. <br>De vez em quando conteúdo para trabalhos da escola.
| **Relacionamento(s):** | Possui diversos amigos que são colegas na escola onde estuda.
| **Expectativas** | Espera que alguém tenha escrito sobre alguma curiosidade para produzir um belo vídeo. <br>Espera que alguém tenha escrito sobre o tema de seu trabalho de escola.

</div>

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **Antipersona 1:** | Wesley Alan Braz
|-|
| **Foto:** | ![Persona 3](assets/images/personas/Persona3.jpeg) | 
| **Idade:** | 34 anos
| **Ocupação:** | Professor
| **Objetivo(s):** | Procurar conteúdo digitais para compartilhar com seus alunos.
| **Habilidade(s)** | Inglês intermediário, boa oratória, conhecimento básico sobre computadores e internet.
| **Relacionamento(s):** | É casado e possui dois filhos.
| **Expectativas** | Espera que o conteúdo da enciclopédia livre não contenha a mesma veracidade que obteria de um bom livro.

</div>

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **Antipersona 2:** | Lorenzo Borges da Costa
|-|
| **Foto:** | ![Persona 4](assets/images/personas/Persona4.jpeg) | 
| **Idade:** | 28 anos
| **Ocupação:** | Pesquisador de Ciências Sociais, editor experiente do wikipédia
| **Objetivo(s):** | Procurar ajudar a comunidade do wikipédia de forma orgânica.<br>Acredita que um modelo de desenvolvimento aberto ajuda a criar bons conteúdos.<br>Gosta de debater e se envolver em decisões da comunidade.
| **Habilidade(s)** | Inglês intermediário, cientista político, <i>soft skills</i>(habilidades interpessoais).
| **Relacionamento(s):** | Possui contato com outros editores experientes do wikipédia.
| **Expectativas** | Espera visualizar histórico de edição dos artigos.<br>Espera que possa realizar discussões sobre um artigo.<br>Espera poder conversar com outros editores facilmente.

</div>

As fotos foram retiradas do site [thispersondoesnotexist.com](thispersondoesnotexist.com).

## Introspecção {#introspeccao}

Introspecção é uma técnica utilizada para elicitação de requisitos. Nesse método o responsável por levantar os requisitos deve imaginar quais propriedades o sistema deve possuir para atender com sucesso as necessidades do seu público alvo (personas). [[2]](#label2)

**Legenda:**
<br>
RF: Requisito Funcional.
<br>
RFN: Requisito Não Funcional.

##### Requisitos Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **ID do Requisito** | **Requisito** |
|-|-|
| RF1 | A aplicação deve permitir que o usuário efetue o login mediante suas credênciais.
| RF2 | A aplicação deve permitir que o usuário efetue o logout de sua conta.
| RF3 | A aplicação deve permitir que o usuário possa mudar sua senha.
| RF4 | A aplicação deve permitir que o usuário possa recuperar sua senha.
| RF5 | A aplicação deve permitir que o usuário possa pesquisa artigos.
| RF6 | A aplicação deve permitir que o usuário possa visualizar artigos offline.
| RF7 | A aplicação deve permitir que o usuário possa ver o histórico de artigos acessados.
| RF8 | A aplicação deve permitir que o usuário possa apagar o histórico de artigos acessados.
| RF9 | A aplicação deve permitir que o usuário possa compartilhar artigos.
| RF10 | A aplicação deve permitir que o usuário possa contribuir em artigos.
| RF11 | A aplicação deve permitir que o usuário possa visualizar suas edições de artigos.
| RF12 | A aplicação deve avisar ao usuário quando uma contribuição foi revertida.
| RF13 | A aplicação deve recomendar artigos ao usuário.
| RF14 | A aplicação deve permitir que o usuário possa alterar o tema da aplicação.

</div>

##### Requisitos não Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| **ID do Requisito** | **Requisito** |
|-|-|
| RNF1 | A aplicação deve garantir a veracidade dos artigos
| RNF2 | A aplicação deve garantir a praticidade
| RNF3 | A aplicação deve responder com rapidez

</div>

## Questionário {#questionario}

#### Motivação do uso desta técnica

Devido às restrições de interação restringidas em decorrência à pandemia de coronavírus, essa técnica se mostrou a forma mais acessível de obtermos informações do público alvo sem pormos a nós nem aos entrevistados em risco.

Outro ponto é a facilidade de aplicação dessa técnica e também devido a simplicidade do aplicativo tornar essa opção viável.

#### O que o grupo espera com o questionário?

O grupo espera com a utilização desta técnica de elicitação uma coleta de dados de diversas pessoas com o intuito de constatar alguns requisitos do sistema baseado nas respostas dos usuários.

#### Metodologias e técnicas utilizadas

A fim de entender melhor quem são os usuários e o que eles precisam, buscamos obter dados demográficos: idade, sexo, ocupação. Fazendo uso de perguntas fechadas para nos ajudar a entender a prioridade dos requisitos levantados durante o brainstorm e algumas abertas para extrairmos novos requisitos.

#### Dados coletados

<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest1.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest2.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest3.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest4.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest5.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest6.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest7.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest8.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest9.png){: .img-responsive}
</div>
<div class="screenshot-holder" style="display: flex; justify-content: center;margin: 2rem auto">
  ![screenshot](assets/images/questionario/quest10.png){: .img-responsive}
</div>

#### Resultados

Como resultados nós tivemos acesso a uma série de requisitos e a opiniões de diversos usuários de modo que usamos essas opiniões na priorização dos requisitos levantados pelo grupo.

## Brainstorm

#### O que é um Brainstorm?

Brainstorming é, basicamente, uma reunião em grupo onde ideias ou soluções para problemas podem ser encontradas através do debate entre os integrantes da sessão. É bastante utilizada quando não se tem muita informação sobre
o objeto alvo da equipe.<br><br>

#### Por que escolhemos usar o Brainstorm?

Por ser uma técnica que levanta uma grande quantidade de opiniões e ideias, diversos requisitos podem ser
encontrados. Outro motivo é que a mesma garante a participação de todos os integrantes do grupo.<br><br>

#### Tema do Brainstorm

Os temas que guiaram as reuniões de Brainstorm foram:

- Possíveis funcionalidades que seriam utilizadas por usuários dispostos a contribuir em artigos.
- Possíveis funcionalidades que seriam utilizadas por usuários que apenas buscam informações em artigos.
- Possíveis funcionalidades que oferecem comodidade a todos os usuários.

### 1° sessão do Brainstorm - Requisitos Elicitados

__Legenda:__ <br> RF: Requisito Funcional. <br>RFN: Requisito Não Funcional.

##### Requisitos Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| ID do Requisito |                              Requisito                              |
|:--:|:--:|
|RF1| Fazer Login |
|RF2| Fazer Cadastro |
|RF3| Buscar Artigo |
|RF4| Salvar Artigo |
|RF5| Compartilhar Artigo |
|RF6| Definir Tema do Aplicativo |
|RF7| Definir Linguagem do Aplicativo |
|RF8| contribuir em Artigo |
|RF9| Criar tópico de discussão |
|RF10| Visualizar Histórico de Artigos Acessados |
|RF11| Fazer Doações ao Site |
|RF12| Visualizar notificações |


</div>

##### Requisitos Não Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| ID do Requisito |                              Requisito                              |
|:--:|:--:|
|RNF1| O aplicativo deve possuir portabilidade |
|RNF2| O aplicativo ser Veloz |
|RNF3| O aplicativo deve Garantir Veracidade Dos Artigos |

</div>

### 2° sessão do Brainstorm - Requisitos Elicitados

##### Requisitos Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| ID do Requisito |                              Requisito                              |
|:--:|:--:|
|RF13| Criar lista de artigos  |
|RF14| Acompanhar artigo  |
|RF15| Possuir um feed de artigos relevantes e noticias  |

</div>

## Lista Completa de Requisitos Elicitados

##### Requisitos Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| ID do Requisito |                              Requisito                              |
|:--:|:--:|
|RF1| Fazer Login |
|RF2| Fazer Cadastro |
|RF3| Buscar Artigo |
|RF4| Salvar Artigo |
|RF5| Compartilhar Artigo |
|RF6| Definir Tema do Aplicativo |
|RF7| Definir Linguagem do Aplicativo |
|RF8| contribuir em Artigo |
|RF9| Criar tópico de discussão |
|RF10| Visualizar Histórico de Artigos Acessados |
|RF11| Fazer Doações ao Site |
|RF12| Visualizar notificações |
|RF13| Criar lista de artigos  |
|RF14| Acompanhar artigo  |
|RF15| Possuir um feed de artigos relevantes e notícias  |

</div>

##### Requisitos Não Funcionais

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| ID do Requisito |                              Requisito                              |
|:--:|:--:|
|RNF1| O aplicativo deve possuir portabilidade |
|RNF2| O aplicativo ser Veloz |
|RNF3| O aplicativo deve Garantir Veracidade Dos Artigos |

</div>

## Referências {#referencias}

###### [1] {#label1}
> Personas. Disponível [aqui](https://www.usability.gov/how-to-and-tools/methods/personas.html). Acesso em 11 de mar. de 2021

###### [2] {#label2}
> Elicitação de Requisitos. PUC-RIO. Disponível [aqui](http://www2.dbd.puc-rio.br/pergamum/tesesabertas/0521479_08_cap_02.pdf). Acesso em 11 de mar. de 2021

> Klaus Pohl, Chris Rupp Requirements Engineering Fundamentals 2nd Edition

> BARBOSA. Simone. SILVA. Bruno. 2010. Interação Humano-computador.

## Histórico de Versão {#historico-de-versao}

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Versão | Data | Modificação | Autor(es) |
|--|--|--|--|
| 1.0 | 11/03/2021 | Criação da página | Eduardo Picolo |
| 1.1 | 11/03/2021 | Adição do conteúdo de brainstorm | Pedro Henrique |
| 1.2 | 11/03/2021 | Adição do conteúdo de personas e introspecção | Igor Queiroz e Kess Jhones
| 1.3 | 11/03/2021 | Adição do conteúdo de questionários | Matheus e Roberto

</div>
