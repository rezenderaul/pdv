# GRID Alinhamento
___

Existem 6 tipos de alinhamentos:
1. `justify-contents`
2. `align-contents`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separar em 2 grupos:
1. `justify` e `align`
2. `content`, `items` e `self`

---

## Justify e Align
Sabendo que o grid é bidirecional, nós temos o eixo x e y.

O **eixo x** é posicionamento horizontal, da esquerda para a direita.

O **eixo y** é posicionamento vertical, de cima para baixo.

---

## Content, Items e Self
Juntando o `justify` ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedade

---

### Content
`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que área definida, (por exemplo: quando usamos px no tamanho da grid, poderemos terminar com um grid pequeno, para o tamanho da areá do grid).

Podemos utilizar **7 valores** utilizados dentro do container
1. start
2. end
3. center
4. stretch
5. space-between // Espaço igual entre
6. space-around // Espaço igual ao redor, colocando um espaço inicial e final diferente
7. space-evenly  // Espaço contínuo

---

### Items
`justify-items` e `align-items` vão permitir alinharmos itens da grid, em qualquer espaço disponível, na célula que ele habitar.

Podemos utilizar **4 valores**
1. start
2. end
3. center
4. stretch

---

### Self
`justify-self` e `align-self` vão nos permitir alinhar o item em si.

Faz o mesmo que o `justify-items` e `align-items`, porém aplicado diretamente no item do grid.