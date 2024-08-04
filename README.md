# Acessando elementos pelo console

Utilizaremos uma maneira de acessar elementos no console do navegador.&#x20;

Para que possamos acessar apenas um elemento, podemos utilizar o QuerySelector, mas antes devemos dar um document., pois ele está referenciando o arquivo que queremos selecionar os elementos. A sintaxe é:

```javascript
document.querySelector('elemento');
```

no console já retorna o elemento a qual voce mencionou dentro das aspas, lembrando que quando se trata de classe devemos adicionar o <mark style="color:yellow;">.</mark> e quando se trata de um id, devemos utilizar o #.

<mark style="color:blue;">**O que mais?**</mark>

Deste modo podemos acessar apenas um elemento, mas e se quisermos acessar mais de um elemento? podemos utilizar o QuerySelectorAll. Não muda a sintaxe, mas o que diferencial é que ele retornará todos os elementos que possuem aquele tipo. Ex:

<div align="left">

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

</div>

Desse modo ele retorna um array com os resultados.&#x20;
