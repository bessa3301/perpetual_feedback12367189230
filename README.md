# Introdução
O objetivo deste documento é alinhar o entendimento entre as partes, a respeito do diagnóstico da solução. Tendo como base o código atual e a narrativa do cliente, realizamos uma análise por tópicos, visando delimitar o escopo a ser tratado no desenvolvimento.

### [IMPORTANTE](#definicao)
Esta análise foi baseada nas informações obtidas pelas primeiras reuniões. Após aceite da proposta, serão definidas as reuniões de escopo baseadas em metodologia ágil, onde serão definidos os tipos de entregáveis, seus respectivos SLA's e os responsáveis (tanto contratante como contratada).

## Definicao
Web app para pós venda
Facil de usar para logistas
O sistema retornar metricas (NPS) para os lojistas
Logista poder identificar Leads
Integração com serviços atuais (API)
Logista poder adicionar usuarios
Criação de base de dados de clientes existentes

## Minhas sugestões para este projeto:
Aumento na estrutura de segurança com Sistema encriptação de dados mais atualizada e robusta.
Atualização das tecnologias utilizadas no projeto anterior para mais atuais.
Mudança na paleta de cores para uma tendência de experiência do usuário.
Técnicas de interatividade como gamificação para obter informações dos clientes.
Criação da estrutura interna para API.
Criação de níveis diferentes de acessos para usuários permitindo a comercialização de diferentes planos.
Melhora na estrutura e coleta de dados.
Entrega e desenvolvimento do projeto por versões, sendo a próxima versão 2.0.1.

# O Estado Atual do Projeto:

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fsteemitimages.com%2F0x0%2Fhttps%3A%2F%2Fsteemitimages.com%2FDQmXpJLUC3tJg5PiBpDQvCyGWPmQWWNeA9Lw5sJksxiJABT%2Fimage.png&f=1&nofb=1" alt="pepe is confused" style="width:300px;"/>
<p></p>

 `[ Visible Confusion ]`

### Pontos Positivos
O site funciona;

O projeto atual pode servir como um rascunho bem completo, embora as boas práticas de desenvolvimento ágil indiquem ganho de segurança, performance e qualidade refazendo o código.

O esquema de funcionalidade já está melhor demonstrado, o que salva tempo na arquitetura de sistema;

### Pontos de melhoria
Corrigir redundâncias no código

Corrigir vulnerabilidades de segurança

Reiniciar desenvolvimento a partir de frame mais moderno, pois não seria prático lidar com a cascata de erros ao modificar o código ja existente;

Arquitetura atual não compatível com as funcionalidades propostas;

Páginas de erro em Html puro sem customização e não condizente com a imagem profissional que a empresa deseja passar ao seu cliente.

SEO inexistente

## Comentários:
Apesar de estar evidente que foi um projeto rápido o que poderia impactar uma entrega de melhor qualidade, o uso de tecnologias inferiores, e ultrapassadas, mostram necessidade de entendimento da equipe de requisitos do projeto com as funcionalidades pedidas pelo cliente. Dar a importância para os requisitos e ter muito claro as funcionalidades desejadas, criando documentações e discutindo a experiência do usuário são etapas fundamentais para um projeto de sucesso.

# E agora? Como o projeto pode correr? Abaixo  exemplo prático:

<img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.impulsecreative.com%2Fhs-fs%2Fhubfs%2FCat%2520typing.gif%3Fwidth%3D513%26name%3DCat%2520typing.gif&f=1&nofb=1" alt="pc_kitty" style width=300px>
<p></p>

Atualmente, o projeto está escrito singularmente em PHP, HTML e alguns snippets de CSS e Javascript. O PHP domina a maior parte do projeto, e apesar de ser uma linguagem forte, o fato de ela ser muito perdoável, gera muita discussão nas comunidades de desenvolvedores, em especial no meu ponto de vista, nos times que participam de competições de hacking na DEFCON.

Abaixo você verá uma mesma senha, com algumas simulações de como seria um resultado da encriptação, e a dificuldade de acesso forçado (a dificuldade e medida pelo tempo médio que levaria para a senha ser quebrada):

Senha de referência:
>joaoLUIZ

**22 Minutos**

Senha com encriptação atual:
>am9hb2x1aXo=

**34 mil anos**

Senha com encriptação SHA3 militar (que gostaria de implantar)
>A5E9539372DDB2F96CE75E6877C48B2758DD6FBA95B1526B13013631E085F92031324C87C04A7B14300009DFFD8FD5DAA4F2BC7FCA667DBC08B076946D4B9EE6

**12,751,349,217,300,716,000,000,000,000 anos**

Encriptação de camadas:

senha inicial: 
>joaoLUIZ

`etapa1:70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a384587c7dc4603ff7ca12e`

`etapa2:BC7CB7C45FE67C541449A95C0FA2BB43E3DDFF01`

`etapa3:E0BFC36E26E8EFC7E380BA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0`

`etapa4:E0BFC36E26E8EFC7E380B70ff7ae5df58c90a33f3081670ce6fddb08f48bb2a3845 87c7dc4603ff7ca12eA4EC8CC6F605EFDF530C2271420F326EFD7482B6FDB85C20A50596E61443A48FADE5FC86A4F73E4CE21FB5578A80543F878E57514D0`

**Acima de 10^100 mil anos / Encriptação militar**

Espero que as dúvidas tenham sido sanadas e estaremos a disposição para definir as *próximas etapas pós contrato*.

**=))**

Gabriel Bessa - Developer.

Hosted with blue_heart @ github
