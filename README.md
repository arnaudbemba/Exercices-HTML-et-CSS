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
