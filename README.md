# Introdução a HTML5 e CSS3
###### Digital Innovation One
---

## Introdução:
![HTML5](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFd_5HLVA4Dj0GzUmGLxVcpeFN9kLU-j-L9g&usqp=CAU)

**Objetivos:**
1. História e estrutura básica;
2. Semântica;
3. Principais elementos HTML;

**Requisitos**
- [x] Editor de texto
- [x] Browser
---

## Definição:
O HTML1 foi criado em 1991 pelo físico britânico, cientista da computação e professor do MIT [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/). Desde 1991 surgiram 5 versões:
Versões do HTML | Ano de Criação
:-------------: | :-------------:
HTML1 | 1991
HTML2 | 1995
HTML3 | 1997
HTML4 | 1997
HTML5 | 2014

## Elemento:
Para entendermos como funciona o HTML, primeiramente precisamos entender como funicona o _elemento_, pois ele é a base do HTML.
>TUDO dentro de um documento/arquivo .html é um elemento.

Um elemento HTML começa com uma _**tag** de abertura_ e depois escrevemos qual vai ser o **tipo de elemento** _(o que esse elemento vai fazer na tela)_. Essa **tag pode ter um _atributo_**_(esse atributo pode mudar uma funcionalidade, ou aparência, ou seja, informar alguma coisa ao navegador)_. Temos o **conteúdo do elemento** e por fim a **tag de fechamento**.

* Exemplo:
>Imagens de exemplo com o elemento _p_ (paragraph).

![Tag do elemento p](https://www.chiefofdesign.com.br/wp-content/uploads/2018/05/estrutura-de-um-elemento-html-768x398.jpg)

![Anatomia de um elemento HTML](https://media.prod.mdn.mozit.cloud/attachments/2014/11/14/9345/99516bbeb470af58b608d17bb30e53e6/grumpy-cat-attribute-small.png)

## Estrutura básica:
Depois de conhecer o elemento HTML, podemos conhecer também a estrutura. 
>A estrutura básica de um documento HTML é como a que está logo a baixo:

~~~HTML
<!DOCTYPE html> <!--Não é um elemento HTML mas informa ao navegador que, o que está sendo escrito é um texto em HTML5-->
<html><!--Começo de um documento HTML-->
  <head> 
    <meta> <!--Meta informações servem para os mecanismos de busca dos navegadores e bots indexarem a página da forma que definimos nas meta tags-->
    <title></title><!--Título que aparece na aba do Navegador-->
  </head>
  <body>
      <!--Conteúdo que aparece na página-->
  </body>  
</html> 
~~~
---

## Exercício:
>Criaremos a estrutura básica para o nosso site.
