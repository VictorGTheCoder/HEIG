#### 9.1 Exemple introductif

Soit la fonction $f : \mathbb{R^*} \mapsto \mathbb{R_+^*}$ avec
$$
f(x) =  \frac{\sqrt{x^2 + 1} -1}{x^2}
$$
![[Pasted image 20241007104817.png]]
 On dira par la suite que la limite de $f$ lorsque $x$ tend vers $0$ existe et est égale à 0.5. On écrira alors
$$
\lim\limits_{x \to 0} f(x) = \frac{1}{2}
$$
La limite n'est pas forcement une valeur prise par la fonctions (même si elle peut). Mais une valeurs vers laquelle elle tend.


#### 9.2 Limites finies en un point réel

Déf: Soit $x_0 \in \mathbb{R}, f : E\mapsto F$ définie au voisinage de $x_0$
On écrit $\lim\limits_{x\rightarrow x_0} f(x) = L$ si la valeur de $f(x)$ devient arbitrairement proche de L quand x devient arbitrairement proche de $x_0$.
Ou
$\forall \epsilon > 0, \exists \delta > 0$ tel que $[x \in E, |x - x_0| < \delta]\Rightarrow [|f(x) - L| < \epsilon]$

**Limites unilatérales :**
. Limites à gauche $\lim\limits_{x\rightarrow x_0^-} f(x)$
. Limites à droite $\lim\limits_{x\rightarrow x_0^+} f(x)$

Utile pour vérifier qu'une limite existe. On regarde que la limite à droite et à gauche existe et qu'elles tendent vers le même résultat.

**Exemple de fonctions sans limite**
![[d8abc486-4d44-45a1-8602-031f7adf5ec4.png]]

$\underline{Prop :}$
$\lim\limits_{x\rightarrow x_0} f(x) = L \Leftrightarrow [\lim\limits_{x\rightarrow x_0^-} f(x) = L \text{ et } \lim \limits_{x\rightarrow x_0^+} f(x) = L]$

#### 9.3 Continuité

$\underline{\text{Trois cas de figure}}$
1. La limite n'existe pas
2. La limite existe  mais ne vaut pas $f(x_0)$
3. La limite existe et est égale à $f(x_0)$  $\Rightarrow f(x)$ est continue en $x_0$

$\underline{Ex..}$
$(i) \quad f(x) = \frac{|x|}{x}$ et $x_0 = 0$ 
$\lim\limits_{x\rightarrow0^+} = \lim\limits_{x\rightarrow0^+} \frac{|x|}{x} = \lim\limits_{x \rightarrow 0^+} \frac{x}{x} = 1$
$\lim\limits_{x\rightarrow0^-} = \lim\limits_{x\rightarrow0^-} \frac{|x|}{x} = \lim\limits_{x \rightarrow 0^-} \frac{-x}{x} = -1$

Donc la limite n'existe pas
![[38845abe-6103-4278-a94d-a343fb45f84e.png]]

$(ii) \quad g(x) = \frac{x-1}{\sqrt{x} - 1}$ et $x_0 = 1$
$\lim\limits_{x\rightarrow 1} g(x) = \lim\limits_{x\rightarrow 1} \frac{x-1}{\sqrt{x} -1} = \lim\limits_{x\rightarrow 1} \frac{(\sqrt{x} - 1)(\sqrt{x} +1)}{\sqrt{x} - 1} = \lim\limits_{x\rightarrow 1 }\sqrt{x} + 1 = 2$

La limite existe, alors que $f$ n'est pas définie en $x_0 = 1$
![[9076014b-8b06-4dac-9548-5619f8a1d74a.png]]

$(iii)\quad h(x)= \frac{\sqrt{6-x}}{1 + ln(x-1)}$ et $x_0 = 2$
$\lim\limits_{x \rightarrow 2} h(x) = \lim\limits_{x \rightarrow 2} \frac{\sqrt{6-2}}{1 + ln(2-1)} = \frac{2}{1} = 2$

La limite existe et est égale à $h(2)$ 

