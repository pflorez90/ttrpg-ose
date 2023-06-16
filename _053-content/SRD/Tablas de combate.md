---
srd: true
tag: srd
alias: 
---
# Tablas de combate

Estas tablas enumeran las probabilidades de ataque de todos los monstruos y personajes, así como los valores de tiradas de salvación de monstruos y humanos comunes.

---
## Humano común

Cualquier humano que no pertenezca a una clase aventurera. Se les trata como si tuvieran menos de 1 Dado de Golpe y tienen sus propias tiradas de salvación y ataque.

---
## Tiradas de ataque usando GAC0 (regla opcional)

En lugar de consultar la matriz de ataque, los ataques pueden resolverse usando directamente GAC0. Un valor de GAC0 indica la tirada de ataque necesaria para golpear CA 0. La tirada de ataque necesaria para golpear a oponentes con un valor de CA diferente se puede calcular restando la CA del objetivo del GAC0. Por ejemplo, un personaje con GAC0 19 podría golpear a un oponente con CA 5 con una tirada de 14 o más (19 - 5 = 14).

**Nota:** El uso de GAC0 para resolver las tiradas de ataque da como resultado probabilidades de ataque ligeramente diferentes a cuando se usa la matriz de ataque.

---
# Matriz de ataque por GAC0

-tx-
| | Tirada de ataque para golpear CA|||||||||||||
|   GAC0  | -3 | -2 | -1 |  **_0_** |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |
|:-------:|:--:|:--:|:--:|:--------:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 20 [-1] | 20 | 20 | 20 | **_20_** | 19 | 18 | 17 | 16 | 15 | 14 | 13 | 12 | 11 |
|  19 [0] | 20 | 20 | 20 | **_19_** | 18 | 17 | 16 | 15 | 14 | 13 | 12 | 11 | 10 |
| 18 [+1] | 20 | 20 | 19 | **_18_** | 17 | 16 | 15 | 14 | 13 | 12 | 11 | 10 |  9 |
| 17 [+2] | 20 | 19 | 18 | **_17_** | 16 | 15 | 14 | 13 | 12 | 11 | 10 |  9 |  8 |
| 16 [+3] | 19 | 18 | 17 | **_16_** | 15 | 14 | 13 | 12 | 11 | 10 |  9 |  8 |  7 |
| 15 [+4] | 18 | 17 | 16 | **_15_** | 14 | 13 | 12 | 11 | 10 |  9 |  8 |  7 |  6 |
| 14 [+5] | 17 | 16 | 15 | **_14_** | 13 | 12 | 11 | 10 |  9 |  8 |  7 |  6 |  5 |
| 13 [+6] | 16 | 15 | 14 | **_13_** | 12 | 11 | 10 |  9 |  8 |  7 |  6 |  5 |  4 |
| 12 [+7] | 15 | 14 | 13 | **_12_** | 11 | 10 |  9 |  8 |  7 |  6 |  5 |  4 |  3 |
| 11 [+8] | 14 | 13 | 12 | **_11_** | 10 |  9 |  8 |  7 |  6 |  5 |  4 |  3 |  2 |
| 10 [+9] | 13 | 12 | 11 | **_10_** |  9 |  8 |  7 |  6 |  5 |  4 |  3 |  2 |  2 |
| 9 [+10] | 12 | 11 | 10 |  **_9_** |  8 |  7 |  6 |  5 |  4 |  3 |  2 |  2 |  2 |
| 8 [+11] | 11 | 10 |  9 |  **_8_** |  7 |  6 |  5 |  4 |  3 |  2 |  2 |  2 |  2 |
| 7 [+12] | 10 |  9 |  8 |  **_7_** |  6 |  5 |  4 |  3 |  2 |  2 |  2 |  2 |  2 |
| 6 [+13] |  9 |  8 |  7 |  **_6_** |  5 |  4 |  3 |  2 |  2 |  2 |  2 |  2 |  2 |
| 5 [+14] |  8 |  7 |  6 |  **_5_** |  4 |  3 |  2 |  2 |  2 |  2 |  2 |  2 |  2 |

---
## Tiradas de salvación de PNJ

Los PJ y los PNJ con clase usan los valores de tiradas de salvación de su [[Clases|clase]], listadas en su libro de reglas de género.

-tx-
|Tirada de salvación de monstruo||||||
| Dado de   Golpe | **M**uerte | **V**aritas | **P**arálisis | **A**liento | **H**echizos |
|:---------------:|:----------:|:-----------:|:-------------:|:-----------:|:------------:|
|  Humano común   |     14     |     15      |      16       |     17      |      18      |
|       1-3       |     12     |     13      |      14       |     15      |      16      |
|       4-6       |     10     |     11      |      12       |     13      |      14      | 
|       7-9       |     8      |      9      |      10       |     10      |      12      |
|      10-12      |     6      |      7      |       8       |      8      |      10      |
|      13-15      |     4      |      5      |       6       |      5      |      8       |
|      16-18      |     2      |      3      |       4       |      3      |      6       |
|      19-21      |     2      |      2      |       2       |      2      |      4       |
|    22 o más     |     2      |      2      |       2       |      2      |      2       |

-tx-
|GAC0 de monstruo por Dado de Golpe||
| Dado de   Golpe |   GAC0  |
|:---------------:|:-------:|
|   Humano común  | 20 [-1] |
|     Hasta 1     |  19 [0] |
|      1+ a 2     | 18 [+1] |
|      2+ a 3     | 17 [+2] |
|      3+ o 4     | 16 [+3] |
|      4+ a 5     | 15 [+4] |
|      5+ a 6     | 14 [+5] |
|      6+ a 7     | 13 [+6] |
|      7+ a 9     | 12 [+7] |




