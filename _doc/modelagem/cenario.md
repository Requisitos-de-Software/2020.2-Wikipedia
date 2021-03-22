---
title: Cenarios
sections:
   - Template
   - Cenarios
---

## Introdução

É uma narrativa textual rica em detalhes contextual, de uma situação de uso da aplicação, envolvendo usuários, processos e dados reais ou potenciais. Cenários são poderesos, requerem menos tempo quando comparados a modelos e protótipos complexos.
## Template

Template adotado pelo grupo para a documentação de seus cenários:

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo**        | Objetivo do cenário |
| **Contexto**        | Os detalhes em que se ocorre o cenário |
| **Atores**          | atores envolvidos |
| **Recursos** | Recursos necessários para se realizar o cenário |
| **Exceção** | Problemas que podem ocorrer |
| **Episódios** | Etapas para se realizar a ação |

</div>

## Cenarios

#### Fazer login

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

#### Vigiar artigo

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

#### Contribuir em artigo

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Contribuir em um artigo no qual possuo dominio |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Recomendado ter conta |
| **Exceção** | Ficar sem conexão durante o processo<br>Artigo ser uma página protegida |
| **Episódios** | O usuário abre o aplicativo<br>Acessa o artigo que deseja contribuir<br>Clica no botão "ADICIONAR [DESCRIÇÃO/LEGENDA/ETIQUETA]"<br>O ator digita o conteúdo a ser adicionado |

</div>

#### Contribuir em artigo(Por sugestão)

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Contribuir em um artigo no qual possuo dominio |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet<br>Recomendado ter conta |
| **Exceção** | Ficar sem conexão durante o processo<br>Artigo ser uma página protegida |
| **Episódios** | O usuário abre o aplicativo<br>Clica no icone descrito como "Edições"<br>O ator selociona a forma que quer contribuir<br>O ator adiciona o conteúdo que deseja adicionar em um artigo |


</div>

#### Compartilhar artigo

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

#### Deslogar

<div class="table-responsive">

{: .table .table-striped .table-bordered}
| Elemento | Resposta |
|--|--|
| **Objetivo** | Deslogar da conta no sistema |
| **Contexto** | Estar conectado na internet |
| **Atores** | Usuário |
| **Recursos** | Internet |
| **Exceção** | - |
| **Episódios** | O usuário abre o aplicativo<br>Clica no icone descrito como "Mais"<br>Clica em "Sair" |

</div>

#### Criar lista de artigos
#### Pesquisar artigos
