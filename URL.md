
# URL

Dans la barre d'adresse de votre navigateur web vous trouvez :  
"https://romainguyot42.github.io/SNTWeb/URL.html"  
C'est l'URL du site que vous êtes en train de visiter.  
Nous aurons l'occasion de reparler du "http" plus tard dans ce chapitre.   
"romainguyot42.github.io" est le nom de domaine, nous l'avons vu pendant le chapitre sur Internet.   
La partie "/disciplines/informatiquelycee/index.html" est la partie qui nous intéresse.   
C'est le chemin vers la ressource de la page qui nous intéresse   


Une URL (Uniform Resource Locator) permet d'identifier une ressource (par exemple un fichier) sur un réseau.

L'URL indique « l'endroit » où se trouve une ressource sur un ordinateur. Un fichier peut se trouver dans un dossier qui peut lui-même se trouver dans un autre dossier... On parle d'une structure en arborescence, car elle ressemble à un arbre à l'envers :

![URL photo](./url.png)  
structure en arborescence
  
Comme vous pouvez le constater, la base de l'arbre s'appelle la racine de l'arborescence et se représente par un /
  
# Chemin absolu ou chemin relatif ?
  
Pour indiquer la position d'un fichier (ou d'un dossier) dans l'arborescence, il existe 2 méthodes : indiquer un chemin absolu ou indiquer un chemin relatif. Le chemin absolu doit indiquer « le chemin » depuis la racine. Par exemple l'URL du fichier fichier3.jpg sera : /dossier2/dossier3/fichier3.jpg  
  
Remarquez que nous démarrons bien de la racine /
  
Imaginons maintenant que le fichier fichier1.css fasse appel au fichier fichier3.jpg (comme un fichier HTML peut faire appel à un fichier CSS). Il est possible d'indiquer le chemin non pas depuis la racine, mais depuis le dossier (dossier2) qui accueille le fichier1.css, nous parlerons alors de chemin relatif :  
  
dossier3/fichier3.jpg
  
Remarquez l’absence du / au début du chemin (c'est cela qui nous permettra de distinguer un chemin relatif et un chemin absolu).  
