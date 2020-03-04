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
Premièrement nous voulons que le fond de cette div soit blanche : pour cela ajouter **background-color** (blanc en anglais : white)  
ensuite nous voulons que le contenu de notre page ne prenne que 80% de la page pour cela ajouter ```` width:80%; ````  
  
actualiser la page,
Le premier problème est que le contenu de la page n'est pas centrer pour cela ajouter : ```` margin:auto; ````

Image
---
Notre image est toujours trop grande, modifier sa taille pour qu'elle fasse 80% de notre div **content**

Bloc couleur
---
Ajoutez une ```` <div> ```` avec pour nom **paragraphe** et changer la couleur de fond de cette ```` <div> ```` pour la mettre en gris (gris en anglais : grey)  

Marge
---
Le texte est trop proche des bords. Affin de l'éloigné nous voullons créer une marge  
Nous voullons l'éloigné de 10% de la surface totale.  
Pour ce faire vous allez ajoutez du code dans la page css  
Voici quelques éléments qui peuvent vous être utiles :
- p
- margin-right
- margin-left
- 10%
