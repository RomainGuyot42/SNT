# HTML


Nous allons nous intéresser aux bases du développement web.  
Pour cela nous allons voir 2 languages le HTML et le CSS  
Dans un premier temps nous allons nous intéresser au language HTML.  
  
"Le HyperText Markup Language, généralement abrégé HTML ou dans sa dernière version HTML5, est le langage de balisage conçu pour représenter les pages web. C’est un langage permettant d’écrire de l’hypertexte, d’où son nom" (cf Wikipedia)  
  
Donc le HTML n'est pas un language de programmation comme python c'est un "langage de balisage conçu pour représenter les pages web"

Une balise késako ?
Les balises sont là pour décrire la structure de la page Web. Elles indiquent aux navigateurs comment afficher le document 

La syntaxe des balises
-
Les balises HTML fonctionnent de manière simple  :
- Un chevron ouvrant (<)
- Le nom de la balise
- Des attributs (optionnels). Un espace, suivi du nom de l'attribut, d'un signe égal (=) et d'une valeur entre doubles quotes ("").
- Un chevron fermant (>)  
la plupart des balises fonctionnent par paires. La première balise est ouvrante et la seconde est la balise est fermante.  
Une balise fermante doit avoir le même nom que la balise ouvrante, une balise fermante doit avoir une barre oblique entre le chevron initial et le nom de la balise  

exemple :
  ````html
  <h1></h1> 
  ````
Il est important de savoir qu'une structure du type :
  ````html
<balise1>
<balise2>
</balise1>
</balise2>
  ````
est interdite, la balise2 a été ouverte après la balise1, elle devra donc être refermée avant la balise1.

La structure suivante est correcte :
  ````html
<balise1>
<balise2>
</balise2>
</balise1>
  ````
---
# [Suite](./MINI.md)
