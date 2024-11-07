
![[Pasted image 20241004110603.png]]
$$
\begin{array}{|c|c|c|c|c|c|c|c|c|}
\hline
\textbf{4 pattes} & \textbf{Ecailles} & \textbf{Ovipare} & \textbf{ovovivipare} & \textbf{Ours} & \textbf{Oiseau} & \textbf{Ornithorynque} & \textbf{Lézard} & \textbf{Serpent} & \textbf{Indéfini} \\
\hline
0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 \\
0 & 0 & 0 & 1 & 0 & 0 & 0 & 0 & 0 & 1 \\
0 & 0 & 1 & 0 & 0 & 1 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 0 & 0 & 0 & 0 & 0 & 1 \\
0 & 1 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 \\
0 & 1 & 0 & 1 & 0 & 0 & 0 & 0 & 1 & 0 \\
0 & 1 & 1 & 0 & 0 & 0 & 0 & 0 & 1 & 0 \\
0 & 1 & 1 & 1 & 0 & 0 & 0 & 0 & 0 & 1 \\
1 & 0 & 0 & 0 & 1 & 0 & 0 & 0 & 0 & 0 \\
1 & 0 & 0 & 1 & 0 & 0 & 1 & 0 & 0 & 0 \\
1 & 0 & 1 & 0 & 0 & 0 & 0 & 0 & 0 & 1 \\
1 & 0 & 1 & 1 & 0 & 0 & 0 & 0 & 0 & 1 \\
1 & 1 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 \\
1 & 1 & 0 & 1 & 0 & 0 & 0 & 1 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & 0 & 0 & 1 & 0 & 1 \\
1 & 1 & 1 & 1 & 0 & 0 & 0 & 0 & 0 & 1 \\
\hline
\end{array}
$$


**Question 2**
Ours: $A\overline{BCD}$
Oiseaux: $\overline{AB}C\overline{D}$
Ornythtorincs: $A\overline{BC}D$
Lezard: $AB\overline{C}D$ + $ABC\overline{D}$
Sepent: $\overline{A}B\overline{C}D$ + $\overline{A}BC\overline{D}$

**Factorisation Lezard et Serpent**
$AB\overline{C}D+ABC\overline{D}=AB(D\overline{C}+\overline{D}C)$
$\overline{A}B\overline{C}D+ \overline{A}BC\overline{D}=\overline{A}B(D\overline{C}+\overline{D}C)$


**Indéfinis :**
$\overline{ABCD} + \overline{ABC}D+ \overline{AB}CD + \overline{A}B\overline{CD} + \overline{A}BCD + A\overline{B}C\overline{D} + A\overline{B}CD + AB\overline{CD} + ABC\overline{D} + ABCD$

**Question 3**
Pour indéfinis
Min terme f(a,b,c,d) = 0,1,3,4,7,10,11,12,14,15
$$
\begin{array}{|c|c|c|c|}
\hline
AB\backslash CD & 00 & 01 & 11 & 10 \\
\hline
00 & 1 & 1 & 1 & 0 \\
\hline
01 & 0 & 0 & 1 & 0 \\
\hline
11 & 1 & 1 & 1 & 1 \\
\hline
10 & 0 & 0 & 1 & 1 \\
\hline
\end{array}
$$


$=\overline{BD} + BD$


