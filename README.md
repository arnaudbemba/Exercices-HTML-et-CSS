# Exercices HTML et CSS

Ceci est une notice de programmation pour l'explication, la documentation, la formation et l'apprentissage du code.

href="mailto:NOMDUMAIL@MAIL.COM" crée un lien hypertexte qui ouvre la boîte mail avec un nouveau message vide.

href="NOMDEFICHIER.EXTENSION" crée un lien hypertexte qui permet de télécharger un fichier que vous avez placé au préalable dans le même dossier que votre page web.

les termes montagne_mini.jpg et montagne.jpg permet de céer une miniature cliquable

 <!--les balises li, ul, ol sert à baliser et insérer des éléments dans une liste -->

Cette ligne à rajouter dans le fichier .html s'ouvre avec la balise orpheline <link> et on la place à l'intérieur de la balise <head> </head> :

<head>
    <meta charset="utf-8">
    <title>Ma page</title>
    <link href="style.css" rel="stylesheet">
</head>

/_le css applique une propriété à plusieurs balises_/
Ce code CSS signifie que nos titres de niveau 1 et nos paragraphes doivent s'afficher en bleu :

h1 {
color: blue;
}

p {
color: blue;
}

Exemple de cumule des classes dans une même balise :

<body>
    <h1>Titre principal</h1>
    <p>Ceci est le contenu de mon premier paragraphe</p>
    <p class="ma-classe grand-texte">Ceci est le contenu de mon deuxième paragraphe</p>
    <h2 class="grand-texte">Voilà mon sous-titre h2</h2>
</body>

les tailles en em html

<p class="elem1">Élément 1 : 1em</p>
<p class="elem2">Élément 2 : 1.3em</p>
<p class="elem3">Élément 3 : 2em</p>

Pour utiliser la police de Google Fonts sélectionner une police, puis :

Copiez les balises <link> dans le <head> </head> du fichier HTML.

Utilisez la propriété font-family dans le fichier CSS pour déclarer que vous voulez utiliser cette police. Par exemple, pour la police Roboto, on vient coller dans le HTML :

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
Et on l'utilise dans le CSS en déclarant dans notre sélecteur :

font-family: 'Roboto', sans-serif;

En CSS, on donne une valeur à font-style pour dire si on veut que du texte soit en italique ou non :

italic : le texte sera mis en italique ;

normal : le texte sera normal (par défaut). Cela vous permet d'annuler une mise en italique. Par exemple, si vous voulez que les textes entre <em> ne soient plus en italique, vous devrez écrire :

em
{
font-style: normal;
}

En CSS, on donne une valeur à font-style pour dire si on veut que du texte soit en italique ou non :

italic : le texte sera mis en italique ;

normal : le texte sera normal (par défaut). Cela vous permet d'annuler une mise en italique. Par exemple, si vous voulez que les textes entre <em> ne soient plus en italique, vous devrez écrire :

em
{
font-style: normal;
}

La propriété CSS text-decoration permet, entre autres, de souligner le texte, mais pas seulement. Voici quelques-unes des différentes valeurs qu'elle peut prendre :

underline: souligné ;

line-through: barré ;

none: normal (par défaut, sauf dans le cas des liens).

Le propriété CSS text-align permet d'aligner du texte selon la valeur qu'on lui donne :

left : le texte sera aligné à gauche (c'est le réglage par défaut) ;

center : le texte sera centré ;

right : le texte sera aligné à droite ;

la propriété color permet de modifié la couleur du texte
Sous forme hexadécimale (6 chiffres précédés d'un #). Exemple : color: #FFC8D3;

En notation RGB (pour Red Green Blue en anglais). Exemple : color: rgb(250,25,118);. Notez qu'on peut ajouter la notion d'opacité (ou de transparence) avec la notation RGBA, où la dernière valeur correspond à l'opacité : color: rgba(250,25,118, 0.5);

La propriété CSS background-attachment associée à la valeur fixed permet de rendre l'image de fond fixe lorsqu'on déroule la page web : background-attachment: fixed;

La propriété CSS background-size associée à la valeur cover permet de redimensionner l'image afin qu'elle s'adapte à la taille de l'élément qui la contient (elle garde ses proportions, en rognant la largeur ou la hauteur en fonction de la taille de l'élément qui la contient) : background-size: cover;

La propriété CSS background-position associée aux valeurs top , bottom , left , center ou right permet d'indiquer où doit se trouver l'image de fond, par exemple : background-position: top right;

Chacune de ces 3 propriétés possède plusieurs valeurs possibles qu'on peut leur associer. Je vous invite à aller tester en direct sur le site de Mozilla Developer les différents effets possibles des propriétés :

background-attachment ;

background-size ;

background-position.

De nombreux paramètrages existent en ce qui concerne les images de fond. Si vous voulez en savoir plus, vous pouvez vous référer à la documentation de la propriété CSS background.
