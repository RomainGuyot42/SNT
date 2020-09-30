# Les Conditions 

Le programme est amené à faire des choix pour cela il faut utiliser un instruction qui dépend de certaines conditions : 
  L'instruction `if`
  
Prenon un exemple 
````
Si je suis en retard 
  Alors je vais à la vie scolaire
Sinon 
  je vais en classe
````

Cette notion en fait intervenir une autre :
La notion de Bloc

### Les Bloc d'instructions
  un bloc d'instructions est crée par une instruction (if, while et for, ...)
  
> Sous Python, toutes les instructions composées ont toujours la même structure : une ligne d'en-tête terminée par un double point
> Suivie d'une ou de plusieurs instructions indentées sous cette ligne d'en-tête
>Il y a deux solutions pour indenter : utiliser quatre espaces ou un seul caractère tabulation, mais jamais un mélange des deux sous peine d'erreurs IndentationError: unindent does not match any outer indentation level

### L''instruction `if`

exemple 1
````
a = 11
if a > 10 :
    print("a est plus grand que dix")
````

l'instruction teste si a est supérieur à 10. 
La partie alors est matérialiser par l'indentation. Si il y a plus d'une ligne de code il faut maintenir l'indentation. 

````
if a > 10 :
    print("a est plus grand que dix")
else:
    print("a n'est pas plus grand que dix")
````
La partie est matérialiser par le else, les instructions corespondantes aux else sont a la suite avec une indentation 


## Instructions imbriquées

Il est parfaitement possible d'imbriquer les unes dans les autres plusieurs instructions composées, de manière à réaliser des structures de décision complexes.
Pour chaque instruction imbriquer il faut rajouter une tabulation.

````
if embranchement == "vertébrés":
    if classe == "mammifères":
        if ordre == "carnivores":
            if famille == "félins":
                print ("c'est peut-être un chat")
````
