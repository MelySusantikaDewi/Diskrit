---
title: UAS

---

#### UAS

#### 1

| No | P | Q |R |S |
| -- | --|-- |--|--|
| 1.| T  | T | T|  |
| 2.| T  | T | F|  |
| 3.| T  | F | T|  |
| 4.| T  | F | F|  |
| 5.| F  | F | T|  |
| 6.| F  | F | F|  |
| 7.| T  | F | T|  |
| 8.| F  | T | T|  |

##### Soal Pertama
$(P\implies Q)$ $\implies$ $(R\implies S)$
##### Jawaban

| No | P | Q |R |S |$(P\implies Q)$|$(R\implies S)$|$(P\implies Q)$ $\implies$ $(R\implies S)$|
| -- | --|-- |--|--|--|--|--|
| 1.| T  | T | T| T |T|T|T|
| 2.| T  | T | F| F |T|T|T|
| 3.| T  | F | T| T |F|T|T|
| 4.| T  | F | F| F |F|T|T|
| 5.| F  | F | T| T |T|T|T|
| 6.| F  | F | F| F |T|T|T|
| 7.| T  | F | T| T |T|T|T|
| 8.| F  | T | T| F |T|T|T|

##### Soal Kedua
![Screenshot 2024-12-09 143415](https://hackmd.io/_uploads/BJVGAM4Ekx.png)


1.Hitunglah Closeness Centrality =F
2.Hitunglah Bettweennes Centrality =G

##### Jawaban

1.Hitunglah Closeness Centrality

| Node | A | B | C | D | E | F |
|  --- |-- | --|-- |-- |-- |-- |
| A |  - |  1|   2|   1|  3 |   2|
| B |  1 |  - |   2|   1|   2|  1 |
| C | 2  | 2  |  - |  1 |  2 | 1  |
| D |  1 |  1 | 1  | -  | 2  |  1 |
| E |  3 |  2 |   1|   2|   -|   1|
| F |   2|   1|   1|   1|   1|   -|

$C_C(v) = \frac{n-1}{\sum_{u \in V} d(v, u)}$

##### Node A
$C_C(V) = \frac{6-1}{9}= \frac{5}{9}=0,55555555556$

##### Node B
$C_C(V) = \frac{6-1}{7}= \frac{5}{7}=0,7142857143$

##### Node C
$C_C(V) = \frac{6-1}{8}= \frac{5}{8}=0,625$

##### Node D
$C_C(V) = \frac{6-1}{6}= \frac{5}{6}=0,83$

##### Node E
$C_C(V) = \frac{6-1}{9}= \frac{5}{9}=0,55555555556$

##### Node F
$C_C(V) = \frac{6-1}{6}= \frac{5}{6}=0,0,83$

