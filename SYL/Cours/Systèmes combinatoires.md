# Les 4 Composants Clés

- **Comparateur**
- **Décodeur**
- **Multiplexeur**
- **Encodeur**

---

## Comparateur

**Objectif :** Déterminer si deux nombres sont égaux.
![[Pasted image 20241101084017.png]]

![[Pasted image 20241101084017.png]]

### Fonctionnement

#### Exemple avec un Comparateur 1 Bit

Un comparateur 1 bit est essentiellement un **XOR** inversé.

![[Pasted image 20241101084115.png]]

#### Comparateur à n Bits

![[Pasted image 20241101084633.png]]

##### Cascade

**Note :** Le résultat de chaque comparateur est utilisé comme **Enable** pour le comparateur suivant. Ainsi, si une comparaison donne 0, le comparateur suivant n'est pas activé.

![[Pasted image 20241101084654.png]]

##### Parallèle

**Note :** Cette configuration est plus rapide car tous les comparateurs sont exécutés simultanément. La comparaison finale avec un **ET** se fait en deux étapes.

![[Pasted image 20241101084911.png]]

### Table de Vérité (Comparateur 2 Bits)

| A | B | A XOR B | Égalité |
|---|---|---------|---------|
| 0 | 0 |    0    |    1    |
| 0 | 1 |    1    |    0    |
| 1 | 0 |    1    |    0    |
| 1 | 1 |    0    |    1    |

---

## Décodeur

![[Pasted image 20241101085602.png]]
Par exemple, si **Sel₀ = 0** et **Sel₁ = 0**, la sortie active sera **Y₀**. Pour **Sel₀ = 1** et **Sel₁ = 1**, ce sera **Y₃**.

![[Pasted image 20241101085932.png]]

Dans un décodeur, une seule sortie est activée à la fois.

![[Pasted image 20241101085954.png]]

### Décodeur sans ENABLE

![[Pasted image 20241101090111.png]]

**Formules des sorties :**
- $Y_0 = \overline{\text{Sel}_1} \cdot \overline{\text{Sel}_0}$
- $Y_1 = \overline{\text{Sel}_1} \cdot \text{Sel}_0$
- $Y_2 = \text{Sel}_1 \cdot \overline{\text{Sel}_0}$
- $Y_3 = \text{Sel}_1 \cdot \text{Sel}_0$

### Décodeur avec ENABLE

![Décodeur avec ENABLE](Pasted_image_20241101090221.png)

**Formules des sorties avec ENABLE (\( \text{En} \)) :**
- $Y_0 = \text{En} \cdot (\overline{\text{Sel}_1} \cdot \overline{\text{Sel}_0})$
- $Y_1 = \text{En} \cdot (\overline{\text{Sel}_1} \cdot \text{Sel}_0)$
- $Y_2 = \text{En} \cdot (\text{Sel}_1 \cdot \overline{\text{Sel}_0})$
- $Y_3 = \text{En} \cdot (\text{Sel}_1 \cdot \text{Sel}_0)$

### Décodeur 3 à 8

![Décodeur 3 à 8](Pasted_image_20241101090805.png)

### Table de Vérité

| EN | Sel(2) | Sel(1) | Sel(0) | Y(7) | Y(6) | Y(5) | Y(4) | Y(3) | Y(2) | Y(1) | Y(0) |
|----|--------|--------|--------|------|------|------|------|------|------|------|------|
| 0  | x      | x      | x      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    |
| 1  | 0      | 0      | 0      | 0    | 0    | 0    | 0    | 0    | 0    | 0    | <span style="color:red">1</span> |
| 1  | 0      | 0      | 1      | 0    | 0    | 0    | 0    | 0    | 0    | <span style="color:red">1</span> | 0    |
| 1  | 0      | 1      | 0      | 0    | 0    | 0    | 0    | 0    | <span style="color:red">1</span> | 0    | 0    |
| 1  | 0      | 1      | 1      | 0    | 0    | 0    | 0    | <span style="color:red">1</span> | 0    | 0    | 0    |
| 1  | 1      | 0      | 0      | 0    | 0    | 0    | <span style="color:red">1</span> | 0    | 0    | 0    | 0    |
| 1  | 1      | 0      | 1      | 0    | 0    | <span style="color:red">1</span> | 0    | 0    | 0    | 0    | 0    |
| 1  | 1      | 1      | 0      | 0    | <span style="color:red">1</span> | 0    | 0    | 0    | 0    | 0    | 0    |
| 1  | 1      | 1      | 1      | <span style="color:red">1</span> | 0    | 0    | 0    | 0    | 0    | 0    | 0    |

---

## Multiplexeur

**Objectif :** Sélectionner et transmettre une des entrées vers la sortie en fonction des lignes de sélection.

## Symbole
![[Pasted image 20241101095418.png]]
### Composants

- \( 2^n \) entrées
- \( n \) lignes de sélection
- Une sortie
- Une entrée supplémentaire **Enable** (souvent présente pour faciliter l’extension)

![[Pasted image 20241101093924.png]]

### Multiplexeur 4 à 1

#### Table de Vérité

| EN  | Sel(1) | Sel(0) | Y     |
| --- | ------ | ------ | ----- |
| 0   | x      | x      | 0     |
| 1   | 0      | 0      | $D_0$ |
| 1   | 0      | 1      | $D_1$ |
| 1   | 1      | 0      | $D_2$ |
| 1   | 1      | 1      | $D_3$ |

![[Pasted image 20241101095133.png]]

### Multiplexeur m à 1
![[Pasted image 20241101095500.png]]

![[Pasted image 20241101100052.png]]

---

## Encodeur

**Objectif :** Convertir une seule entrée active parmi plusieurs en un code binaire correspondant.

![[Pasted image 20241101100027.png]]
### Fonctionnement

Un encodeur prend  $2^n$ entrées et les encode en $n$ bits de sortie.

**Detect** Nous informe si **Enable** est actif

### Table de Vérité (Encodeur 4 à 2)

| Entrée | Sortie(1) | Sortie(0) |
| ------ | --------- | --------- |
| Y₀     | 0         | 0         |
| Y₁     | 0         | 1         |
| Y₂     | 1         | 0         |
| Y₃     | 1         | 1         |


## Unité Arithmétique et Logique (ALU)

L'ALU est l'organe de l'ordianteur pour les calculs![[Pasted image 20241101102938.png]]

Ce sont des **1-bit** ALU

![[Pasted image 20241101103029.png]]

Pour donner les instruction à l'ALU quel opération il doit faire on utilise l'**OPCODE**

![[Pasted image 20241101103331.png]]

![[Pasted image 20241101103633.png]]

