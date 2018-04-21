# Master1 Systèmes Embarqués
Université Nice Sophia-Antipolis

### Professeurs
  - Amar BOUALI
  - Frédéric MALLET

### Projet NuSMV

Sujet [ici](http://miageprojet2.unice.fr/index.php?title=User:FredericMallet/M1_IFI_-_M7_-_Mobile_%26_Embedded_Systems/Traffic_light_with_NuSMV) !
#### Exercice 1

Gestion d'un carrefour entre un feu de voiture et celui des piéton.

Le feu des voitures changent en fonction du temps écoulé :
  - 10 temps en vert
  - 5 temps en rouge
  - 2 temps en jaune

Le feu de piétons se base sur le feu de voitures, en respectant les propriétés définies ci-dessous. Le feu de piéton passe au vert dès que le feux de voiture passe au rouge. Il repassera au rouge lorsque le feu de voiture passe au vert.

#### Exercice 2

Gestion d'un carrefour un peu plus intelligent -> introduction d'un bouton pour piétons

Le feu de voiture reste vert pendant un temps minimum. S'il n'y a pas de piéton (le bouton n'est pas appuyé) il restera vert jusqu'à ce que qu'un piéton appuie sur le bouton. Le piéton peut appuyer à tout moment, mais le feu de voiture restera pendant un temps minimal.

#### Propriétés

Dans ces deux exercices, il faut respecter deux propriétés importantes même dans la vie réelle :
  - Sureté : on doit s'assurer que les deux feux ne deviennent jamais vert en même temps
  - Vivacité : assurer que le carrefour fonctionne correctement, et que les feux alternent pour faire vivre le carrefour

### Projet Android
