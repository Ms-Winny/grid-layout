# GRID - LAYOUT

## GRID

 - Bidimensional
 - Divisão de toda a página em linhas e colunas
 - Colocar elementos aonde quiser nessa divisão

---

## GRID ou Flexbox

 - Grid: Duas dimensões (colunas e linhas)
 - Flexbox: Uma dimensão (ou coluna ou linha)
 - Um complementa o trabalho do outro
 - Verificar quais navegadores ainda não são compatíveis

 ---

 ## PROPRIEDADES 

 Vamos separar em 2 grupos:
 `container` e `item(s)`

 ---
 ### Container

 - display: grid;
 - grid-template-columns;
 - grid-template-rows;
 - grid-gap;
   - grid-row-gap
   - grid-column-gap
 - grid-template-areas;

  ... e mais 4 propriedades de **alinhamentos**

 ---
 ### Item(s)

 - grid-column;
   - grid-column-start
   - grid-column-end
 - grid-row;
   - grid-row-start
   - grid-row-end
 - grid-area;

  ... e mais 2 propriedades de **alinhamentos**


 ---
 # ALINHAMENTO

 Existem 6 propriedades para alinhamento:
 1. `justify-content`
 2. `align-content`
 3. `justify-items`
 4. `align-items`
 5. `justify-self`
 6. `align-self`

 Vamos separá-los em 2 grupos
 1. `justify` e `align`
 2. `content`, `items` e `self`

 ---
## Justify e Align 

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita. 

O **eixo y** é o posicionamento vertical, de cima para baixo.

---
## Content, Items e Self

Essas três propriedades definem o que vamos posicionar:

`Content` é relativo ao **espaço fora do grid**

`Items` é relativo ao **espaço dentro da célula**

`Self` é semelhante ao items, porém aplicado **diretamente em um item**

--- 
## JUNÇÃO DESSAS PROPRIEDADES


