# Ohmyfood

Troisième projet à réaliser dans le cadre du parcours Développeur Web chez Openclassrooms. L'objectif est d'intégrer la maquette de la startup Ohmyfood avec une approche mobile-first. 

![Ohmyfood](https://user.oc-static.com/upload/2020/08/24/15982605908418_Maquettes%20Ohmyfood.jpg)

## Éléments à respecter

## Identité graphique

Polices : 
- Logo et titres : Shrikhand 
- Texte : Roboto 

Couleurs : 
- Primaire : #9356DC 
- Secondaire : #FF79DA 
- Tertiaire : #99E2D0

## Containtes Techniques

- Utilisation d'HTML et de SASS 
- Utilisation de Javascript et des Frameworks non-autorisée 
- Pas de CSS dans via un attribut style dans une balise HTML 
- Le site doit être responsive 
- Les pages doivent passer la validation W3C sans erreur
- Le site doit être compatible avec les dernière versions de Chrome et Firefox 

## Contenu des pages

### Page d'accueil

- Affichage de la localisation des restaurants
- Courte présentation de l'entreprise
- Section avec 4 menus qui redirigent au clic sur la page du menu 

### Page de menu

- 4 pages contenu chacune le menu d'un restaurant

### Header

- Header présent sur toutes les pages 
- Le logo du site sur le header de la page d'accueil
- Pour les pages de menu, il contient un bouton de retour vers la page d'accueil en plus du logo

## Footer

- Il doit être identique sur toutes les pages 
- En cliquant sur "Contact", un renvoi vers une adresse mail est effectué 


## Effets Graphiques

### Boutons 
- L'ombre portée des boutons devra s'intensifier au survol et la couleur de fond devra légèrement s'éclaircir
- Les boutons "j'aime" en forme de coeur sur la maquette devra se remplir progressivement

### Page d'accueil 
- Mise en place d'un loading spinner devant couvrir l'intégralité de la page d'une durée de 1 à 3 secondes en cohérence avec la charte graphique du site 
  
### Pages de menu 
- En arrivant sur la page les plats devront apparaître progressivement avec un léger décalage dans le temps 
- En cliquant sur un plat et au survol pour la version desktop, une petit coche doit apparaître à droite du plat en coulissant de la droite vers la gauche. Le texte devra être rogné avec trois petits points si la coche passe dessus

## SASS 

Pour mettre en place SASS dans ce projet, il faut vous rendre sur le site de [SASS](https://sass-lang.com/install) dans la partie "command line" en suivant les instructions d'installation. Installez-le en version standalone via leur page [Github](https://github.com/sass/dart-sass/releases/tag/1.32.13). Choisissez la version adaptée à votre système et allez dans le fichier zip téléchargé.  
Ensuite, glissez le dossier **dart-sass** dans votre dossier de travail et ouvrez-la dans votre éditeur de code.   Maintenant, toujours dans votre éditeur, **créez un dossier** nommé **sass** dans lequel vous allez ajouter un fichier "style.scss".
  
Rendez vous dans votre terminal et tapez la commande   **./dart-sass/sass --help**  et vous verrez apparaître la documentation SASS. Pour génerer le fichier .scss tapez :   
**./dart-sass/sass sass/style.scss**  

Ensuite, pour générer un fichier css à partir de sass, il suffit de taper la dernière commande suivie de style.css :   
**./dart-sass/sass sass/style.scss style.css**  

Et pour finir, pour que le scss puisse se compiler dans le fichier css, il faut taper la dernière commande suivie de --watch :   
**./dart-sass/sass sass/style.scss style.css --watch**