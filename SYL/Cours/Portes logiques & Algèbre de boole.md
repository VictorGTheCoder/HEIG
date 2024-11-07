![[Pasted image 20240927091227.png]]![[Pasted image 20240927091255.png]]![[Pasted image 20240927091307.png]]![[Pasted image 20240927091321.png]]![[Pasted image 20240927091444.png]]Exo

| C   | X   | Y   | S   | Cout |
| --- | --- | --- | --- | ---- |
| 0   | 0   | 0   | 0   | 0    |
| 0   | 0   | 1   | 1   | 0    |
| 0   | 1   | 0   | 1   | 0    |
| 0   | 1   | 1   | 0   | 1    |
| 1   | 0   | 0   | 1   | 0    |
| 1   | 0   | 1   | 0   | 1    |
| 1   | 1   | 0   | 0   | 1    |
| 1   | 1   | 1​  | 1   | 1    |
$$
\begin{align}
Cout(c,x,y) &= \{3,5,6,7\} \\
&= \overline{C}XY + C\overline{X}Y + CX\overline{Y} + CXY \\
&= \overline{C}XY + C\overline{X}Y + CX\overline{Y} + CXY + CXY + CXY \\
&= XY(\overline{C} + C) + CY(\overline{X} + X) + CX(\overline{Y} + Y) \\
&= XY + CY + CX
\end{align}
$$
$$
\begin{align}
S(c,x,y) &= \{1,2,4,7\} \\
&= \overline{CX}Y + \overline{C}X\overline{Y} + C\overline{XY} + CXY \\
&= \overline{C}(\overline{X}Y + X\overline{Y}) +C(\overline{XY} + XY) \\
&= \overline{C}(X \oplus Y) + C(\overline{X\oplus Y})
\end{align}
$$


# Table de Karnaugh

Construit sur $A + \overline{A} =1$
![[Pasted image 20241004093703.png]]
![[Pasted image 20241004093727.png]]
![[Pasted image 20241004093809.png]]