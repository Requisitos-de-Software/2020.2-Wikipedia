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

## Caso de uso 1: Wikipédia {#caso-de-uso-1}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Wikipédia.png" data-title="Caso de uso do Wikipédia" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Wikipédia.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Wikipédia.png" data-title="Caso de uso do Wikipédia" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

## Caso de uso 2: Buscar artigo {#caso-de-uso-2}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Buscar_artigo.png" data-title="Caso de uso buscar artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Buscar_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Buscar_artigo.png" data-title="Caso de uso buscar artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

## Caso de uso 3: Contribuir em artigo {#caso-de-uso-3}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Contribuir_em_artigo.png" data-title="Caso de uso contribuir em artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Contribuir_em_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Contribuir_em_artigo.png" data-title="Caso de uso contribuir em artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

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
    3. O ator clica em "ADICIONAR TÍTULO DE DESCRIÇÂO".
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

## Caso de uso 5: Salvar artigo {#caso-de-uso-5}

<div class="screenshot-holder" style="display: flex; justify-content: center;">
<a href="assets/images/casosdeuso/Salvar_artigo.png" data-title="Caso de uso salvar artigo" data-toggle="lightbox">
<img class="img-responsive" src="assets/images/casosdeuso/Salvar_artigo.png" alt="screenshot" style="width: 100%" />
</a>
<a class="mask" href="assets/images/casosdeuso/Salvar_artigo.png" data-title="Caso de uso salvar artigo" data-toggle="lightbox"><i class="icon fa fa-search-plus"></i>
</a>
</div>

### Especificação:

* **Ator(es):**
    * Usuário.
    <br><br>
* **Pré-condição:**
    * O ator deve estar visualisando um artigo.
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
                2. O ator digita a decrição (opcional) da nova lista.
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
            2. O ator digita a decrição (opcional) da nova lista.
    3. O artigo e movida para a lista escolhida pelo usuário.
    <br><br>
* **Pós-condição:**
    O artigo será salvo/movido/removido de uma lista que foi selicionada pelo usuário.
    <br><br>