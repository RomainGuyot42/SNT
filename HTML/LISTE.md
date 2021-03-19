# Les listes

L'objectif des liste est d'ordonner du contenu dans nos page HTML, Ce contenu peut être hiérarchisé ou non.

Il existe deux types de listes en HTML : les listes ordonnées et les listes non-ordonnées.

## Les listes non ordonnées

Par exemple, pour lister les mots « avion », « vélo » et « voiture », sans plus de contexte, j’utiliserai une liste non-ordonnée.
En effet il n'y a pas de hiérarchie entre ses 3 mots.

Pour créer une liste non-ordonnée, nous allons avoir besoin d’un élément ````ul```` (pour « unordered list », ou « liste non-ordonnée » en français) qui va représenter la liste en soi ainsi que d’un élément ````li```` (« list item » ou « élément de liste ») pour chaque nouvel élément de liste.

Dans le cas que nous avons cité précédemment cela donnerait :
````html
<ul>
    <li>Avion</li>
    <li>Vélo</li>
    <li>Voiture</li>
</ul>
````

Comme vous pouvez le remarquer, on va placer les éléments ````li```` à l’intérieur de l’élément de liste ````ul````. C’est tout à fait logique puisque les éléments de liste « appartiennent » à la liste.

Visuellement, des puces (les points noirs) apparaissent automatiquement devant chaque élément d’une liste non-ordonnée par défaut. Nous allons pouvoir changer ce comportement et personnaliser l’apparence de nos listes en CSS grâce notamment à la propriété ````list-style-type```` que nous pouvons modifer dans la page css.

## Les listes ordonnées

Au contraire des listes non-ordonnées, nous allons utiliser les listes ordonnées lorsqu’il y aura une notion d’ordre ou de progression logique ou encore de hiérarchie entre les éléments de notre liste.

Pour créer une liste ordonnée, nous allons cette fois-ci utiliser l’élément ````ol```` (pour « ordered list » ou « liste ordonnée ») pour définir la liste en soi et à nouveau des éléments ````li```` pour chaque élément de la liste.

````html
<ol>
  <li>INtroduction</li>
  <li>Partie 1</li>
  <li>Partie 2</li>
  <li>Conclusion</li>
</ol>
````

Cette fois ce sont cette fois-ci des numéros qui sont affichés devant chaque élément de la liste par défaut.

Encore une fois, nous allons pouvoir changer ce comportement et afficher différents styles de puces avec la propriété CSS ````list-style-type````
