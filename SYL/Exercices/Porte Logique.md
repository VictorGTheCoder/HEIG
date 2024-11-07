Ex1
a) 
$$
\overline{\overline{A} + \overline{B}} = S
$$
b)
$$
\begin{array}{|c|c|c|}
\hline
A & B & S \\
\hline
0 & 0 &0 \\
\hline
0 & 1 & 0\\
\hline
1 & 0 & 0\\
\hline
1 & 1 & 1\\
\hline
\end{array}
$$
c)
C'est un "ET"

Ex5
a) 
$AB + \overline{AB}$

$$
\begin{array}{|c|c|c|}
\hline
A & B & S\\
\hline
0 & 0 & 1\\
\hline
0 & 1 & 0\\
\hline
1 & 0 & 0\\
\hline
1 & 1 & 1\\
\hline
\end{array}
$$

Ex6
$\overline{AB} + A\overline{B} + \overline{A}B$
$$
\begin{array}{|c|c|c|}
\hline
A & B & S\\
\hline
0 & 0 & 0\\
\hline
0 & 1 & 1\\
\hline
1 & 0 & 1\\
\hline
1 & 1 & 0\\
\hline
\end{array}
$$
C'est un ou exclusif XOR

Ex7


$$
\begin{array}{|c|c|c|c|c|}
\hline
A & B & C &D &S\\
\hline
0 & 0 & 0 & 0 & 1\\
\hline
0 & 0 & 0 & 1 & 1\\
\hline
0 & 0 & 1 & 0 & 1\\
\hline
0 & 0 & 1 & 1 & 1\\
\hline
0 & 1 & 0 & 0 & 1\\
\hline
0 & 1 & 0 & 1 & 1\\
\hline
0 & 1 & 1 & 0 & 1\\
\hline
0 & 1 & 1 & 1 & 0\\
\hline
1 & 0 & 0 & 0 & 1\\
\hline
1 & 0 & 0 & 1 & 1\\
\hline
1 & 0 & 1 & 0 & 1\\
\hline
1 & 0 & 1 & 1 & 1\\
\hline
1 & 1 & 0 & 0 & 1\\
\hline 
1 & 1 & 0 & 1 & 1\\
\hline
1 & 1 & 1 & 0 & 0\\
\hline
1 & 1 & 1 & 1 & 0\\
\hline\end{array}
$$

Si A & B & C or A & B & C & D or B & C & D alors false


Ex8
![[Pasted image 20241004084808.png]]

$$
\begin{align}
S_1(a,b,c) &= \sum (2,5,7) \\
&= \overline{a}b\overline{c} + a\overline{b}c + abc \\
&=ac(\overline{b} + b) + \overline{a}b\overline{c} \\
&=ac + \overline{a}b\overline{c} \\
\end{align}
$$

$$
\begin{align}
S_2(a,b,c) &= \sum (0,1,3,4,6) \\
&= \overline{abc} + \overline{ab}c + \overline{a}bc + a\overline{bc} + ab\overline{c} \\
&= \overline{abc} + \overline{ab}c + \overline{a}bc + a\overline{bc} + ab\overline{c} + \overline{abc} \\
&= 5\overline{c}(a + \overline{a}) + \overline{ab}(c + \overline{c}) + a\overline{c} + a\overline{c}(b + \overline{b}) \\
&=5\overline{c} + \overline{ab} + a\overline{c} \\
\end{align}
$$
![[Pasted image 20241004084824.png]]
$$
\begin{align}
S_3(a,b,c,d) &= \sum (0,2,3,6,7,11,15) \\
&= \overline{abcd} + \overline{ab}c\overline{d} + \overline{ab}cd + \overline{a}bc\overline{d} + \overline{a}bcd + a\overline{b}cd + abcd \\
&= \overline{abd}(c + \overline{c}) + \overline{a}cd(b + \overline{b}) + acd(\overline{b} + b) + ... \\
&= \overline{abd} + \overline{a}cd + acd \\
&= cd(\overline{a} + a) = cd
\end{align}
$$

On remarque que peut importe si $a = 0$ out $a = 1$ donc on peut sortir $a$

$$
\begin{align}
S_4(a,b,c) &= \sum (0,2,3,4,5,7,8,10,11,12,13,15) \\
&= \overline{bcd} + \overline{b}c\overline{d} + \overline{b}cd + \overline{bc} + b\overline{cd} + b\overline{c}d + bcd \\
&= \overline{bd} + \overline{b}c + b\overline{c} + bd \\
\end{align}
$$
**Ex 10**
Démontrer $A + AB = A$

$A(1 + B) = A$
$A (1) = A$
$A = A$

b)
Démontrer $A + \overline{A}B = A + B$
$A(1) + A\overline{B}$
$A(B + \overline{B}) + \overline{A}B$
$AB + A\overline{B} + \overline{A}B$
$A(B + \overline{B}) + B(\overline{A} + A)$
$A + B$

c)
$$
\begin{align} \\
&=(A + B)(A+C) = A + BC \\
&=A + AC + BA + BC \\
&=A + A + BC \\
&= A + BC
\end{align}
$$

