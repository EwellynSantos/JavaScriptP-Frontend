# Importando o script

É importante importar o script js de maneira correta, ou pode acarretar em problemas para a sua aplicação. O ideal é que o arquivo js seja carregado após o conteudo html estar renderizado na tela. Então temos 2 opçoes, ou importamos no fim do conteudo html, ou importamos na tag head conforme abaixo:

```html
<script src="./main.js" defer></script>
```

o segredo está na palavra defer, pois ela faz com que essa importação em específica ocorra após o carregamento do conteudo da pagina, o que facilita muito!
