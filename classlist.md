# classList

**Adicionando uma classe**

Para adicionar uma classe a um elemento HTML, podemos usar o método `add()` do `classList`. Este método aceita o nome da classe como argumento e adiciona a classe ao elemento, se ela ainda não estiver presente. Conforme exemplo a seguir:

```csharp
const element = document.getElementById('meuElemento');
element.classList.add('minhaClasse');

```

**Removendo uma classe**

Para remover uma classe de um elemento HTML, podemos utilizar o método `remove()` do `classList`. Este método aceita o nome da classe como argumento e remove a classe do elemento, se ela estiver presente. Veja o exemplo abaixo:

```csharp
const element = document.getElementById('meuElemento');
element.classList.remove('minhaClasse');

```

**Alternando uma classe**

O método `toggle()` do `classList` permite alternar uma classe em um elemento. Se a classe já estiver presente no elemento, o método a remove; caso contrário, ele a adiciona, conforme exemplo a seguir:

```javascript
const element = document.getElementById('meuElemento');
element.classList.toggle('minhaClasse');

```

**Verificando se uma classe está presente**

Para verificar se uma classe específica está associada a um elemento, podemos usar o método `contains()` do `classList`, como no exemplo:

```javascript
const element = document.getElementById('meuElemento');
if (element.classList.contains('minhaClasse')) {
  // A classe 'minhaClasse' está presente no elemento
  // Faça algo aqui...
}

```

**Substituindo classes**

Como feito em aula, podemos substituir uma classe por outra usando os métodos `add()` e `remove()` em sequência.

```csharp
const element = document.getElementById('meuElemento');
element.classList.remove('classeAntiga');
element.classList.add('classeNova');

```

**Manipulando várias classes simultaneamente**

É possível adicionar ou remover várias classes de uma vez usando o método add() ou remove() passando vários argumentos separados por vírgula. Veja o exemplo:

```csharp
const element = document.getElementById('meuElemento');
element.classList.add('classe1', 'classe2', 'classe3');
element.classList.remove('classe2', 'classe3');
```
