Une loi à densité commune : la loi normale

BTS MC1

# 1 Lien avec la loi binômiale

La loi binômiale est une loi discrète mais en « épaississant » les batons du 
diagramme de sa représentation, on se ramène à un calcul d'aires de 
rectangles.

Si $X \hookrightarrow$$\mathcal{B} (10 ; 0, 6)$ alors :

$$ P (X = k) = \cdots $$

Le sommet des rectangles obtenus appartiennent à une courbe en cloche 
permettant de se ramener à un calcul de probabilités avec une loi à densité. 
Cette loi à densité s'appelle la **loi normale**.

**Exemple** : Représenter la loi $\mathcal{B} (10 ; 0, 6)$

1118.01.0111.07.0



La fonction de densité s'appelle **une gaussienne** (ou « courbe en cloche ») 
et elle intervient dans la modélisation de phénomènes aléatoires possédant de 
nombreuses causes indépendantes, dont les effets s'ajoutent sans que l'un 
d'eux soit dominant : par exemple, dans les mesures physiques avec de 
multiples erreurs indépendantes.



**Remarque:** pourquoi remplacer dans les calculs la loi binômiale par la loi 
normale de même espérance et de même densité ?

<table style="display: inline-table; vertical-align: middle">
  <tbody><tr>
    <td style="text-align: center; background-color: #80808040; border-bottom: 1px solid"><p>
      <strong>Avantages</strong>
    </p></td>
    <td style="text-align: center; background-color: #80808040; border-bottom: 1px solid"><p>
      <strong>Inconv&eacute;nient</strong>s
    </p></td>
  </tr><tr>
    <td style="padding-left: 0.2cm; padding-right: 0.2cm; padding-bottom: 0.2cm; padding-top: 0.2cm; border-top: 1px solid; border-bottom: 1px solid; border-left: 1px solid; border-right: 1px solid"><p>
      Les calculs sont faciles &agrave; r&eacute;aliser par des machines (ce
      sont des calculs d'aires).
    </p><p>
      Alors que pour le calcul de la loi bin&ocirc;miale , les algorithmes
      utilisent des nombres tr&egrave;s grands li&eacute;s aux arbres de
      bernoulli et les machines sont rapidement limit&eacute;s par leurs
      capacit&eacute;s.
    </p></td>
    <td style="padding-left: 0.2cm; padding-right: 0.2cm; padding-bottom: 0.2cm; padding-top: 0.2cm; border-top: 1px solid; border-bottom: 1px solid; border-left: 1px solid; border-right: 1px solid"><p>
      Pour mod&eacute;liser la loi normale &agrave; partir d'une loi
      bin&ocirc;miale, il faut calculer l'esp&eacute;rance et
      l'&eacute;cart-type de cette loi.
    </p><p>
      Les calculs sont moins pr&eacute;cis puisqu'on utilise des
      approximations avec des rectangles.
    </p></td>
  </tr></tbody>
</table>





# 2 Deuxième rencontre avec la loi normale

On suppose que le résultat d'une mesure est un nombre décimal au hasard entre 
0 et 100. Plus précisément, on suppose que la  variable $X$ donnant les 
résultat d'une mesure suivra la loi uniforme $\mathcal{U} [0 ; 100]$.

**Figure.** on répète 100 fois une mesure- répartition des résultats.



Calculons maintenant la moyenne de 10 mesures et répétons cette opération 100 
fois.

Cette moyenne est aussi une variable aléatoire $F\_{10}$ dont l'histogramme 
des fréquences « suggère » qu'elle suit une courbe en cloche de moyenne 50.

**Figure.** on répète 100 fois une moyenne de 10 mesures - répartition des 
résultats



**Remarque:** si on change la loi de $X$ (par exemple, $X \hookrightarrow 
\mathcal{E} (0, 05)$),  on peut faire la même remarque en passant à la 
moyenne.

**C'est un fait général :**

*La variable moyenne des résultats d'une variable aléatoire suivant une loi 
quelconque suit une loi normale.*



<table style="display: inline-table; vertical-align: middle">
  <tbody><tr>
    <td><p>
      <img class="image" src="image-1.png" width="45%"></img>
    </p></td>
    <td><p>
      <img class="image" src="image-2.png" width="45%"></img>
    </p></td>
  </tr></tbody>
</table>

# 3 Moyenne $\mu$ et Écart-type $\sigma$ d'une loi normale $\mathcal{N} (m ; \sigma)$


**Figure.** Quelques exemples de courbes « en cloche » avec des paramètres $m$ 
et $\sigma$





# 4 Comment calculer une probabilité avec une variable suivant une loi normale $\mathcal{N} (m ; \sigma)$

## 4.1 Avec une calculatrice, un tableur

<table style="display: inline-table; vertical-align: middle">
  <tbody><tr>
    <td><p>
      <img class="image" src="image-1.png" width="45%"></img>
    </p></td>
    <td><p>
      <img class="image" src="image-2.png" width="45%"></img>
    </p></td>
  </tr><tr>
    <td><p>
      <img class="image" src="image-3.png" width="45%"></img>
    </p></td>
    <td style="vertical-align: middle"><p>
      <img class="image" src="image-4.png" width="45%"></img>
    </p></td>
  </tr></tbody>
</table>

## 4.2 En utilisant la courbe de Gauss 

Cannot process embedded image

## 4.3 Avec la règle du 1$\sigma$, 2$\sigma$ et 3$\sigma$ 

<table style="display: inline-table; vertical-align: middle">
  <tbody><tr>
    <td><p>
      <img class="image" src="image-1.png" width="65%"></img>
    </p></td>
    <td style="vertical-align: middle"><p>
      <img class="image" src="image-2.png" width="30%"></img>
    </p></td>
  </tr></tbody>
</table>



# 5 Exercices

**Exercice 1:**

*Cannot process embedded image*

**Exercice 2:**

*Cannot process embedded image*

**Exercice 3:**

*Cannot process embedded image*

**Exercice 4:**

*Cannot process embedded image*




