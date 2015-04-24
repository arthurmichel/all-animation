All Animation
=============

All Animation.css is a set of animations amusing to let your sexiest design. Are cross-browser animations that will give emphasis to your pages but as sliders,’s 3D effects

##[Try the demo](http://clovisdasilvaneto.github.io/all-animation/)
<a href="http://clovisdasilvaneto.github.io/all-animation/">Veja uma demo dos efeitos que este imenso framework pode fazer :D</a>


### Contribuidores:
Caso você queira contribuir com o nosso projeto, leia o arquivo: <a href="https://github.com/clovisdasilvaneto/all-animation/blob/master/contribuidores.md">contribuidores.md</a> ;)

### Como Usar:

É facil ultilizar este framework css :D, veremos passo a passo como ultilizá-lo...


### Passo 1, inclua os arquivos necessários no head, para que o framework funcione corretamente:

baixe o all animation, <a href="http://clovisdasilvaneto.github.io/all-animation/css/all-animation.css" target="_blank">clicando aqui</a>

```
<link rel="stylesheet" type="text/css" href="yourpath/all-animation.css" />
<script type="text/javascript" src="yourpath/jquery.js"></script>

```

### Passo 2, html:

```
<div id="animation"></div>

<button class="anny-class">Trigger class, go!</button>

```

### Passo 3, Jquery:

```js
$(".anny-class").click(function(){
 $("#animation").addClass("journal");
});
```

Caso queira adicionar o efeito em algum determinado tempo, é colocar um temporizador ;)

ex, colocando uma animação em um determinado elemento, depois de 2 segundos:

```js
setTimeout(function(){
 $("#animation").addClass("journal");
},2000);
```

### Atenção:

Caso você queira adicionar alguma animação em um elemento que já sofreu uma outra animação deste framework, ou queira reiniciar a animação, você terá que remover a ultima animação e inserir a sua, ex:


```js
 $("#animation").removeClass("journal").addClass("four-rock");
```


Temos várias classe no lugar da class journal, vejamos quais são:

### Especiais:

<ul>
 <li>dance</li>
 <li>journal</li>
 <li>pulse</li>
 <li>pulse-slow</li>
 <li>jamp</li>
 <li>four-rock</li>
</ul>

### Bounce:
<ul>
 <li>enter-up-bounce </li>
 <li>enter-down-bounce</li>
 <li>enter-right-bounce </li>
 <li>enter-left-bounce</li>
 <li>scale-bounce</li>
 <li>jump-bounce</li>
</ul>

### Perspective:
<ul>
 <li>tree-flip-right</li>
 <li>tree-flip</li>
 <li>tree-flip-up</li>
 <li>tree-flip-down</li>
 <li>flip-left-bounce</li>
 <li>rotate-flip</li>
 <li>flip-right-bounce</li>
</ul>

### Fading Entrances:
<ul>
 <li>flip-top</li>
 <li>flip-left</li>
 <li>flip-right</li>
 <li>flip-bottom</li>
</ul>

### Rotate:
<ul>
 <li>rotate-flip-down</li>
 <li>rotate-down-bounce</li>
 <li>rotate-out</li>
</ul>

### Agrecives:
<ul>
 <li>flash-bang</li>
 <li>bomba</li>
</ul>

Email para contato: cloves13@hotmail.com
