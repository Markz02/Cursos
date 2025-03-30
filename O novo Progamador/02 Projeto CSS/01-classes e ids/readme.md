# Classes e IDs no CSS

## Classes

Classes são usadas para aplicar estilos a múltiplos elementos. Elas são definidas no HTML com o atributo `class` e no CSS com um ponto (`.`) seguido pelo nome da classe.

### Exemplo de Classe

HTML:
```html
<div class="container">
    <p class="text">Este é um parágrafo.</p>
    <p class="text">Este é outro parágrafo.</p>
</div>
```

CSS:
```css
.container {
    width: 100%;
    margin: 0 auto;
}

.text {
    color: blue;
    font-size: 16px;
}
```

### Descrição

- `.container`: Define um contêiner que ocupa 100% da largura e centraliza seu conteúdo.
- `.text`: Aplica a cor azul e o tamanho de fonte de 16px a todos os elementos com a classe `text`.

## IDs

IDs são usados para aplicar estilos a um único elemento. Eles são definidos no HTML com o atributo `id` e no CSS com um sustenido (`#`) seguido pelo nome do ID.

### Exemplo de ID

HTML:
```html
<div id="header">
    <h1 id="title">Título da Página</h1>
</div>
```

CSS:
```css
#header {
    background-color: #f8f9fa;
    padding: 20px;
}

#title {
    color: #343a40;
    font-size: 24px;
}
```

### Descrição

- `#header`: Define um cabeçalho com uma cor de fundo e padding.
- `#title`: Aplica a cor e o tamanho da fonte ao título da página.

## Diferenças entre Classes e IDs

- **Classes**: Podem ser reutilizadas em múltiplos elementos.
- **IDs**: Devem ser únicos dentro de um documento HTML.
