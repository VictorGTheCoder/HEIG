---
title: Relation Inverse
tags:
  - relation
  - mathématiques
  - discrètes
  - propriété
---

## Définition

Si $R$ est une [relation](Relations) de $A$ vers $B$, la **relation inverse** de $R$, notée $R^{-1}$, est la relation de $B$ vers $A$ formée de tous les couples $(b, a) \in B \times A$ tels que $a$ est en relation avec $b$ par $R$ :

$$
R^{-1} = \{\, (b, a) \in B \times A \mid (a, b) \in R \,\}
$$

## Exemple

### Exemple 1

**Ensemble de départ :**

- $A = \{1, 2\}$
- $B = \{x, y\}$

**Relation $R$ :**

$$
R = \{\, (1, x), (2, y) \,\}
$$

**Relation inverse $R^{-1}$ :**

$$
R^{-1} = \{\, (x, 1), (y, 2) \,\}
$$

### Exemple 2

**Ensemble de départ :**

- $A = \{a, b, c\}$
- $B = \{1, 2\}$

**Relation $R$ :**

$$
R = \{\, (a, 1), (b, 2), (c, 1) \,\}
$$

**Relation inverse $R^{-1}$ :**

$$
R^{-1} = \{\, (1, a), (2, b), (1, c) \,\}
$$

## Propriétés

- $(R^{-1})^{-1} = R$
- Si $R$ est injective, alors $R^{-1}$ est fonctionnelle.
- Si $R$ est une bijection, alors $R^{-1}$ est également une bijection.
