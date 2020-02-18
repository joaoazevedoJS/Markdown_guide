# Listas não ordenada e Listas ordenadas

## Listas não ordenada

**Exemplo 1**:

`* Exemplo`

* Item 01
* Item 02
* Item 03

**Exemplo 2**:

`- Exemplo`

- Item 01
- Item 02
- Item 03

**Exemplo 3**:

`+ Exemplo`

+ Item 01
+ Item 02
+ Item 03

### Listas não ordenada com Subitem

    - ou * ou +
   
    - Item 01
      - Subitem
    - Item 02
      - Subitem 01
      - Subitem 02

* Item 01
  * Subitem
* Item 02
  * Subitem 01
    * . . .
  * sub Item 02

## Lista Ordenada

**Exemplo 1**:

    1. Item 01
    2. Item 02
    3. Item 03

1. Item 01
2. Item 02
3. Item 03

**Exemplo 2**:

    Não importa se você colocar o mesmo numero:

    1. Item 01
    1. Item 02
    1. Item 03

1. Item 01
1. Item 02
1. Item 03

**Exemplo 3**:

    Mas se você começar por um certo numero ele vai continuar seguindo a sequência correta:

    8. Item 08
    5. Item 05
    20. Item 20

8. Item 08
5. Item 05
20. Item 20

**Exemplo 4**:

    Caso queira fazer uma "Lista Ordenada" sem que ele siga a sequência:

    1994\. Brasil // space space
    1998\. França // space space
    2002\. Brasil // space space

1994\. Brasil  
1998\. França  
2002\. Brasil

### Listas ordenada com Subitem

    1. Item 01
       1. Subitem
    2. Item 02
       1. Subitem 01 
       2. Subitem 02

1. Item 01
    1. Subitem
2. Item 02
    1. Subitem 01
    2. Subitem 02

## Dando Espaçamento

### Espaçamento em Lista não ordenada

    '*', '-' ou '+'

    *. Item 01
       *. Subitem // Enter 2x
  
    * Item 02
      * Subitem 01
        * . . .
      * Subitem 02

* Item 01
  * Subitem

* Item 02
  - Subitem 01
    + . . .
  * Subitem 02

### Espaçamento em Lista Ordenada

    1. Item 01
       1. Subitem // Enter 2x

    2. Item 02
        1. Subitem 01
          1.  . . .
        2. Subitem 02

1. Item 01
   1. Subitem

2. Item 02
   1. Subitem 01
      1. . . .
   2. Subitem 02

## Lista de Tarefa

```
  - [ ] Item 01
  - [X] Item 02
```

- [ ] Item 01
- [X] Item 02
  