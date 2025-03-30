# CSS (Cascading Style Sheets)

CSS é uma linguagem de estilo utilizada para descrever a apresentação de um documento escrito em HTML ou XML. Ele controla a aparência dos elementos na página, como cores, fontes, espaçamento e layout.

## Como Funciona o CSS

O CSS funciona aplicando regras de estilo aos elementos HTML. Cada regra consiste em um seletor e um bloco de declarações. O seletor aponta para o elemento HTML que você deseja estilizar, e o bloco de declarações contém uma ou mais declarações separadas por ponto e vírgula. Cada declaração inclui uma propriedade CSS e um valor.

### Estrutura Básica de uma Regra CSS

```css
seletor {
    propriedade: valor;
}
```

## Tags e Atributos Mais Usados

### Seletor de Elemento

Aplica o estilo a todos os elementos de um tipo específico.

```css
p {
    color: blue;
}
```

### Seletor de Classe

Aplica o estilo a todos os elementos com uma classe específica. As classes são definidas no HTML com o atributo `class`.

```css
.intro {
    font-size: 20px;
}
```

### Seletor de ID

Aplica o estilo a um único elemento com um ID específico. Os IDs são definidos no HTML com o atributo `id`.

```css
#header {
    background-color: #f1f1f1;
}
```

### Propriedades CSS Comuns

- **color**: Define a cor do texto.
- **background-color**: Define a cor de fundo de um elemento.
- **font-size**: Define o tamanho da fonte.
- **margin**: Define a margem externa de um elemento.
- **padding**: Define o preenchimento interno de um elemento.
- **border**: Define a borda de um elemento.
- **width**: Define a largura de um elemento.
- **height**: Define a altura de um elemento.
- **display**: Define como um elemento é exibido (ex.: `block`, `inline`, `flex`).

### Exemplo Completo

```css
/* Seletor de elemento */
h1 {
    color: navy;
    font-size: 24px;
}

/* Seletor de classe */
.intro {
    color: gray;
    margin-bottom: 20px;
}

/* Seletor de ID */
#main {
    padding: 10px;
    background-color: lightblue;
}
```

CSS é uma ferramenta poderosa para criar páginas web visualmente atraentes e organizadas. Com a prática, você pode dominar a arte de estilizar seus documentos HTML de maneira eficaz.