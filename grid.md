# GRID

* colunas e linhas

## Propriedades Fundamentais

* todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

```html
<div id="app">
  <div>1</div>
  <span>2</span>
  <span>3</span>
</div>
```

* div = display block  (a linha toda)
* span = display inline (somente a largura do conteúdo)
* inline puro não aceita o margin-top
* o pai recebe o comportamento grid e isso muda o comportamento dos filhos

### CONTAINER (pai)

- display: grid
- grid-template:

#### grid-template-colummns

* colunas
* fr = fração
* repeat(3, 1fr)

#### grid-template-rows
* linhas

### ITENS (filhos)

* coluna virtual
* linha virtual

#### grid-column

* grid-column-start 
* grid-column-end 

#### grid-row

* grid-column-start 
* grid-column-end 

#### grid-template-areas

* grid-area

#### gap

### PROPRIEDADES DE ALINHAMENTO

- existem 9 propriedades fundamentais

**6 aplicadas em container (pai)**
`align-content`
`justify-content`
`place-contet`

`align-items`
`justify-items`
`place-items`

**3 aplicadas em items**
`align-self`
`justify-self`
`place-self`

- então podemos separar em 3 grupos:
`align`, `justify` e `place`

- e cada um irá observar ou o:
  * conteúdo do elemento `content`
  * itens do elemento `items`
  * o próprio elemento `self`

- align trabalha no eixo y (vertical)
- justify trabalha no eixo x (horizontal)
- place trabalha com ambos (eixo y e eixo x)

### PROPRIEDADES AUTO

- grid-auto-flow (por padrão é row)
- grid-auto-rows (linhas)
- grid-auto-columns (colunas)



