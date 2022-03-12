# Caixas (Box model)

# Box Model
- Fundamental para fazer layouts para a web
- Maior facilidade para aplicar o CSS

* Você irá perceber que (quase) tudo são caixas do CSS
* Posicionamentos, tamanhos, espaçamentos, bordas, cores
* Caixa pode ficar ao lado uma da outra, ou acima
* Elementos HTML são caixas

Nesta aula falaremos sobre o conceito de caixas, já que o CSS trabalha com essa ideia de caixas, ou seja, o box model. Mas o quê exatamente é esse box model?

É uma caixa retangular. Essa caixa possui as mesmas propriedades de uma caixa 2D, e tem como propriedades:

Tamanho (largura x altura width e height, respectivamente
Conteúdo: o content
Bordas: o border
Preenchimento interno: o padding
Espaços fora da caixa: a margin

Quase todo elemento de uma página é considerado uma caixa: Posicionamentos, tamanhos, espaçamentos, bordas, cores, então, em suma, elementos HTML são caixas, assim como quase tudo no CSS.

## box-sizing

Como será calculado o tamanho total da caixa?

- content-box|border-box

```css
div {
    box-sizing: border-box;
}
```

Importante para manter os cálculos dos elementos corretos, pois irá calcular as propriedades em relação a borda e não ao conteúdo