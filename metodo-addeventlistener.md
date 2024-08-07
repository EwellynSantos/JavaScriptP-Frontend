# Método addEventListener

Ele é um método disponível para todos os elementos HTML e permite que registremos funções (callbacks) que serão chamadas quando um evento específico ocorrer. Segue a sintaxe:

```javascript
elemento.addEventListener(evento, callback);
```

<mark style="color:blue;">**Onde:**</mark>

* elemento: É o elemento HTML ao qual queremos associar o evento.
* evento: É uma string que representa o tipo de evento que desejamos capturar.
* callback: É a função que será chamada quando o evento ocorrer.

#### **Tipos de Eventos**

* _Eventos de clique (click)_
* _Eventos de submissão de formulário (submit)_
* _Eventos de teclado (keydown, keyup, keypress)_
* Eventos de foco (focus, blur)
