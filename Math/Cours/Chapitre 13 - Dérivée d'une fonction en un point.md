## 13.1 Intuition : Taux d'accroissement

### Définition du taux d'accroissement

Soit $x_0 \in \mathbb{R}$ et $f$ une fonction définie au voisinage de $x_0$. Pour un accroissement $\Delta x$ de $x$, le **taux d'accroissement** de $f$ entre $x_0$ et $x_0 + \Delta x$ est donné par :

$$
\frac{\Delta f}{\Delta x}\bigg|_{x_0} = \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}.
$$

#### Remarque 13.1

Le taux d'accroissement représente le rapport entre la variation de$f$ et celle de$x$ sur l'intervalle $[x_0, x_0 + \Delta x]$. Graphiquement, il correspond à la pente de la **droite sécante** passant par les points$(x_0, f(x_0))$ et $(x_0 + \Delta x, f(x_0 + \Delta x))$.

### Exemple 13.1

Prenons $f : \mathbb{R} \rightarrow \mathbb{R}$ définie par $f(x) = \sin(x) + 0.3x$, avec $x_0 = 0.5$. Calculons le taux d'accroissement pour $\Delta x = 0.5$ :

$$
\frac{\Delta f}{\Delta x}\bigg|_{x_0=0.5} = \frac{f(0.5 + 0.5) - f(0.5)}{0.5} = \frac{1.141 - 0.629}{0.5} = 1.024.
$$

*Remarque :* La valeur de $f(0.5)$ est approximativement $0.629$, et celle de $f(1.0)$ est environ $1.141$.

## 13.2 Définition et illustrations

### Définition de la dérivée en un point

La **dérivée** de $f$ en $x_0$, si elle existe, est définie par la limite du taux d'accroissement lorsque \$Delta x$ tend vers 0 :

$$
f'(x_0) = \lim_{\Delta x \to 0} \frac{\Delta f}{\Delta x}\bigg|_{x_0} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}.
$$

On dit alors que $f$ est **dérivable** (ou différentiable) en $x_0$.

#### Remarque 13.2

Cette définition signifie que la dérivée en $x_0$ est la pente de la **droite tangente** à la courbe de $f$ en ce point.

### Exemple 13.2

Reprenons la fonction $f(x) = \sin(x) + 0.3x$ avec $x_0 = 0.5$. En laissant $\Delta x$ tendre vers 0, le taux d'accroissement approche la valeur de la dérivée en $x_0$. On obtient :

$$
f'(0.5) \approx 1.178.
$$

*Ceci correspond à la pente de la tangente à la courbe en $x_0 = 0.5$.*

### Droites tangente et normale

#### Définition 13.3

Si $f$ est dérivable en $x_0$, alors :

1. **La droite tangente** à la courbe en $(x_0, f(x_0))$ a pour équation :

   $$
   y = t(x) = f(x_0) + f'(x_0)(x - x_0).
   $$

2. **La droite normale** à la courbe en $(x_0, f(x_0))$, si $f'(x_0) \neq 0$, est donnée par :

   $$
   y = n(x) = f(x_0) - \frac{1}{f'(x_0)}(x - x_0).
   $$

### Exemple 13.3

Soit $f(x) = x^2$ et $x_0 = 1$.

- **Calcul de la dérivée en $x_0$** :

  $$
  f'(1) = \lim_{h \to 0} \frac{(1 + h)^2 - 1^2}{h} = \lim_{h \to 0} \frac{2h + h^2}{h} = \lim_{h \to 0} (2 + h) = 2.
  $$

- **Équation de la tangente** :

  $$
  y = f(1) + f'(1)(x - 1) = 1 + 2(x - 1) = 2x - 1.
  $$

- **Équation de la normale** :

  $$
  y = f(1) - \frac{1}{f'(1)}(x - 1) = 1 - \frac{1}{2}(x - 1) = \frac{3}{2} - \frac{1}{2}x.
  $$

### Remarque 13.4

- **Continuité et dérivabilité** : Si $f$ est dérivable en $x_0$, alors elle est continue en $x_0$. L'inverse n'est pas toujours vrai ; une fonction peut être continue en un point sans y être dérivable.
  
- **Existence de la dérivée** : La dérivée en $x_0$ existe si les limites du taux d'accroissement à gauche et à droite existent et sont égales :

  $$
  f'(x_0) = \lim_{h \to 0^-} \frac{f(x_0 + h) - f(x_0)}{h} = \lim_{h \to 0^+} \frac{f(x_0 + h) - f(x_0)}{h}.
  $$

Pour vérifier qu'une dérivée en un point existe, on peut vérifier l’existence et l’égalité des dérivées à gauche et à droite, définies de manière évidente.

### Exemple 13.4: Fonction non dérivable en un point

Considérons $f(x) = |x|$.

- **Continuité** : $f$ est continue en $x_0 = 0$.

- **Dérivabilité** :

  - Limite à gauche :

    $$
    \lim_{x \to 0^-} \frac{|x| - |0|}{x} = \lim_{x \to 0^-} \frac{-x}{x} = -1.
    $$

  - Limite à droite :

    $$
    \lim_{x \to 0^+} \frac{|x| - |0|}{x} = \lim_{x \to 0^+} \frac{x}{x} = 1.
    $$

  *Conclusion* : Les limites à gauche et à droite ne sont pas égales, donc $f$ n'est pas dérivable en $x_0 = 0$.

---
