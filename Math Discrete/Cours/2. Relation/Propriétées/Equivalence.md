---
title: Relation d’Équivalence
tags:
  - équivalence
  - mathématiques
  - discrètes
  - relation
  - propriété
---
## Définition

Une [relation](Relations) $R$ sur un ensemble $A$ est dite une **relation d’équivalence** si et seulement si elle satisfait simultanément les trois propriétés suivantes :

1. **[[Réflexivité]]**: Pour tout $a \in A$, $a R a$
2. **[[Symétrie]]** : Si $a R b$, alors $b R a$
3. **[[Transitivité]]** : Si $a R b$ et $b R c$, alors $a R c$

Deux éléments $a, b \in A$ liés par une telle relation sont dits **équivalents**, notés $a \equiv b$
## Exemples

1. **Exemple 1 : Département des Étudiants**
   - **Ensemble** : $A$ est l’ensemble des étudiants et étudiantes de l’école.
   - **Relation** : Deux personnes sont en relation si elles appartiennent au même département.
   - **Vérification des Propriétés** :
     - **Réflexivité** : Chaque étudiant appartient à son propre département.
     - **Symétrie** : Si l'étudiant $a$ est dans le même département que $b$, alors $b$ est dans le même département que $a$.
     - **Transitivité** : Si $a$ est dans le même département que $b$, et $b$ dans le même département que $c$, alors $a$ est dans le même département que $c$.

2. **Exemple 2 : Longueur des Mots**
   - **Ensemble** : $A$ est l’ensemble des mots de la langue française.
   - **Relation** : Deux mots sont en relation si et seulement s'ils ont le même nombre de lettres.
   - **Vérification des Propriétés** :
     - **Réflexivité** : Tout mot a le même nombre de lettres que lui-même.
     - **Symétrie** : Si un mot $a$ a le même nombre de lettres que $b$, alors $b$ a le même nombre de lettres que $a$.
     - **Transitivité** : Si $a$ a le même nombre de lettres que $b$, et $b$ que $c$, alors $a$ a le même nombre de lettres que $c$.

3. **Exemple 3 : Entiers et Valeurs Absolues**
   - **Ensemble** : $A = \mathbb{Z}$ (ensemble des entiers).
   - **Relation** : $R = \{(x, y) \in \mathbb{Z}^2 \mid |x| = |y|\}$.
   - **Vérification des Propriétés** :
     - **Réflexivité** : $|x| = |x|$ pour tout $x \in \mathbb{Z}$.
     - **Symétrie** : Si $|x| = |y|$, alors $|y| = |x|$.
     - **Transitivité** : Si $|x| = |y|$ et $|y| = |z|$, alors $|x| = |z|$.

4. **Exemple 4 : Plan Euclidien $\mathbb{R}^2$**
   - **Ensemble** : $A = \mathbb{R}^2$ (ensemble des points du plan).
   - **Relation** : Deux points $P(x_1, y_1)$ et $Q(x_2, y_2)$ sont en relation si $\max(x_1, y_1) = \max(x_2, y_2)$.
   - **Vérification des Propriétés** :
     - **Réflexivité** : $\max(x_1, y_1) = \max(x_1, y_1)$.
     - **Symétrie** : Si $\max(x_1, y_1) = \max(x_2, y_2)$, alors $\max(x_2, y_2) = \max(x_1, y_1)$.
     - **Transitivité** : Si $\max(x_1, y_1) = \max(x_2, y_2)$ et $\max(x_2, y_2) = \max(x_3, y_3)$, alors $\max(x_1, y_1) = \max(x_3, y_3)$.

**Remarques :**
- Une **relation d’ordre** est une relation réflexive, antisymétrique et transitive. Contrairement aux relations d’équivalence, elle impose une directionnalité.
- Les **diagrammes de Hasse** sont utilisés pour représenter visuellement les relations d’ordre.
- Les **classes d’équivalence** sont les ensembles d’éléments équivalents entre eux sous une relation d’équivalence donnée.

**Symbolisme :**
Le symbole usuel pour noter l’équivalence de deux éléments $a$ et $b$ est le « triple égal » : $a \equiv b$.

**Applications :**
Les relations d’équivalence sont fondamentales en mathématiques, notamment dans la classification des objets en classes équivalentes, la définition des quotients d’ensembles, et dans de nombreuses structures algébriques telles que les groupes, les anneaux et les espaces vectoriels.
