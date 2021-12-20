# Projeto-TCC

### O QUE É
Esse projeto e um TCC feito no termino do curso de analise e desenvolvimento de sistema na faculdade impacta de tecnologia onde ele apresenta um serviço de agendamento via Web junto com um BOT de telegram para uma barbearia chamada 'Tom Barbearia'

### A QUEM SE DESTINA / OBJETIVO
Este projeto é destina para barbearias

### INSTALAÇÃO LOCAL
• Instale python, flask e uma IDE de sua preferencia;

• Em seu servidor local baixe o projeto usando `git clone`;


### CONVENÇÕES
Convenções adotadas no ambiente de trabalho para o projeto tombarbearia:
* Regra para nome de classes e tabelas e colunas em um db: **_primeiroNome_**
* Para as tabelas devem possuir 's' no final;
* Todas as `classes` devem ser representadas por um substantivos e não um verbo: Clientes, Contatos, Perfil, Configurações etc;
* Todos os `metodos` devem ser representadas por um verbo ou frases verbais no infinitivo: salvarStatus, editarPagina, remover etc;
* Regra para nome de links: **_editar/pagina/souUmLink_**;





### BIBLIOTECAS DO PROJETO
* Usamos o [ Flight framework ](http://flightphp.com/) como framework para rotas, porque tem um desempenho melhor que o Slim Framework ou outros top de linha;

* Banco de dados SQLite e biblioteca [ Medoo ](http://sqliteonline.com). O Medoo é de longe a melhor library que ja conheci. A regra de outro é que suas clases não podem de maneira alguma ficarem dentro de classes e ou funções;

* Sistema de template: o [ Twig ](http://twig.sensiolabs.org) para gerenciar e separar com mais segurança as views, mais abaixo você encontra um tópico falando um pouco mais dessa escolha;

* A biblioteca para detectar navegador, sistema operacional e dispositivo: [ PHP Browser Detector ](https://github.com/sinergi/php-browser-detector);



### BANCO DE DADOS
Medoo é sem dúvidas a ORM mais simples que eu já pude conhecher na vida.
Você pode estudar a aplicação de login desenvolvida e consultar o guia oficial em: [ medoo.in ](http://medoo.in).

### SISTEMA DE TEMPLATE
Escolhi twig pela facilidade de aprendizado, por ter usado bastante com microframeworks também. Se você olhar uma [ folha de resumo ](https://s-media-cache-ak0.pinimg.com/originals/9b/7c/f0/9b7cf0ed69f91af8bdbf3d55ec5f893e.jpg) sobre o twig dá pra tirar muitas dúvidas, contudo, se você já está acostumado com com o Smarty por exemplo pode substituir.

----------------------------
#### SE VOCÊ CHEGOU ATÉ AQUI
Muito obrigado pela atenção

#### SOBRE O AUTOR/ORGANIZADOR
Ênio Henrique Ferreira Alves de Souza

enio.henrique12@gmail.com
