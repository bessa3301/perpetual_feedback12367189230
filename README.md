# Introdução
O objetivo deste documento é alinhar o entendimento entre as partes, a respeito do diagnóstico da solução. Tendo como base o código atual e a narrativa do cliente, realizamos uma análise por tópicos, visando delimitar o escopo a ser tratado no desenvolvimento.

# IMPORTANTE
Esta análise foi baseada nas informações obtidas pelas primeiras reuniões. Após aceite da proposta, serão definidas as reuniões de escopo baseadas em metodologia ágil, onde serão definidos os tipos de entregáveis, seus respectivos SLA's e os responsáveis (tanto contratante como contratada).

Definição
Web app para pós venda
Facil de usar para logistas
O sistema retornar metricas (NPS) para os lojistas
Logista poder identificar Leads
Integração com serviços atuais (API)
Logista poder adicionar usuarios
Criação de base de dados de clientes existentes

Minhas sugestões para este projeto:
Aumento na estrutura de segurança com Sistema encriptação de dados mais atualizada e robusta.
Atualização das tecnologias utilizadas no projeto anterior para mais atuais.
Mudança na paleta de cores para uma tendência de experiência do usuário.
Técnicas de interatividade como gamificação para obter informações dos clientes.
Criação da estrutura interna para API.
Criação de níveis diferentes de acessos para usuários permitindo a comercialização de diferentes planos.
Melhora na estrutura e coleta de dados.
Entrega e desenvolvimento do projeto por versões, sendo a próxima versão 2.0.1.

O Estado Atual do Projeto:
pepe is confused

[ Visible Confusion ]

Pontos Positivos
O site funciona;

O projeto atual pode servir como um rascunho bem completo, embora as boas práticas de desenvolvimento ágil indiquem ganho de segurança, performance e qualidade refazendo o código.

O esquema de funcionalidade já está melhor demonstrado, o que salva tempo na arquitetura de sistema;

Pontos de melhoria
Corrigir redundâncias no código

Corrigir vulnerabilidades de segurança

Reiniciar desenvolvimento a partir de frame mais moderno, pois não seria prático lidar com a cascata de erros ao modificar o código ja existente;

Arquitetura atual não compatível com as funcionalidades propostas;

Páginas de erro em Html puro sem customização e não condizente com a imagem profissional que a empresa deseja passar ao seu cliente.

SEO inexistente

Comentários:
Apesar de estar evidente que foi um projeto rápido o que poderia impactar uma entrega de melhor qualidade, o uso de tecnologias inferiores, e ultrapassadas, mostram necessidade de entendimento da equipe de requisitos do projeto com as funcionalidades pedidas pelo cliente. Dar a importância para os requisitos e ter muito claro as funcionalidades desejadas, criando documentações e discutindo a experiência do usuário são etapas fundamentais para um projeto de sucesso.

E agora? Como o projeto pode correr? Abaixo  exemplo prático:

Atualmente, o projeto está escrito singularmente em PHP, HTML e alguns snippets de CSS e Javascript. O PHP domina a maior parte do projeto, e apesar de ser uma linguagem forte, o fato de ela ser muito perdoável, gera muita discussão nas comunidades de desenvolvedores, em especial no meu ponto de vista, nos times que participam de competições de hacking na DEFCON.

Abaixo você verá uma mesma senha, com algumas simulações de como seria um resultado da encriptação, e a dificuldade de acesso forçado (a dificuldade e medida pelo tempo médio que levaria para a senha ser quebrada):
Senha de referência:
joaoLUIZ

22 Minutos

Senha com encriptação atual:
am9hb2x1aXo=

34 mil anos

Senha com encriptação SHA3 militar (que gostaria de implantar)
A5E9539372DDB2F96CE75E6877C48B2758DD6FBA95B1526B13013631E085F92031324C87C04A7B14300009DFFD8FD5DAA4F2BC7FCA667DBC08B076946D4B9EE6

