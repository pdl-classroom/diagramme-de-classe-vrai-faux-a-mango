# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ? 
- Etudiant est une classe d’association - **Faux**
- Un étudiant peut participer à autant de cours qu’il veut - **Vrai**
- Plusieurs professeurs peuvent enseigner la même discipline - **Faux**
- Un professeur peut enseigner plusieurs disciplines - **Vrai**
- Un cours peut être enseigner à 2 étudiants - **Faux**
- Un cours peut être enseigner à 20 étudiants - **Vrai**

## Question ouverte w

Représentez la même association avec la notation UML « petit losange »

> ![Classes](uml/classes-n-ary.png)

- Quelles informations perd-on par rapport au diagramme ci-dessus ? 

On perd l'information qu'un professeur peut avoir plusieurs disciplines et par 
conséquent plusieurs cours.

Dans la version n-aire, si la cardinalité d'un cours était "*", cela
indiquerai qu'un professeur peut enseigner plusieurs cours pour la même
discipline, ce que le diagramme original ne représente pas. Il en va de
même pour la discipline.
