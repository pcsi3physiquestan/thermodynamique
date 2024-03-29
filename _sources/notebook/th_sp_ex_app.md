---
jupytext:
  encoding: '# -*- coding: utf-8 -*-'
  formats: ipynb,md:myst
  split_at_heading: true
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
# Second principe: Exercice d'application

## Identité thermodynamique

````{admonition} Exercice
:class: attention
On définit les grandeurs énergétiques suivantes:
* Enthalpie : H = U + PV
* Energie libre : F = U - TS
* Enthalpie libre : G = F + PV

Exprimer les différentielles de ces trois grandeurs $dH(S,P)$, $dF(T,V)$, $dG(T,P)$ respectivement en fonction des différentielles $(dS, dP)$; $(dT, dV)$; $(dT, dP)$
````
_Point utile pour cet exercice_
* _$\Longrightarrow$ Identité thermodynamique._

## Chauffage d'une masse d'eau

````{admonition} Exercice 
:class: attention

1. Une masse de $1kg$ d'eau à $273\rm{K}$ est mise en contact avec un thermostat à la température de $373\rm{K}$. Quelles sont, lorsque l'eau atteint 373K, les variations d'entropie:
    1. de l'eau
    1. du thermostat (on supposera qu'il n'y a pas de création d'entropie dans le thermostat)
    1. de l'univers (ou entropie créée)
2. Si la masse d'eau est mise en contact d'abord avec un thermostat à $323\rm{K}$ puis avec celui à $373\rm{K}$, quelle est la variation d'entropie de l'Univers?
2. Comment l'eau pourrait-elle être chauffée de $273\rm{K}$ à $373\rm{K}$ en gardant l'entropie de l'Univers à peu près constant.


````
_Point utile pour cet exercice_
* _$\Longrightarrow$ Entropie d'une phase condensée._
* _$\Longrightarrow$ Entropie échangée._
* _$\Longrightarrow$ Second principe._
* _$\Longrightarrow$ Irréversibilité._

## Bilan entropique du chauffage d'un morceau de cuivre

````{admonition} Exercice 
:class: attention

1. On chauffe à l'aide d'un thermostat à la température $T_S = 600 \rm{K}$ une mole de cuivre solide pour faire passer sa température de $293\rm{K}$ à $320\rm{K}$. On néglige la variation du volume et on admet que sa capacité thermique est $3R$. Effectuer un bilan entropique de ce chauffage. Conclure.
1. On fait passer un courant électrique de $5.0\rm{A}$ dans un conducteur ohmique de $44 \rm{\Omega}$ pendant $1h$. La puissance fournie par effet Joule sert maintenir une enceinte à la température de $293\rm{K}$ et fait passer la température de la résistance chauffante de $293\rm{K}$ à $313\rm{K}$. On admet que la capacité thermique de la résistance chauffante est de $C = 5,0 \rm{J.K-1}$. Effectuer le bilan entropique de l'opération. Conclure.

````
_Point utile pour cet exercice_
* _$\Longrightarrow$ Entropie d'une phase condensée._
* _$\Longrightarrow$ Entropie échangée._
* _$\Longrightarrow$ Second principe._
* _$\Longrightarrow$ Irréversibilité._

## Transformations polytropiques d'un GP diatomique

````{admonition} Exercice 
:class: attention

Soit $n$ moles d'un gaz parfait diatomique dont le rapport des capacités calorifiques à pression constante et à volume constants est noté $\gamma$. On suppose qu'il subit des transformations polytropiques, c'est-à-dire que le produit $PV^k$ est constant au cours des transformations ($k \in \mathbb{R}$ et constant).

1. Etablir l'expression différentielle de l'entropie $dS $et la mettre sous la forme $f(\gamma, n, R, k) \frac{dT}{T}$. (On ne supposera pas connu pour cette question l'expression de l'entropie d'un gaz parfait)
1. En déduire la variation d'entropie au cours de la transformation entre deux états A et B.
1. En supposant la transformation quasistatique, calculer le travail $W$ et le transfert thermique $Q$.
1. A quelle situation correspondent les cas:
    * $k=1$?
    * $k=0$?
    * $k$ infini?
    * $k = \gamma$?
````
_Point utile pour cet exercice_
* _$\Longrightarrow$ Entropie d'un gaz parfait._
* _$\Longrightarrow$ Entropie échangée._
* _$\Longrightarrow$ Second principe._
* _$\Longrightarrow$ Irréversibilité._

## Vaporisation réversible ou irréversible

````{admonition} Exercice 
:class: attention

On vaporise une masse de m=1g d'eau liquide des deux manières suivantes:

* la masse m et enfermée à $100 \rm{^{\circ}C}$ sous la pression atmosphérique, dans un cylindre fermé par un piston. Par déplacement lent du piston, on augmente le volume à température constante et on s'arrête dès que toute l'eau est vaporisée. Le volume est alors égal à $V=1,67\rm{L}$.
* on introduit rapidement la masse m d'eau liquide initialement à $100 \rm{^{\circ}C}$ dans un récipient fermé de même température, de volume $1,67\rm{L}$ initialement vide. La température finale est à $100 \rm{^{\circ}C}$.


1. Calculer $Q_{thermostat}$ et les variations d'énergie interne, d'enthalpie et d'entropie de l'eau dans chaque cas.
1. Calculer l'entropie crée lors du processus irréversible.


Données numériques: Enthalpie massique de vaporisation de l'eau est $L_V = 2.25 \times 10^6 \rm{J.kg^{-1}}$.

````
_Point utile pour cet exercice_
* _$\Longrightarrow$ Cor^ps pur diphasé._
* _$\Longrightarrow$ Entropie de changement d'état._
* _$\Longrightarrow$ Enthalpie de changement d'état._
* _$\Longrightarrow$ Volume massique d'une phase condensée et d'un gaz._
