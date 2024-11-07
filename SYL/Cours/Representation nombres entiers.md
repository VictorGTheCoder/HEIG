![[Pasted image 20241011084829.png]]
Pour trouver la version négative d'un nombre on prend sont complement et ajoute 1
Example
7 = 0111
-7 = 1000 + 0001 = 1001

$\underline{\text{Overflow}}$
![[Pasted image 20241011090407.png]]

On a un overflow seulement lorsque les deux signes sont les mêmes. Si le bit de signe est inversé (par rapport au 2 addition ou peut import), alors on a overflow.

#### Etendre un nombre
![[Pasted image 20241011091031.png]]
![[Pasted image 20241011091043.png]]

#### Multiplication par puissance de 2
![[Pasted image 20241011093012.png]]
Pour non signé on décale tout a gauche et le LSB devient $0$

Pour signé on n'a pas le droit de remplacer le bit de signe. Alors si  il y a un $1$ avant alors il s' "évapore". On a donc une erreur dans le calcule.
#### Division par puissance de 2
![[Pasted image 20241011093538.png]]

Ex1:
$\underline{\text{Non signé}}$
128 non signé. 10000000

$\underline{\text{Complément à deux}}$
-128 complement à deux : $10000000$
128 Pas possible overflow

$\underline{\text{Signe magnitude}}$
-127: 11111111
128: Pas possible overflow.
