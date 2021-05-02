---
title: Casos de uso
sections:
    - Caso de uso 1
    - Caso de uso 2
    - Caso de uso 3
    - Caso de uso 4
    - Caso de uso 5
---

## Introdução

Na Linguagem de modelagem unificada (UML), o diagrama de caso de uso resume os detalhes dos usuários do seu sistema (também conhecidos como atores) e as interações deles com o sistema. Para criar um, use um conjunto de símbolos e conectores especializados.

Um diagrama de caso de uso adequado dá uma visão geral do relacionamento entre casos de uso, atores e sistemas. Para oferecer maior detalhamento foi utilizado da especificação de caso de uso. [[2]](#label2)

## Caso de uso 1: Wikipédia {#caso-de-uso-1}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Wikipédia.png" data-title="Caso de uso do Wikipédia" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Wikipédia.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Wikipédia.png" data-title="Caso de uso do Wikipédia" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

<p style="text-align: center; font-Weight: bold; font-style: italic;">
    Figura 1 - Caso de uso Wikipédia. Própria Autoria.
</p><br/>

## Caso de uso 2: Buscar artigo {#caso-de-uso-2}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Buscar_artigo.png" data-title="Caso de uso buscar artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Buscar_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Buscar_artigo.png" data-title="Caso de uso buscar artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

<p style="text-align: center; font-Weight: bold; font-style: italic;">
    Figura 2 - Caso de uso buscar artigo. Própria Autoria.
</p><br/>


### Especificação:

* **Ator(es):**
    * Usuário.
    <br><br>
* **Pré-condição:**
    * O ator deve estar com aplicativo aberto.
    <br><br>
* **Fluxo de evento principal: (Buscar artigo)**
    1. O ator clica na barra de pesquisa do aplicativo.
        1. O autor pode escolher o idioma da pesquisa.
    2. O ator digita o conteúdo que deseja pesquisar e pressiona em “ir”.
    3. O sistema responde a pesquisa do autor com vários resultados.
    4. O ator seleciona a pesquisa dentre os resultados.
    <br><br>
* **Fluxo de evento alternativo: (Buscar artigo)**
    1. O ator clica no microfone na barra de pesquisa do aplicativo.
    2. O ator fala o conteúdo que deseja pesquisar.
    3. O sistema responde a pesquisa do autor com vários resultados.
    4. O ator seleciona a pesquisa dentre os resultados.
    <br><br>
* **Fluxo de evento principal: (Buscar artigo vistos recentemente)**
    1. O ator clica na barra de pesquisa do aplicativo.
    2. O sistema lhe mostra seu histórico de pesquisa.
    3. O ator procura o conteúdo que deseja pesquisar entre as pesquisas recentes e pressiona em cima do mesmo.
    4. O sistema responde a pesquisa do autor com vários resultados.
    5. O ator seleciona a pesquisa dentre os resultados.
    <br><br>
* **Pós-condição:**
    O autor poderá navegar entre os resultados ou selecionar um que lhe satisfaça.
    <br><br>

## Caso de uso 3: Contribuir em artigo {#caso-de-uso-3}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Contribuir_em_artigo.png" data-title="Caso de uso contribuir em artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Contribuir_em_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Contribuir_em_artigo.png" data-title="Caso de uso contribuir em artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

<p style="text-align: center; font-Weight: bold; font-style: italic;">
    Figura 3 - Caso de uso contribuir em artigo. Própria Autoria.
</p><br/>

### Especificação:

* **Ator(es):**
    * Usuário.
    <br><br>
* **Pré-condição:**
    * O ator deve estar com aplicativo aberto.
    <br><br>
* **Fluxo de evento principal: (Acessar artigo)**
    1. O ator acessa um artigo.
    2. O sistema apresenta opções de contribuições na página.
    <br><br>
* **Fluxo de evento alternativo: (Acessar artigo)**
    1. O ator acessa um artigo.
    2. O sistema apresenta opções de contribuições na página.
        1. O ator clica em "ADICIONAR TÍTULO DE DESCRIÇÂO".
        2. O ator clica em uma imagem.
            1. O ator clica em "ADICIONAR LEGENDA À IMAGEM".
    3. O ator digita o conteúdo a ser adicionado.
    4. A contribuição e adicionada ao artigo.
    <br><br>
* **Fluxo de exceção (Acessar artigo)**
    1. O ator acessa um artigo.
    2. O sistema apresenta opções de contribuições na página.
    3. O ator clica em "ADICIONAR TÍTULO DE DESCRIÇÃO".
    4. O sistema apresenta uma mensagem informando que o artigo é protegido. Saiba mais [aqui](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:P%C3%A1gina_protegida).
    <br><br>
* **Fluxo de evento principal: (Exibir estatísticas de contribuição)**
    1. O ator clica no ícone descrito "Edições".
        1. O sistema apresenta ao ator uma mensagem de como ator pode ajudar a contribuir com o aplicativo.
        2. O sistema apresenta ao ator estatísticas de suas contribuições.
    <br><br>
* **Fluxo de evento alternativo: (Exibir estatísticas de contribuição)**
    1. O ator clica no ícone descrito "Edições".
        1. O sistema apresenta ao ator uma mensagem de como ator pode ajudar a contribuir com o aplicativo.
        2. O sistema apresenta ao ator estatísticas de suas contribuições.
    2. O ator seleciona uma forma de contribuir.
        1. O ator seleciona contribuir adicionando legendas as imagens.
        2. O ator seleciona contribuir adicionando etiquetas as imagens.
        3. O ator seleciona contribuir adicionando descrição aos artigos.
    3. O sistema apresenta um slide de artigos/imagens.
    4. O ator clica no botão "ADICIONAR [DESCRIÇÃO/LEGENDA/ETIQUETA]"
    5. O ator digita o conteúdo a ser adicionado.
    6. A contribuição e adicionada ao artigo.
    <br><br>
* **Pós-condição:**
    O ator adiciona sua contribuição aos artigos do aplicativo.
    <br><br>

## Caso de uso 4: Realizar login {#caso-de-uso-4}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Realizar_login_.png" data-title="Caso de uso realizar login" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Realizar_login_.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Realizar_login_.png" data-title="Caso de uso realizar login" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

<p style="text-align: center; font-Weight: bold; font-style: italic;">
    Figura 4 - Caso de uso realizar login. Própria Autoria.
</p><br/>

### Especificação:

* **Ator(es):**
    * Usuário.
    <br><br>
* **Pré-condição:**
    * O ator deve estar com aplicativo aberto.
    <br><br>
* **Fluxo de evento principal: (Criando Conta)**
    1. O ator seleciona o ícone escrito “Mais” na barra de rodapé.
    2. O sistema lhe apresenta 4 opções.
    3. O ator seleciona “ENTRAR/JUNTAR NA WIKIPEDIA”.
    4. O sistema lhe apresenta um formulário de cadastro.
    5. O ator preenche seus dados e envia o formulário.
    6. O sistema valida as credenciais inseridas.
    7. O sistema retorna o ator para a página inicial.
    <br><br>
* **Fluxo de evento principal: (Fazendo Login)**
    1. O ator seleciona o ícone escrito “Mais” na barra de rodapé.
    2. O sistema lhe apresenta 4 opções.
    3. O ator seleciona “ENTRAR/JUNTAR NA WIKIPEDIA”.
    4. O sistema lhe apresenta um formulário de cadastro.
    5. O ator seleciona “ENTRAR”.
    6. O sistema lhe apresenta um formulário de login.
    7. O ator preenche seus dados e envia o formulário.
    8. O sistema valida as credenciais inseridas.
    9. O sistema retorna o ator para a página inicial.
    <br><br>
* **Fluxo de evento principal: (Senha Esquecida)**
    1. O ator seleciona o ícone escrito “Mais” na barra de rodapé.
    2. O sistema lhe apresenta 4 opções.
    3. O ator seleciona “ENTRAR/JUNTAR NA WIKIPEDIA”.
    4. O sistema lhe apresenta um formulário de cadastro.
    5. O ator seleciona “ESQUECI MINHA SENHA”.
    6. O sistema redireciona o ator a um no navegador para que continue o processo de recuperação.
    <br><br>
* **Pós-condição:**
    O autor deverá conseguir entrar, recuperar sua senha ou se cadastrar com sucesso e finalizar seu login no aplicativo.
    <br><br>

## Caso de uso 5: Salvar artigo {#caso-de-uso-5}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Salvar_artigo.png" data-title="Caso de uso salvar artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Salvar_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Salvar_artigo.png" data-title="Caso de uso salvar artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

<p style="text-align: center; font-Weight: bold; font-style: italic;">
    Figura 5 - Caso de uso salvar artigo. Própria Autoria.
</p><br/>

### Especificação:

* **Ator(es):**
    * Usuário.
    <br><br>
* **Pré-condição:**
    * O ator deve estar visualizando um artigo.
    <br><br>
* **Fluxo de evento principal: (salvar artigo)**
    1. O ator clica no ícone descrito "salvar".
    2. O artigo e salvo na lista padrão (salvo).
    <br><br>
* **Fluxo de evento alternativo: (salvar artigo)**
    1. O ator clica no ícone descrito "salvar".
        1. O ator clica em "ADICIONAR À LISTA".
            1. O ator seleciona a lista no qual será salva o artigo.
            2. O ator clica no ícone descrito "Criar nova".
                1. O ator digita o nome da nova lista.
                2. O ator digita a descrição (opcional) da nova lista.
        2. O ator clica em "Adicionar a outra lista de leitura".
    4. O artigo e salvo na lista escolhida pelo usuário.
    <br><br>
* **Fluxo de evento principal: (remover da lista)**
    1. O ator clica no ícone descrito "salvar" em um artigo já salvo em uma lista.
        1. O ator clica em "Remover de [nome da lista]".
        2. O ator clica em "Remover das listas de leitura"
            1. O ator escolhe de quais listas será removido o artigo.
    3. O artigo e removido das listas escolhidas pelo usuário.
    <br><br>
* **Fluxo de evento principal: (mover para outra lista)**
    1. O ator clica no ícone descrito "salvar" em um artigo já salvo.
    2. O ator clica em "Mover de [nome da lista] para outra lista de leitura".
        1. O ator seleciona a lista no qual será salva o artigo.
        2. O ator clica no ícone descrito "Criar nova".
            1. O ator digita o nome da nova lista.
            2. O ator digita a descrição (opcional) da nova lista.
    3. O artigo e movida para a lista escolhida pelo usuário.
    <br><br>
* **Pós-condição:**
    O artigo será salvo/movido/removido de uma lista que foi selecionado pelo usuário.
    <br><br>