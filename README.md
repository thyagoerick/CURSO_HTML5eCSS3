# Introdução a HTML5 e CSS3

###### Digital Innovation One

---

## Introdução

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

### Definição

O HTML1 foi criado em 1991 pelo físico britânico, cientista da computação e professor do MIT [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/). Desde 1991 surgiram 5 versões:
Versões do HTML | Ano de Criação
:-------------: | :-------------:
HTML1 | 1991
HTML2 | 1995
HTML3 | 1997
HTML4 | 1997
HTML5 | 2014

### Elemento

Para entendermos como funciona o HTML, primeiramente precisamos entender como funicona o _elemento_, pois ele é a base do HTML.
>TUDO dentro de um documento/arquivo .html é um elemento.

Um elemento HTML começa com uma _**tag** de abertura_ e depois escrevemos qual vai ser o **tipo de elemento** _(o que esse elemento vai fazer na tela)_. Essa **tag pode ter um _atributo_**_(esse atributo pode mudar uma funcionalidade, ou aparência, ou seja, informar alguma coisa ao navegador)_. Temos o **conteúdo do elemento** e por fim a **tag de fechamento**.

- Exemplo:

>Imagens de exemplo com o elemento _p_ (paragraph).

![Tag do elemento p](https://www.chiefofdesign.com.br/wp-content/uploads/2018/05/estrutura-de-um-elemento-html-768x398.jpg)

![Anatomia de um elemento HTML](https://media.prod.mdn.mozit.cloud/attachments/2014/11/14/9345/99516bbeb470af58b608d17bb30e53e6/grumpy-cat-attribute-small.png)

### Estrutura básica

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

### Exercício

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
<section>
<!--Representa uma seção genérica de conteúdos-->

<header>
<!--Representa o cabeçalho de uma página, ou de uma seção etc...-->

<article>
<!--Representa um conteúdo relevante dentro da página-->

<aside>
<!--Representa um conteúdo relacionadp ao conteúdo principal da página (normalmente uma "barra lateral")-->

<footer>
<!--É o rodapé da página, mas também pode ser o rodapé de uma section, ou de um article etc-->

<h1>-<h6> 
<!-- Não foram ciados na versão 5, mas servem bem ao propósito de trazer semântica, porque eles representam a importância de um título dentro de uma página.
A única regra é que deve haver apenas um h1 por página-->
~~~~

### Exercício

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
>> _blank: abre a página em uma nova janela/aba;_self: abre a página
> na mesma janela; _parent: abre a página na mesma janela do link;
>_top: cancela todos os demais frames e abre a nova página no mesmo
> navegador.

### Exercício

>Adicionar um texto a nossa "postagem" e alguns links dentro desse texto.
---

### Imagens

São elementos de tag sem fechamento.

~~~~HTML
<img>

<img src="img/avatar.jpg">

<img alt="Foto de Thyago Erick">
~~~~

Possui apenas 2 atibutos:

**_src_:**
>**Source**(Fonte): É obrigatório, podendo ser a localização da imagem em um diretório próprio ou em outro lugar.

**_alt_:**
>**Alt Text**(texto alternativo): Não é obrigatório, mas é recomendado para melhorar a acessibilidade. Ele mostra a descrição da foto quando ela não é carregada e leitores de tela usam essa descrição para mostrar aos usuários o que a imagem significa.

### Exercício

>Adicionar uma imagem ao cabeçalho da página e uma imagem à "postagem".
---

### Listas

Listas servem para agrupar coleções de itens.

~~~~HTML
Lista: (É uma tag composta)
<ul> 
<!--Representa um item na lista em que a ordem dos itens NÃO É importante-->

<ol> 
<!--Representa um item na lista em que a ordem dos itens É importante. E podem ser representados ou por números, ou letras (em ordem alfabética ou algarismos romanos)-->

Elementos de dentro da lista:
<li>
~~~~

### Exercício

>Adicionar uma lista de contatos ao rodapé
---

## Introdução

![CSS3](https://armyyazilim.com/wp-content/uploads/2019/10/css.png)

**Objetivos:**

1. O que são seletores;
2. Conceitos básicos;
3. Principais seletores CSS;

**Requisitos**

- [x] Editor de texto
- [x] Browser
- [x] Ter conhecimento em HTML5
---

Por causa da criação do HTML a necessidade de formatar páginas ficou 
evidente, então **em 1996 foi criada a linguagem de estilos que conhecemos por _CSS_**

Sua sintaxe é bem simples, básicamente criamos **regras de estilo** para
elementos ou grupos de elementos.

---

## 1. O que são seletores

![RegraCSS](https://pensandonaweb.com.br/content/images/2014/Aug/css-rule-structure.png)

> De a cordo com a imagem a cima é possível perceber que seletores são apenas elementos HTML.
> Na imagem vemos uma regra para o seletor h1, porém poderia ter mais de um elemento que usaria da mesma regra.

- Para isso poderíamos fazer da seguinte forma:

~~~~CSS
h1, a, p, h3{
  color: #333;
  font-size: 12px;
  text-align: center;
}
~~~~

Os todos os elementos (HTML5)/ seletores (CSS3): **a**, **p**, **h3** e 
**h1** fazem uso da mesma regra CSS separados/listados por **,**(vírgula).

---

### ID x Classe

Anteriormente, vimos uma como uma regra CSS pode alterar vários
elementos HTML diretamente.
Mas isso significa que qualquer elemento que seja de um daqueles tipos vai ter a mesma aparência.

Para ficar mais claro, vamos lembrar do nosso site, lá temos vários "header's", mas algumas vezes não queremos que quando editarmos um "header" todos os outros fiquem com a mesma formatação. Aí que entra o uso dos ID's e Classes.

> O seletor que vimos anteriormente é um seletor de **tipo/tag**
> pois ele representa um elemento HTML.
> Mas **_os ID's e Classes podem representar quaisquer tipos de elementos_**.

- No **HTML** declaramos as classes e id's como no trecho a baixo:
~~~~HTML
<header id="header" class="header"></header>

<header class="header"></header>
~~~~

- No **CSS** declaramos as classes e id's como no trecho a baixo:
~~~~CSS
/*Classe*/
.header{
  padding: 10px
}

/*ID*/
#header{
  padding: 15px
}
~~~~

> Temos precedência de seletores: **Classe** > **ID** > **Tag**
>> Isso significa que se um elemento tem seletores de tag e de classe, por exemplo, as regras que irão aparecer primeiro serão as da classe e depois a da tag, se um elemento tem regra de classe e regra de tag em que há mesma propriedade está sendo modificada de formas diferentes a que prevalecerá será a com maior significado que no caso é a modificação da classe.

- _Exemplo_: a regra de tag coloca a cor como vermelha e a regra de classe coloca como amarela; a cor amarela será a que ficará.
---

## 2. Conceitos básicos

Quando estamos fazendo o leiaute de um site, o navegador
representa cada elemento HTML com uma caixa retangular, e chamamos isso de **_box model_** e com CSS conseguimos alterar a aparência dessa caixa.

### Box model

O _box model_ tem 4 áreas: (da mais externa a mais interna)

1. margem;
2. borda;
3. padding;
4. conteúdo;


Box Model |
:--------: | 
![Box Model](https://miro.medium.com/max/724/1*sKnLrT1TtqWDZg7GWoBCow.png) |

- **Margin**: São os espaçamentos entre os elementos;
- **Border**: Circundam o padding e o conteúdo;
- **Padding**: É o espaçamento entre a borda e o conteúdo;
- **Content**: Pde ser um texto, um vídeo ou uma imagem.

### Exercício

>Para enxergarmos o box-model vamos adicionar cores e bordas e alguns elementos.
---

## Estilizando elementos 

### Padding e Margin

Podemos atrbuir tamanhos diferentes para cada lado do padding e da margin, e temos algumas formas de fazer isso;


~~~~CSS
.post{
  padding: 10px 5px; 
  /*
  10px = parte superior e inferior (eixo y)
  5px  = lado esquerdo e direito (eixo x)
  */
}         

.post{
  padding: 15px 10px 5px 0; 
  /*
    Temos um valor para cada lado:
    15px = topo;
    10px = direita;
    5px  = parte inferior;
    0 =  esquerda (quando temos o valor 0 não precisamos usar unidade)
  */
}  

.post{
  padding-top: 15px;
  padding-right: 10px;
  padding-bottom: 5px;
  padding-left: 0; 
  /*
    Usando valores específicos para cada variação da propriedade.
    Isso é mais usado quando temos um padding ou uma margin que tem 3 lados iguais e só um diferente
  */
} 
~~~~

### Background 

~~~~CSS
.post{
  background-color: green;
  background-image: url("caminho/imagem.estencao");
  background-position: top;
  /*
    background-color e  background podem alterar a cor de fundo do elemento;
  */
}
~~~~

### Border

~~~~CSS
.post{
  border: 3px     solid   blue;
  /*      largura estilo  cor*/ 
  /*
    solid = aparência sólida
    dotted = pontilhada
    dashed = trecejada
  */ 
 
}

.post{
  border-top: 15px dotted green;
  border-right: 10px dashed pink;
  border-bottom: 5px solid purple;
  border-left: 2px dotted cyan;
}


.post{
  border: 3px solid grey;
}
/*Caso não queira só a propriedade border para setar todos os valores, podemo decalarar as propriedades separadamente*/
.post{
  border-width: 3px;
  border-color: grey;
  border-style: solid;
}

/*
E ainda podemos ser mais específicos ainda colocando o lado que queremos mudar antes da propriedade separadamente
*/
.post{
  border-top-width: 3px;
  border-top-color: blue;
  border-top-style: solid;
  /*aqui estamos moditicando apenas o topo da borda*/
}
~~~~

### Border-radius
Ele permite arredondar os cantos de um elemento.
- border-radius: 10px; (_altera todos os cantos de um elemento_)
- border-radius: 50%; (_deixa um elemento quadrado redondo_)
- border-radius: 10% 20%;    
-     border-radius: 10%   20%      15%        22%;
                     topo  direita  inferior   esquerda

---

## Estilizando textos 
Podemos usar as fonts da Web ou as instaladas da nossa máquina.

### font-family

> Web safe fonts, são chamadas assim pois se encontram na maioria dos dispositivos;

~~~CSS
#title{
  font-family: Verdana;
}

.post_title{
  font-family: Verdana, Arial;
  /*Caso a primeira fonte não funcione a segunda entra como backup*/
}
~~~

### font-size
Altera o tamanho do nosso texto, existem algumas unidades de tamanho, porém, aqui só vamos usar o *pixel*.
~~~CSS
#title{
  font-size: 30px;
}

.post_title{
  font-size: 10px;
}
~~~

### font-style
Altera a aparência do nosso texto
~~~CSS
#title{
  font-style: normal;
  /*O valor "normal" é  padrão, então ele vai mostrar a fonte do jeito que ela foi desenhada*/
}

.subtitle{
  font-style: italic; /*muda a fonte para um pouco mais inclinada*/
~~~

### font-weight
Alterao peso do nosso texto
~~~CSS
#title{
  font-weight: normal;
  /*O valor "normal" é  padrão, então ele vai mostrar a fonte do jeito que ela foi desenhada*/
}

.subtitle{
  font-weight: bold; 
  /*deixa a fonte em negrito*/
}
~~~

### text-transform

Ele alterna o texto em maiúsculas e minúsculas
~~~CSS
#title{
 text-transform: uppercase;/*caixa alta*/
}

