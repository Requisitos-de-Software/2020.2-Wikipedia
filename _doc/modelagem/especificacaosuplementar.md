---
title: Especificação Suplementar
sections:
   - Finalidade
   - Escopo
   - FURPS+
---

Visa obter os requisitos que ainda não foram contemplados pelos outros métodos utilizados no projeto até aqui.
O método de avaliação que será usado para elicitar esses requisitos é o FURPS+.

### Finalidade

Neste documento iremos explicitar os requisitos não funcionais que não foram elicitados pelos casos de usos que apresentamos.

### Escopo
A Wikipédia é uma enciclopédia livre que contém mais de 32 milhões de artigos em 280 idiomas, sendo a referência mais abrangente compilada por trabalho humano.

### FURPS+

FURPS+ é um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos, assim como representa atributos de Qualidade de Software, sendo ele parte do Rational Unified Process (RUP): [[3]](#label3)

**F**unctionality (Funcionalidade): Representa todo aspecto funcional do software, ou seja seus requisitos. Sua medição considera, principalmente, o cumprimento dos requesitos especificados.

**U**sability (Usabilidade): É o atributo que avalia a interface com o usuário. Possui diversas subcategorias, entre elas: prevenção de erros; estética e design; ajudas e documentação; consistência e padrões.

**R**eliability (Confiabilidade): Refere-se a integridade, conformidade e interoperabilidade do software.

**P**erformance (Desempenho): Avalia os requisitos de desempenho do software. Podendo usar como medida diversos aspectos, entre eles: tempo de resposta, consumo de memória, utilização da CPU, capacidade de carga e disponibilidade da aplicação.

**S**upportability (Suportabilidade): Os requisitos de suportabilidade agrupam várias características, como: testabilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, instalabilidade, escalabilidade, localizabilidade entre outros.


### Wikipedia
1. Funcionalidade
 - Velocidade: A nossa nova aplicação permite-lhe navegar e editar na Wikipédia de uma forma mais rápida do que nunca.
 - Edição: Pode editar na Wikipédia! Com sessão iniciada ou não, nós agradecemos-lhe todas as suas contribuições.
 - Páginas recentes: Fornecemos-lhe o seu histórico de leitura, para que possa acompanhar as ligações que quiser sem se perder.
 - Páginas guardadas: Pode guardar páginas selecionadas para leitura e navegação ''offline'' mesmo sem ligação de dados.
 - Partilha: Use as suas aplicações sociais para partilhar a soma de todo o conhecimento humano.
 - Suporte de idioma: A aplicação permite que, de forma fácil, consiga ler a Wikipédia escrita em qualquer idioma.
 - Wikipédia Zero: Taxa de dados dispensada para operadores móveis participantes.

2. Usabilidade
 - Paginas usam o formato *wikitext* da MediaWiki, para que usuarios sem conhecimento de HTML ou CSS possam edita-las facilmente;
 - A aplicação segue padrões para cores, espaçamentos e formas;
 - A aplicação da feedbacks de erros para seus usuários.

3. Confiabilidade
 - O usuario poderá enviar relatorios de travamento, contento onde o travamento se originou no código e outras informações de diagnóstico, como a versão do iOS e o tipo de dispositivo. Esta informação não inclui e não está ligada à conta de usuário da Wikimedia ou atividade na wiki, como ler ou editar o histórico;
 - O sistema não deverá rastrear o usuario, exceto se o usuario permitir.

4. Portabilidade
 - O sistema deverá funcionar nos navegadores de internet em geral, assim como em dispositivos capazes de acessar a internet, que suportem os demais navegadores e, também, que estejam equipados com sistema Android e iOS, ou seja, se adaptando visualmente à esses sistemas;
 - O sistema deverá ter alto nível de disponibilidade considerando a necessidade de acesso contínuo e frequente à aplicação.

5. Desempenho
 - Desenvolvido para rodar em uma grande agregação de servidores para um website que é acessado milhões de vezes por dia;
 - Software escalavel para mostrar dados salvos no banco de dados.

6. Suportabilidade
 - O código é totalmente aberto;
 - Disponivel para dispositivos moveis com sistema Android ou iOS.

7. Privacidade
 - Somente se o usuario ativar durante a configuração do aplicativo ou via Habilitar coleta de dados no menu Configurações. Para usuários autorizados, o aplicativo rastreará algumas das ações e enviará relatórios de falhas. Em nenhum caso as informações serão compartilhadas com terceiros.
