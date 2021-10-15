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

## 1. História e estrutura básica

### Definição:
O HTML1 foi criado em 1991 pelo físico britânico, cientista da computação e professor do MIT [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/). Desde 1991 surgiram 5 versões:
Versões do HTML | Ano de Criação
:-------------: | :-------------:
HTML1 | 1991
HTML2 | 1995
HTML3 | 1997
HTML4 | 1997
HTML5 | 2014

### Elemento:
Para entendermos como funciona o HTML, primeiramente precisamos entender como funicona o _elemento_, pois ele é a base do HTML.
>TUDO dentro de um documento/arquivo .html é um elemento.

Um elemento HTML começa com uma _**tag** de abertura_ e depois escrevemos qual vai ser o **tipo de elemento** _(o que esse elemento vai fazer na tela)_. Essa **tag pode ter um _atributo_**_(esse atributo pode mudar uma funcionalidade, ou aparência, ou seja, informar alguma coisa ao navegador)_. Temos o **conteúdo do elemento** e por fim a **tag de fechamento**.

* Exemplo:
>Imagens de exemplo com o elemento _p_ (paragraph).

![Tag do elemento p](https://www.chiefofdesign.com.br/wp-content/uploads/2018/05/estrutura-de-um-elemento-html-768x398.jpg)

![Anatomia de um elemento HTML](https://media.prod.mdn.mozit.cloud/attachments/2014/11/14/9345/99516bbeb470af58b608d17bb30e53e6/grumpy-cat-attribute-small.png)

### Estrutura básica:
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

### Exercício:
>Criaremos a estrutura básica para o nosso site.

- [x] index.html

---

## 2. Semântica

Uma das maiores mudanças no HTML5 foi o  fato de poder implementar
outras tags além da "div". Porque antes o elemento padrão para a 
divisão do conteúdo era a div e ficava muito difícil de entender
o que estava escrito pois eram muitas "div's" no arquivo e para ter
uma diferenciação usavam as classes, mas mesmo assim não ajudava
tanto assim no entendimento do que estava sendo escrito.

Mas com a versão 5 do HTML foram criados novos elementos que troxeram
mais significado ao HTML.
Alguns desses elementos são:

~~~~HTML
<section><!--Representa uma seção genérica de conteúdos-->
<header><!--Representa o cabeçalho de uma página, ou de uma seção etc...-->
<article><!--Representa um conteúdo relevante dentro da página-->
<aside><!--Representa um conteúdo relacionadp ao conteúdo principal da página (normalmente uma "barra lateral")-->
<footer><!--É o rodapé da página, mas também pode ser o rodapé de uma section, ou de um article etc-->
<h1>-<h6> <!-- Não foram ciados na versão 5, mas servem bem ao propósito de trazer semântica, porque eles representam a importância de um título dentro de uma página.
A única regra é que deve haver apenas um h1 por página-->
~~~~

### Exercício:
>Continuaremos à estrutura do nosso site.
---

## 3. Principais elementos HTML

### Textos e links

#### Tags para textos

>A motivação da criação do HTML foi para criar e compartilhar textos
>e documentos

~~~~HTML
<h1>Título da página</h1>
<h2>Título da seção</h2>
<h3>Título de artigo</h3>
...
<h6></h6>

<p>Conteúdos mais extensos</p>
~~~~

#### Tags para links

Serve para interligar vários conteúdos na web.

~~~~HTML
<a>Link</a><!-- <a> == anchor == âncora-->

<a href="linkedin.com/in/thyagoerick/">LinkedIn</a>
<a href="mailto:thyago123gois@gmail.com">E-mail</a>

<a target="_blank">Link</a>
~~~~

**_href_:**
>**HTML reference**: É um hiperlink para onde a 
>âncora está apontando. 
>> Como **site**, **e-mail**
>(_para e-mails é necessário colocar o prefixo **mailto:**_),
> **telefone** (_para telefones é necessário colocar o prefixo **tel:**_).

**_target_:**
>**Alvo**: Serve para indicar como o nosso link será aberto
>> _blank: abre a página em uma nova janela/aba; _self: abre a página 
> na mesma janela; _parent: abre a página na mesma janela do link; 
> _top: cancela todos os demais frames e abre a nova página no mesmo 
> navegador.

### Exercício:
>Adicionar um texto a nossa "postagem" e alguns links dentro desse texto.
---