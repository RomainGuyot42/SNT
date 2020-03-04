# Exercices 2

Premièrement nous allons centrer notre texte :  
dans la page css ajouter :  
````css
body{

}
````
cela signifie que nous allons modifier tout ce qui se trouve dans la partie body de notre code css.
A l'intérieur des ```` {} ```` ajoutez ```` text-align:center; ````  
  
Nous voulons également aligner tout les autres éléménts au centre (ex: image) pour cela il nous faut utiliser **align-content**  
Maintenant nous allons ajouter un fond vert pour cela utiliser **background** (vert se dit green en anglais)  
  
Actualisez la page pour visualiser le résultat.  

Ce vert n'est pas très lisible, pour rendre notre page plus lisible nous allons ajouter une div qui condiendra l'ensemble de notre page   

Le nom de cette balise sera **contenu** cela ajouter la balise ouvrante ```` <div id="contenu"> ```` juste après la balise ```` <body> ```` et la balise fermante ```` </div > ```` juste avant la balise ```` </body> ```` 

Pour appeler note balise **contenu** dans notre code css il faut ajouter le code suivant :  
````css
#contenu{
  
}
````
