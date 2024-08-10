# Computation of Basic Degree for group $S_4^p \times S_4 \le O(3)\times S_4$:
This project computes the basic degree of group $S_4^p \times S_4$, where $S_4^p:=S_4\times Z_2$, using GAP with the additional package "EquiDeg".
## Code
The code for this project is contained in the file `S4xZ2xS4.txt`. Readers can enter it into GAP and run the calculations.
## Selection of appropriate $S_4^p\times S_4$ irreducible representation: 
The following tables outline the process for selecting the appropriate $S_4^p \times S_4$ irreducible representation, where the generators of the group are given by $<(1,2,3,4),(1,2),(5,6),(7,8,9,10),(7,8)>$
<br>
<br>
<br>
Irreducible $S_4$ representation $\mathcal{W}_3$ where $S_4$ is generated by <(1,2,3,4),(1,2)> :
| Rep. | Character | (1) | (1,2) | (1,2)(3,4) | (1,2,3) | (1,2,3,4)|
|:------|:-------- |:------|:------|:------|:------|:------|
|$\mathcal{W}_{3}$|$\chi_{3}$|3|-1|-1|0|1|

Irreducible $S_4$ representation $\mathcal{W}_4$ where $S_4$ is generated by <(7,8,9,10),(7,8)> :
| Rep. | Character | (7) | (7,8) | (7,8)(9,10) | (7,8,9) | (7,8,9,10)|
|:------|:-------- |:------|:------|:------|:------|:------|
|$\mathcal{W}_{4}$|$\chi_{4}$|3|1|-1|0|-1|


<br>

Given the conjugacy classes of $S_4^p \times S_4$ in the same order as presented in GAP, the following table presents the irreducible representation $W_3^- \otimes\mathcal{W}_{4}$ of group $S_4^p \times S_4$ which corresponds to  "X.44 of CharacterTable" in GAP:


|()|(1,3)(2,4)| (2,4,3)|(3,4)|(1,3,2,4) |
|:-------------|:-------------|:-------------|:-------------|:-------------|
|9|-3|0|-3|3|

|(5,6)|(1,3)(2,4)(5,6) | (2,4,3)(5,6)| (3,4)(5,6) |(1,3,2,4)(5,6)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|-9 | 3 | 0 | 3 | -3|

|(7,9)(8,10) | (1,3)(2,4)(7,9)(8,10) | (2,4,3)(7,9)(8,10) |(3,4)(7,9)(8,10) | (1,3,2,4)(7,9)(8,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|-3| 1| 0| 1| -1|

|(5,6)(7,9)(8,10) | (1,3)(2,4)(5,6)(7,9)(8,10) | (2,4,3)(5,6)(7,9)(8,10) |(3,4)(5,6)(7,9)(8,10) |(1,3,2,4)(5,6)(7,9)(8,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|3|-1|0|-1|1|

|(8,9,10)| (1,3)(2,4)(8,10,9)| (2,4,3)(8,10,9)|(3,4)(8,10,9)| (1,3,2,4)(8,10,9)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|0 | 0| 0|0|0|

|(5,6)(8,10,9)| (1,3)(2,4)(5,6)(8,10,9)| (2,4,3)(5,6)(8,10,9)| (3,4)(5,6)(8,10,9) | (1,3,2,4)(5,6)(8,10,9)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|0 | 0 | 0 | 0| 0|

|(9,10)| (1,3)(2,4)(9,10)| (2,4,3)(9,10) | (3,4)(9,10) |(1,3,2,4)(9,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|3 | -1 | 0 | -1 | 1|

|(5,6)(9,10) | (1,3)(2,4)(5,6)(9,10) | (2,4,3)(5,6)(9,10)| (3,4)(5,6)(9,10) | (1,3,2,4)(5,6)(9,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|-3| 1 | 0 | 1 | -1|

|(7,9,8,10) | (1,3)(2,4)(7,9,8,10)| (2,4,3)(7,9,8,10) | (3,4)(7,9,8,10) | (1,3,2,4)(7,9,8,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|-3 | 1| 0 | 1 | -1 |

|(5,6)(7,9,8,10) | (1,3)(2,4)(5,6)(7,9,8,10) | (2,4,3)(5,6)(7,9,8,10) | (3,4)(5,6)(7,9,8,10) | (1,3,2,4)(5,6)(7,9,8,10)|
|:-------------|:-------------|:-------------|:-------------|:-------------|
|3 | -1 | 0 | -1 | 1 |

## License and Credits
The "EquiDeg" package by Haoping Wu (https://github.com/psistwu/equideg) is used in this project. Please refer to the package documentation and license for details on usage and distribution.

