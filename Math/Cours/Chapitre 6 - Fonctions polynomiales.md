#### 6.1 Polynômes
Polynome d'une variables:
$p(x) = a_n\cdot x^n + a_{n-1}\cdot x^{n-1} +... + a_1\cdot x + a_0$

**Ex:**
(i) 
$$
\begin{align}
&\text{(i) Degrée 3 : } &p(x) &= 3x^3-x^2 + 4x + 7 \\
&\text{(ii) Degée 4: } &p(t) &= 1 + t^2 + t^4
\end{align}
$$

#### 6.2 Opération sur les polynômes

Somme: $p(x) + q(x)$
Différence: $p(x) - q(x)$
Produit: $p(x) \cdot q(x)$
Quotient:
Division polynomiale (de p(x) par d(x))
$p(x) = q(x) \cdot d(x) + r(x)$

Si degré $p(x) < d(x) \Rightarrow q(x) = 0, r(x) = p(x)$
Si degré$p(x) \geq d(x)$ Alors $degré(q(x)) = degré(p(x))$
![[Pasted image 20240930110144.png]]
$$
\begin{gather}
p(x) = 4x^4 + 8x^3 +9x^2 +20x + 1  \quad q(x) = x^2 + 2 \\ \\
\frac{(4x^4 + 8x^3 + 9x^2 + 20x + 1)}{x^2 + 2} =  (x^2 + 2) \cdot (4x^2 + 8x + 1) + (4x - 1)\\

\end{gather}
$$

#### 6.3 Racines d'un polynôme

$x_0\mid p(x_0)= 0$
$x_0 \text{ est une racine de }p(x)$
$\Leftrightarrow p(x) \text{ est divisible par } (x-x_0)$

Multplicité d'une racine. Le plus grand entier $k$ tel que $p(x) \text{ est divisible par} (x-x_0)^k$
**Ex:**
$$
\begin{align}
p(x) &= x^3 + 6x^2 + 9x \\
&=x (x^2 + 6x + 9) \\
&=x(x + 3)^2
\end{align}
$$
$0$ est une racine *simple* (Multiplicité 1) de $p(x)$
$-3$ est une racine *double* (Multiplicité 2) de $p(x)$

#### 6.4 Factorisation d'un polynôme

Exprimer $p(x)$ sous forme d'un produit, d'une constante avec des facteurs irréductibles de degrées 1 ou 2.
Degrée 1 :  $x -x_0$, Degrée 2 :  $x^2 + bx + x$
$$
\begin{align*}
\text{(i)} \quad p(x) &= x^4 - 16 \\
&= (x^2 - 4)(x^2 + 4) \quad  \\
&= (x - 2)(x + 2)(x^2 + 4) \quad \\[10pt]
\text{(ii)} \quad q(x) &= 2x^2 - 3x - 2 \\
&= 2\left( x^2 -\frac{3}{2x} - 1 \right) \\
&=2(x-2)\left( x + \frac{1}{2} \right)
\end{align*}

$$

Discriminant: $\Delta = b^2 -4ac$ pour $p(x) = ax^2 + bx + c$
**Prop** $p(x) = ax^2 + bx + c$

$(i)\quad \Delta > 0: p(x)$ a deux racines réelles
$$
x_{1,2} = -\frac{b\pm\sqrt\Delta}{2a}
$$
et $p(x) = (x-x_1)(x-x_2)$

$(ii) \quad\Delta = 0: p(x)$ a une solution réelle
$$
x_0 = -\frac{b}{2a}
$$
Et $p(x) = a (x-x_0)^2$

$(iii) \quad \Delta<0:p(x)$ n'a pas de racines réelle et n'a pas de factorisation dans $\mathbb{R}$

