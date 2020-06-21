# CSS GRID

## GRID
- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX
- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna, ou linha)
- Um complementa o trabalho do outro (no gride fica os limites do layout)
- Verificar quais navegadores ainda não aceitão o Grid

---

## PROPRIEDADES

São separados em 2 grupos:
`container`e `item(s)`

---

### CONTAINER
- display: grid; // Inicia o container informando que é um grid
- grid-template-columns; // Fatia em colunas
    xfr
- grid-template-rows; // Fatia em linhas
    xvh
- grid-gap //shortcut, aplica em ambos
    - grid-row-gap // Espaçamentos em linha 
    - grid-column-gap // Espaçamentos em coluna
- grid-template-areas; // Delimita areas
... e mais 4 propriedades de **alinhamento**

---

### ITEM(s)
- grid-column // Local o onde item está localizado na coluna
shortcut x/x (inicia/finaliza)
    - grid-column-start //x
    - grid-column-end //x
- grid-row // Local onde o item está localizado na linha
    - grid-row-start //x
    - grid-row-end //x
- grid-area // Local onde o item está localizado na area
... e mais 2 propriedades de **alinhamento**