.subtitle{
  text-transform: lowercase;/*caixa baixa*/
}
  
.post_title{
  text-transform: capitalize;/*todas as iniciais das palavras maúsculas*/
}
~~~

### text-decoration

É muito usado para dar destaque em algum texto, pois ele coloca linhas.
~~~CSS
#title{
 text-decoration: underline;
 /*coloca uma linha a baixo da palavra*/
}

.subtitle{
  text-decoration: overline;
  /*coloca uma linha a cima da palavra*/
}
  
.post_title{
  text-decoration: line-through;
  /*coloca uma linha no centro da palavra, cortando-a no meio*/
}
~~~
---

## Estilizando listas
Existem listas ordenadas e listas não ordenadas.
Para alterar os marcadores dessas listas usamos o **list-style-type**.

### list-style-type
~~~CSS
ul{
 list-style-type: square;
 /*muda o marcador padão para um quadrado*/
}

ol{
  list-style-type: upper-roman;
  /*Lista ordenada para algarismo romano em maiúsculo*/
}
  
ul{
  list-style-type: "\1f44D";
 /*muda o marcador padão para um simbolo (emoji de um joinha)*/
}
~~~

### list-style-image
Podemos adicionar imagens como marcadores
~~~CSS
ul{
 list-style-image: url("imagem.extensão");
 /*muda o marcador padão para um quadrado*/
}
~~~
---
## Cascata

