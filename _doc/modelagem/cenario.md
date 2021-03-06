---
title: Cenarios
sections:
   - Template
   - Cenarios
---

É uma narrativa textual rica em detalhes contextual, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais. Cenários são poderosos, requerem menos tempo quando comparados a modelos e protótipos complexos.

## Template

Template adotado pelo grupo para a documentação de seus cenários:

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Objetivo do cenário |
| **Contexto** | Os detalhes em que se ocorre o cenário |
| **Atores** | atores envolvidos |
| **Recursos** | Recursos necessários para se realizar o cenário |
| **Exceção** | Problemas que podem ocorrer |
| **Episódios** | Etapas para se realizar a ação |

</div>

## Cenários {#cenarios}

#### C1 - Fazer login

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Entrar com conta no sistema |
| **Contexto** | Estar conectado na internet<br>Possuir conta no sistema<br>Não estar logado no sistema |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Credenciais de acesso |
| **Exceção** | A internet cair durante a ação<br>O usuário inserir seus dados incorretamente |
| **Episódios** | O usuário abre o aplicativo<br>O usuário acessa a area de login<br>O usuário insere suas credenciais |

</div>

#### C2 - Vigiar artigo

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Vigiar um artigo para acompanhar mudanças |
| **Contexto** | Estar conectado na internet<br>Possuir conta no sistema<br>Estar logado no sistema |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Conta de usuário |
| **Exceção** | Ficar sem conexão durante o processo |
| **Episódios** | O usuário abre o aplicativo<br>Acessa o artigo que possui interesse<br>Clica em "⋮" e depois em "vigiar artigo" |

</div>

#### C3 - Contribuir em artigo (Forma tradicional)

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Contribuir em um artigo no qual o usuário possua domínio |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Recomendado possuir conta e ter efetuado login |
| **Exceção** | Ficar sem conexão durante o processo<br>Artigo ser uma página protegida |
| **Episódios** | O usuário abre o aplicativo<br>Acessa o artigo que deseja contribuir<br>Clica no botão "ADICIONAR [DESCRIÇÃO/LEGENDA/ETIQUETA]"<br>Digita o conteúdo a ser adicionado |

</div>

#### C4 - Contribuir em artigo (Por sugestão)

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Contribuir em um artigo no qual o usuário possua domínio |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Recomendado ter conta |
| **Exceção** | Ficar sem conexão durante o processo<br>Artigo ser uma página protegida |
| **Episódios** | O usuário abre o aplicativo<br>Clica no ícone descrito como "Edições"<br>Seleciona a forma que quer contribuir<br>Adiciona o conteúdo que deseja adicionar em um artigo |


</div>

#### C5 - Compartilhar artigo

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Compartilhar um artigo que tenha interesso |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet |
| **Exceção** | Ficar sem conexão durante o acesso do artigo |
| **Episódios** | O usuário abre o aplicativo<br>Acessa o artigo que deseja compartilhar<br>Clica em "⋮" e depois em "Compartilhar links" |

</div>

#### C6 - Deslogar

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Deslogar da conta no sistema |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet |
| **Exceção** | - |
| **Episódios** | O usuário abre o aplicativo<br>Clica no ícone descrito como "Mais"<br>Clica em "Sair" |

</div>

#### C7 - Criar lista de artigos (Forma tradicional)

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Criar uma lista para organizar artigos salvos |
| **Contexto** | Estar com o aplicativo aberto<br>Recomendado ter efetuado login |
| **Atores** | Usuário |
| **Recursos** | Recomendado ter acesso a internet<br>Recomendado ter conta de usuário  |
| **Exceção** | - |
| **Episódios** | O usuário abre o aplicativo<br>Clica no ícone descrito como "Minhas listas"<br>Clica em "⋮" e depois em "Criar nova lista"<br>Digita o nome da nova lista |

</div>

#### C8 - Criar lista de artigos (Após salvar um artigo)

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Criar uma lista para organizar artigos salvos |
| **Contexto** | Estar com o aplicativo aberto<br>Recomendado ter efetuado login |
| **Atores** | Usuário |
| **Recursos** | Recomendado ter acesso a internet<br>Recomendado ter conta de usuário |
| **Exceção** | - |
| **Episódios** | O usuário abre o aplicativo<br>Seleciona um artigo em que deseja salvar<br>Clica no ícone descrito "Salvar"<br>O usuário clica em "ADICIONAR À LISTA"<br>Clica em "Criar nova"<br>Digita o nome da nova lista para ser salvo o artigo |

</div>

#### C9 - Pesquisar artigos

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Procurar artigos de determinado desejo do usuário |
| **Contexto** | Estar com o aplicativo aberto |
| **Atores** | Usuário |
| **Recursos** | Internet |
| **Exceção** | - |
| **Episódios** | O usuário abre o aplicativo<br>Clica sobre a barra de pesquisa<br>Digita o conteúdo que procura |

</div>