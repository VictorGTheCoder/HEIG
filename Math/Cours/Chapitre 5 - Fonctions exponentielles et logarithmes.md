	#### 5.1 Fonctions exponenetielles
Soit $A \in \mathbb{R*+}$
On définit  $exp\small{a} : \mathbb{R}\rightarrow \mathbb{R{*+}}$
$x \mapsto exp_a(x) = a^x$
comme l'unique fonction continue telle que:
- $exp_a(1) = a$
- $exp_a(x+y) = exp_a(x) * exp_a(y)$

On a $Im(exp_a) = \mathbb{R*+}$
pour $a \in \mathbb{R}*+ \setminus \{1\}$

**Prop:**
i) $exp_a(0) = (a^0) = 1$
ii) $exp_a(1) = (a^1) = 1$
iii) $exp_a(-1) = a^-1 = 1/a$

Pour $a > 1$, expa est strictement croissant sur $\mathbb{R}$
Pour $0 < a < 1$, ""                               décroissant sur $\mathbb{R}$

Pour $a = e$, on a expe = exp

#### 5.2 Fonctions logarithmes
Soit $a \in \mathbb{R}*+ \setminus \{1\}$
 $log_a:\mathbb{R}+* \rightarrow \mathbb{R}$
$y = \log_a(x) \Leftrightarrow \exp_a(y) = x$

**Prop :**
(1) $\log_a(1) = 0$
(2) $\log_a(a) = 1$
(3) $\log_a\left( \frac{1}{a}\right) = -1$

(4)
Pour $a > 1$, $log_a$ est strictement croissant sur $\mathbb{R}*+$
Pour $0 < a < 1$, $log_a$ est strictement décroissant sur $\mathbb{R}*+$

(5) $log_a(x*y) = log_a(x) + log_a(y)$
(6) $log_a\left( \frac{x}{y} \right) = log_a(x) - log_a(y)$
(7) $\log_{\frac{1}{a}}(x) = -log_a(x)$
(8) $log_a(x^z) = z * log_a(x)$
(9) $log_a(x) = \frac{log_b(x)}{log_b(a)}$

**Exemples**
(i) $log_{10}(1000) = log_{10}(10^3) = 3$
(ii) $log_{1000}(10) = log_{1000}((1000)^{\frac{1}{3}} = \frac{1}{3}$
(iii) $log_{\frac{1}{3}}(81) = log_{\frac{1}{3}}(3^4) = -log_3(3^4) = -4$
(iiii) 
$$
\begin{align}
log_a(x^2) + 3log_a\left( \frac{1}{x^{\frac{1}{3}}} \right) &= 2log_a(x)  + 3\left( -\frac{1}{3}*log_a(x) \right) \\
&= log_a(x)
\end{align}
$$


**Ex**
$x\in \mathbb{R}*+$
Représentation en virgule flottante binaire
$$
2^p \cdot m \text{ avec m est la mantisse}
$$
$log_2(2^p\cdot m) = log_2(2^p) + log_2(m)$
$= p + log_2(m)$
