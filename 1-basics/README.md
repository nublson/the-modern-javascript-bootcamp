<div align="center" id="header">
<h1>Conceitos básicos</h1>
</div>

> Tal como outras linguagens de programação, o Javascript dispões de conceitos básicos que tornam a linguagem única. Estes conceitos são aplicados em todo e qualquer projeto desenvolvido usando a linguagem.

---

-   [Variáveis](#variáveis)
    -   [Tipos de variáveis](#tipos-de-variáveis)
    -   [Criando uma variável](#criando-uma-variável)
-   [Tipos Primitivos](#tipos-primitivos)
    -   [String](#string)
    -   [Number](#number)
    -   [Boolean](#boolean)
    -   [Undefined](#undefined)
    -   [Null](#null)
-   [Undefined VS Null](#undefined-vs-null)

## Variáveis

> Variáveis são containers que servem para armazenar valores. Estes valores poderão ser utilizados posteriormente uma vez que foram salvos dentro de uma variável.

### Tipos de variáveis

O Javascript possui 3 tipos de variáveis, variáveis estas que possuem suas diferenças e casos de uso.

-   **var** - variável de [escopo global]() em que o seu valor pode ser alterado
-   **let** - parecida à variável do tipo _var_ porém, possui [escopo local]().
-   **const** - variável de [escopo local]() em que o seu valor não pode ser alterado.

![constletvar](../content/variables.png 'constletvar')

### Criando uma variável

Para criarmos uma variável em Javascript, devemos seguir a sintaxe da linguagem:

> keyword varName = value

-   **_Keyword_** é a _palavra-chave reservada_ da linguagem que indica a criação de uma nova variável
-   **_varName_** é o nome da variável, ele deve seguir algumas regras e padrões definidos para melhor legibilidade do nosso código
-   **_=_** é o sinal de atribuição, ele é usado única e exclusivamente para atribuição de valores
-   **_value_** é o valor da variável, ele pode ser qualquer coisa e vir de qualquer lugar

```javascript
var firstName = 'Nubelson';
let lastName = 'Fernandes';
const race = 'black';
```

## Tipos Primitivos

> Os tipos primitivos são os tipos básicos de dados que compõem um programa. Eles servem para indicar que tipos de tarefas podemos realizar com os dados no nosso programa.

### String

> As string são uma cadeia de caracteres (letras, números e símbolos) usadas para criar palavras, formar frases ou até textos.

Elas são úteis para armazenar dados que podem ser representados em forma de texto.

```javascript
let sayHello = 'Hello World!';
console.log(sayHello); // Hello World!
```

As strings são criadas usando as àspas (simples ou duplas), isso significa qur tudo o que estiver dentro delas, será considerado uma string.

```javascript
'Hello World';
'Eu tenho 23 anos';
```

### Number

> Este tipo de dado serve para representar valores numéricos que podem ser utilizados para realizar cálculos matemáticos, salvar a idade, peso ou altura de uma entidade, tudo o que for possível fazer com um número.

```javascript
let age = 23;
console.log(age + 1); // 24
```

### Boolean

> O Boolean é um tipo de dado que representa um valor lógico, este valor pode ser **TRUE** ou **FALSE**.

```javascript
let youNeedToSleep = true;
console.log(youNeedToSleep); // true

youNeedToSleep = false;
console.log(youNeedToSleep); // false
```

### Undefined

> O undefined representa um valor que não foi definido.

```javascript
let yourAge;

console.log(yourAge); // undefined
```

### Null

> O Null é um literal que representa um valor nulo ou vazio.

```javascript
let tokenApi = null;
console.log(tokenApi); // null
```

## Undefined VS Null

Você com certeza deve estar se perguntando qual a diferença entre o Undefined e o Null visto que os 2 não têm nenhum valor, bem, sim e não, eu explico com mais detalhe:

Sim, porque ambos não possuem um valor
Não, porque o null em sí é um valor

> A diferença entre o Undefined e o Null é que no undefined, temos a variável declarada mas **o seu valor não está definido**, já no null, **nós definimos o valor da variável** como _vazio_.

---

<div align="center" id="footer" >
© 2020 <br>
With ❤️ and ☕ by <br>
<a href="https://nubelson.dev" target="_blank" rel="noopener noreferrer">Nubelson Fernandes</a>
</div>