12,751,349,217,300,716,000,000,000,000 anos

Encriptação de camadas:

senha inicial: joaoLUIZ

etapa1:70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a384587c7dc4603ff7ca12e

etapa2:BC7CB7C45FE67C541449A95C0FA2BB43E3DDFF01

etapa3:E0BFC36E26E8EFC7E380BA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0

etapa4:E0BFC36E26E8EFC7E380B70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a3845 87c7dc4603ff7ca12eA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0

Acima de 10^100 mil anos / Encriptação militar

Espero que as dúvidas tenham sido sanadas e estaremos a disposição para definir as próximas etapas pós contrato.

=))

Gabriel Bessa - Developer.

Hosted with blue_heart @ github






# OBSERVAÇÕES E FEEDBACK DO WEB APP ATUAL

## Introdução

Decidi fazer a analise por tópicos, assim podendo me aprofundar em um assunto especifico, e facilitando a navegação dos tópicos.

### [IMPORTANTE](#definicao)

Esta analise e baseada em nosso cafe, entao afim de prover mais detalhes dos quesitos que estou avaliando, estou listando abaixo, o que eu entendi que seria a necessidade de voces nesse momento.

## Definicao

- Web app para pós venda
- Facil de usar para logistas
- O sistema retornar metricas (NPS) para os lojistas
- Logista poder identificar Leads
- Integração com serviços atuais (API)
- Logista poder adicionar usuarios
- Criação de base de dados de clientes existentes

### Minhas sugestões para este projeto:

- sistema de acesso a database mais simplificado
- encriptação multi etapas + TLS
- Ultiliazao de dados em .JSON
- atualização das tecnologias ultilizadas no projeto anterior para mais atuais.
- mudança na paleta de cores
- obtencao de dados dos clientes atraves de gameficação, e outras atividades interativas a serem desenvolvidas.
- Criação da estrutura interna (serverside) para ultilização de API e para integração do proprio sistema, por desenvolvedores dos clientes.
- Criação de planos, com diferentes precos e diferentes profundidades no acesso do sistema
- Criação de um plano free ou trial de 15 dias (aproximadamente)
- Criação de cookies próprios, para aumentar a eficiência na coleta e validação de dados.
- mudança da interface de usuário, e utilização de API´s (Open Source e futuramente pagas) para aceleração escalar no preenchimento de formulários.
- Entrega e desenvolvimento do projeto por versões, sendo a próxima versão 2.0.1.

# O Estado Atual do Projeto:

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fsteemitimages.com%2F0x0%2Fhttps%3A%2F%2Fsteemitimages.com%2FDQmXpJLUC3tJg5PiBpDQvCyGWPmQWWNeA9Lw5sJksxiJABT%2Fimage.png&f=1&nofb=1" alt="pepe is confused" style="width:300px;"/>
<p></p>

 `[ Visible Confusion ]`

### Pontos Positivos
* O site funciona;

* O projeto atual pode servir como um rascunho bem completo

* o esquema de funcionalidade ja esta melhor demonstrado, o que salva tempo na arquitetura de sistema;

### Pontos Negativos
* Redundancias no codigo, provavelmente devidas a ultilização direta de template;

* tamanho para um projeto inicial, precisa de simplificação;

* vulnerabilidades de segurança, tambem devidos ao desenvolvimento inicial deste projeto;

* necessidade de refazer a estrutura, pois nao seria pratico lidar com a cascata de erros ao modificar o codigo ja existentes;

* arquitetura atual nao compativel com as funcionalidades propostas;

* paginas de erro em Html puro, sem customizacao e nao condizente com a imagem profissional com a qual creio ser seu objetivo passar;

* SEO inexistente

* Template do CodeIgniter desatualizada, e nao ultilizada completamente;

### Comentarios:

