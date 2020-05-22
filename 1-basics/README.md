<div align="center" id="header">
<h1>Conceitos básicos</h1>
</div>

> Tal como outras linguagens de programação, o Javascript dispões de conceitos básicos que tornam a linguagem única. Estes conceitos são aplicados em todo e qualquer projeto desenvolvido usando a linguagem.

---

-   [Variáveis](#vari%c3%a1veis)
-   [Tipos primitivos](#tipos-primitivos)
    -   [String]()
    -   [Number]()
    -   [Boolean]()
-   [Declarações if]()
-   [Operadores Lógicos]()
-   [Escopo da variável]()

## Variáveis

> Variáveis são containers que servem para armazenar valores. Estes valores poderão ser utilizados posteriormente uma vez que foram salvos dentro de uma variável.

### Tipos de variáveis

O Javascript possui 3 tipos de variáveis, variáveis estas que possuem suas diferenças e casos de uso.

-   **var** - variável de [escopo global]() em que o seu valor pode ser alterado
-   **let** - parecida à variável do tipo _var_ porém, possui [escopo local]().
-   **const** - variável de [escopo local]() em que o seu valor não pode ser alterado.

![constletvar](../content/variables.png)

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

---

<div align="center" id="footer" >
© 2020 <br>
With ❤️ and ☕ by <br>
<a href="https://nubelson.dev" target="_blank" rel="noopener noreferrer">Nubelson Fernandes</a>
</div>
