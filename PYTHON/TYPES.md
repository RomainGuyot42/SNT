# Les Types 

En programmation, les données qu’on va pouvoir manipuler avec un langage sont généralement classées par “type”.
Un “type” de données est défini par les manipulations qu’on va pouvoir faire sur ces données.

Prenons un nombre par exemple. Il semble tout à fait logique de pouvoir effectuer des opérations mathématiques de base avec ce nombre : addition, soustraction, multiplication, etc. En revanche, on ne va pas pouvoir effectuer les mêmes opérations / manipulations sur un texte, puisque multiplier un texte par quelque chose par exemple n’a aucun sens.

Dans l'exemple précédent :

````python
a = 7
````

la valeur de a : 7 est une nombre ceci est le type de la variable.

Deux variable qui n'ont pas le même type ne peuvent pas avoir d'opération ensembe.

### exemple 

````python
a = 7
b = 'bonjour'
c = a + b
````

le programme va nous donner une erreur car on ne peut pas ajouter du texte (le type de la variable b) et un nombre (le type de la variable a)

Voici un tableau avec tous les types que vous pouvez croiser au cours de l'année 

| Nom du type (anglais) | Nom du type (français) | Code du type (python) | Description | exemple |
| -- | -- | -- | -- | -- |
| Integer |  	Entier | int | Entier compris entre -2 147 483 648 et 2 147 483 647 | a = 7 |
| Long integer | Entier long | long | Entier compris entre + l'infini et - l'infini | b = 10 000 000 000 |
| Floating point number | Nombre à virgule flottante | float | Nombre réel (Nombre à virgule) | c = 3.7  |
| Character string | Chaîne de caractères | str | Chaîne de caractères (texte) | d = 'bonjour' |
| Boolean| Valeur booléenne | bool | 2 valeur possible True ou False (vrai ou faux) | e = true |

Les langages de programmation sont toujours en anglais à partir de maintenant nous utiliserons exclusivement les termes anglais
C'est pourquoi pour un float on utilise un point et pas une virgule 

## Attention 
Pour définir une Character string il faut mettre le texte entre Guillemet siple ou double 
exemple : 
````python
a = 'bonjour'
````