Apesar de estar evidente que foi um projeto rapido, creio que nao foi um trabalho essencialmente ruim do desenvolvedor da versao atual, porem, o uso de tecnologias inferiores, e ultrapassadas, me faz crer que o mesmo **talvez** nao esteja familiarizado com as tecnologias que este projeto em especial necessita, logo o contrato que estamos visando ser de demasiada importancia.
___

# E agora? Como o projeto pode correr?

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fpa1.narvii.com%2F6877%2Fe63afeba7fde46e0cdc6b2ee65c527f70cbef8b8r1-1170-1050_hq.gif&f=1&nofb=1" alt="fast boiii" style width=300px>
<p></p>

`Abaixo voce encontrara os topicos do desenvolvimento, afim de facilitar a leitura e entendimento.`

## controle de versão
Entregar atualizacoes para um projeto como este, requer um metodo, afinal ele sempre estara em desenvolvimento, melhora e crescimento;

**O processo funcionara assim:**
1. A partir da versao atual, sao encontrados os pontos que devem ser melhorados;
1. A partir da lista de erros ou mudancas, sao pesquisados os metodos para implementacao;
1. Fase de desenvolvimento e testes (para um web-app, funcionalidade atraves de browsers e sistemas operacionais e essencial, pois a portabilidade deve ser um dos fatores de venda do servico)
1. Entrega na plataforma, sempre sob observacao para consertar possiveis [Bugs](https://www.tecmundo.com.br/seguranca/213-o-que-e-bug-.htm)

## criptografia, segurança e exemplos.

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.impulsecreative.com%2Fhs-fs%2Fhubfs%2FCat%2520typing.gif%3Fwidth%3D513%26name%3DCat%2520typing.gif&f=1&nofb=1" alt="pc_kitty" style width=300px>
<p></p>

Seguranca de dados e essencial, e como este projeto conta com muita manipulacao dos mesmos, para dashboards, analises e muito mais, so que para isso, alguns cuidados extras devem serem tomados. Encriptação funciona muitas vezes como uma cebola, com varias camadas, uma dentro da outra, criando varias etapas, e niveis diferentes de seguranca.

Atualmente, o projeto esta escrito singularmente em **PHP, HTML** e alguns snippets de **CSS e Javascript**. O **PHP** domina a maior parte do projeto, e apesar de ser uma linguagem forte, o fato de ela ser muito perdoavel, gera muita discussao nas comunidades de desenvolvedores, em especial no meu ponto de vista, nos times que participam de competicoes de hacking na DEFCON.

**Em outras palavras**, confiar toda a fundacao da seguranca em uma unica framework(CodeIgniter) com o **PHP** pode ser uma implementacao ineficiente. O que eu recomendaria e o uso de mais linguagens, e metodos, e da costumizacao da parte de servidor para dificultar ainda mais o acesso de informacoes protegidas via ataques virtuais.

Como foi comentado o uso de API em um futuro proximo, creio que seria de alto proveito, ultilizar tecnologias mais atuais como o **Node.JS**, elementos do **Flask, angular, materialize, Vue** e ferramentas como **SALT** entre outras mais. Tambem tenho como objetivo, deixar o projeto mais leve, afinal sua estrutura hoje, poderia ceder a um **ataque de computacao quantica**, que hoje pode se ter acesso bem facilmente, e com um baixo custo.

`exemplo`

#### abaixo voce vera uma mesma senha, com algumas simulacoes de como seria um resultado da encriptação, e a dificuldade de acesso forcado (a dificuldade e medida pelo tempo medio que levaria para a senha ser quebrada):
<p></p>

##### Senha de referencia:
> joaoLUIZ

22 Minutos

##### Senha com encriptação atual:

> am9hb2x1aXo=

34 mil anos

##### Senha com encriptação SHA3 militar (que gostaria de implantar)

> A5E9539372DDB2F96CE75E6877C48B2758DD6FBA95B1526B13013631E085F92031324C87C04A7B14300009DFFD8FD5DAA4F2BC7FCA667DBC08B076946D4B9EE6

12,751,349,217,300,716,000,000,000,000 anos

Encriptação de camadas:

> senha inicial: joaoLUIZ


`etapa1:70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a384587c7dc4603ff7ca12e`

`etapa2:BC7CB7C45FE67C541449A95C0FA2BB43E3DDFF01`

`etapa3:E0BFC36E26E8EFC7E380BA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0`

`etapa4:E0BFC36E26E8EFC7E380B70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a3845
87c7dc4603ff7ca12eA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0`

**Acima de 10^100 mil anos / Encriptação militar**

## API, e Integração.

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fi0.wp.com%2Fmanukahoneyusa.com%2Fwp-content%2Fuploads%2F2015%2F08%2FDollarphotoclub_57694142.jpg&f=1&nofb=1" style width=300px>
<p></p>

`API`

Uma API funciona como um mordomo, voce faz um pedido, e ele(a) anota seu pedido, vai ate a *cozinha*, e depois traz o que voce pediu. Nesse projeto creio que o uso de API's para complemetar o preenchimento de formulários por usuarios seria benefico, enquanto o web app ainda nao esta pronto para esse tipo de desenvolvimento.

Para desenvolver a API do PERPETUAL, sao dois trabalhos, o de desenvolver a **parte pratica**, funcionalidades e integracoes, e o da criacao da **Documentacao**, um livro online que da instrucoes de como usar a API para desenvolvedores de outras empresas, e parceiros que queiram usar a ferramenta integrada a um sistema externo.

`DB - DATABASE`

Usar uma database apropriada para o projeto e muito essencial. A database e o cerebro do projeto, ela deve poder pensar, guardar informacoes, e se adaptar da melhor maneira. Por isso, sugeri o uso da **MongoDB**, porem minha observacao se atem mais a ultilizacao de uma database que seja leve, e bem objetiva, nao criando diretorios desnecessarios, a ao longo prazo lentidao, junto a possiveis periodos com demanda de manutenção especializada.

## frameworks e atualização

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2Fd31vTpVi1LAcDvdm%2Fgiphy.gif&f=1&nofb=1" style width=300px>
<p></p>

Cores, aparencia, ultilizacao, e experiencia. Tudo que um usuario busca quando usa um produto, e o que tambem nos leva (desenvolvedores), a ultilizar frameworks. Elas facilitam o desenvolvimento, porem devem ser usadas com cautela, afim de nao apenas clonar o trabalho. Para este projeto com a PERPETUAL, existe a demanda de ter uma interface que deixe espaco para a experiencia do usuario `UI/UX` com graficos e botoes interativos, descomplicada, e que idealmente **nao requeira treinamento**(seja facil mesmo, *mesmo!*).

Decidi misturar elementos do **React Mobile, materialize** e usar a base do **Vue.js**, focando na velocidade do carregamento, a compatibilidade com varios browsers, e a escalabilidade (poder mudar e melhorar o codigo no futuro), alem de eu poder vetores escalaveis no desenvolvimento da interface.

## Gameficação

Uma das vantagens de estar com tecnologias atuais pode ser observada na criacao de jogos ou conteudos gameficados para obtencao de dados, assim vendendo a experiencia para o consumidor final.

<img src="https://proxy.duckduckgo.com/iu/?u=http%3A%2F%2Forig11.deviantart.net%2Fb124%2Ff%2F2015%2F281%2F0%2F6%2Fpacman_loop_by_pxlflx-d9cczgw.gif&f=1&nofb=1" style width=300px>

### Jogue um exemplo agora, clicando [AQUI](http://pacman.platzh1rsch.ch)


## **Ideias:**

* Criacao de planos com diferentes niveis de acesso no futuro, e tambem acomodacao de dados apropriada para clientes grandes.

* Criacao de uma versao trial, ou algo do genero "dinheiro de volta em 30 dias", para encorajar usuarios novos a experimentar.

=))




Gabriel Bessa - Developer.

Hosted with :blue_heart: @ github.
