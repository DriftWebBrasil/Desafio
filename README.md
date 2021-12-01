# Desafio Drift

## Por que Wordpress?
O Wordpress é um CMS (Sistema de gerenciamento de conteúdo), presente em [mais de 40% dos sites de toda a internet](https://w3techs.com/technologies/details/cm-wordpress). É conhecido por ser extensível através de Temas e Plugins, agilizando o desenvolvimento de sites. Inicialmente foi criado para uso em Blogs e cadastro de Posts, mas ao longos dos anos ele conquistou mais áreas, como o E-commerce através do WooCommerce. Por meio do seu painel, o cliente pode ter controle sobre o conteúdo do site, alterando textos, imagens, etc.

## Como usamos o Wordpress?
Aqui na Drift trabalhamos com um tema próprio. Ele contém as funcionalidades mais básicas, ficando a encargo do desenvolvedor criar os templates com PHP/HTML e fazer a estilização. Quanto aos plugins, usamos o menos possível. O nosso objetivo é entregar um site performático para o cliente 🚀🚀🚀

## Qual é o objetivo do teste?
O candidato será avaliado quanto a estruturação e estilização de três telas, utilizando as funções básicas do Wordpress. As telas são:
- Home: página de entrada do site, contém uma imagem e um texto. 
- Blog: página com a lista de posts cadastrados pelo painel.
- Post: página com o conteúdo de um único post cadastrado pelo painel

## O que será avaliado?
- HTML: Uso correto das tags, usando tags semânticas sempre que possível (section, article, main)
- CSS: Flexbox e layout responsivo.
- JS: Criação de componentes interativos (menu burger)

## Detalhes do projeto
O repositório contém o tema que utilizamos, com algumas funcionalidades removidas. O candidato poderá baixar o tema e utilizar localmente, ou instalar em um servidor que será provido para a realização do teste (o qual já estará com o WordPress instalado). Se fizer o projeto localmente, faça questão de usar o PHP 7.4, pois não há suporte ainda para o 8.

Para a criação das páginas, você deve criá-las através do painel com os seguintes nomes: "Home" e "Blog". E então, para criar o template, crie dois arquivos no tema: "page-home.php" e "page-blog.php". Para estilizar a página do artigo, use o "single.php".  O 3º link de referência explica como funciona esse redirecionamento de arquivos no WordPress. 

Não se esqueça que o Header e o Footer são os mesmos para todas as páginas, então edite os arquivos "header.php" e "footer.php" respectivamente. 

## Conclusão
O candidato terá 5 dias para conclusão do teste. Ao concluir, o avalidor deve ser notificado. Ele pode usar o servidor disponibilizado, ou se preferir, enviar os arquivo dos site e uma cópia do banco de dados para o e-mail aneke@driftweb.com.br. Se houver dúvidas, sinta-se a vontade para entrar em contato com o avaliador, mas lembre-se que o Google é seu melhor amigo 😁

### Referências
- https://codex.wordpress.org/pt-br:O_Loop
- https://codex.wordpress.org/Function_Reference
- https://developer.wordpress.org/themes/template-files-section/page-template-files/#page-templates-within-the-template-hierarchy