O CSS funciona como uma cascata, então é possível compor uma hierarquia de classes relacionadas, com o objetivo de criar formatações para áreas especificas, e permitir a hierarquia correta de propriedades.

- Exemplo:
~~~HTML
<ul class="contacts_list">
  <li>
      <a class="email" href="mailto:thyago123gois@gmail.com">thyago123gois@gmail.com</a>
  </li>
  <li>
      <a href="https://www.linkedin.com/in/thyagoerick" target="_blank">LinkedIn</a> 
  </li>
</ul>
~~~

>No exemplo a cima temos que a tag **ul** que é uma *tag composta* pois depende da tag **li** para existir, possui dois *li's* e dentro de cada um temos um conteúdo, no primeiro li temos uma tag **a**  com a classe _"email"_ e dentro do segundo temos apenas uma âncora (sem classe).

>A cascata funciona quando usamos esse cascateamento dos elementos para uma edição mais específica, logo se quisermos fazer alguma alteração apenas no link com a com a classe *"email"*, podemos fazer como mostrado a baixo:

~~~CSS
.contacts_list li .email{
  color: blue;
}

/*Aqui só editamos o elemento que possui a classe "email" que fica dentro de algum li, e que esse li fica dentro de algum elemento que tem a classe "contacts_list"*/
~~~
---

## Propriedades de dimensões e alinhamento
>Valores declarados em px ou %
- **Width**: Largura;
- **Height**: Altura.

- **Max-width**: largura máxima que determinado elemento pode ter;
- **Max-height**: altura máxima que determinado elemento pode ter.

- **Margin**: Serve para colocar espeçamentos entre elementos;
> A propriedade **margin** tem o valor **auto**, que serve para alinhar algum elemento altomaticamente.

- **Taxt aling**: Serve para alinhar textos;
  - right: alinha à direita;
  - left: alinha à esquerda;
  - center: alinha ao centro;
  - justfy: alinha justificado.