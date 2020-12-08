# HTML CSS

# HTML
## Decouvrez le fonctionnement des sites web

* Le Web a ete invente par Tim Berners-Lee au debut des annees 1990.
* Pour creer des sites web, on utilise deux langages informatiques :
	* HTML : permet d'ecrire et organiser le contenu de la page (paragraphes, titres…)
	* CSS : permet de mettre en forme la page (couleur, taille…).

* Il y a eu plusieurs versions des langages HTML et CSS. Les dernieres versions sont HTML5 et CSS3.
* Le navigateur web est un programme qui permet d'afficher des sites web. Il lit les langages HTML et CSS pour savoir ce qu'il doit afficher.
* Il existe de nombreux navigateurs web differents : Google Chrome, Mozilla Firefox, Internet Explorer, Safari, Opera… Chacun affiche un site web de maniere legerement differente des autres navigateurs.
* Nous allons apprendre a utiliser les langages HTML et CSS. Nous travaillerons dans un programme appele « editeur de texte » (Sublime Text, Notepad++, jEdit, vim…).

## Creez votre premiere page web en HTML

* On utilise l'editeur de texte (Sublime Text, Notepad++, jEdit, vim…) pour creer un fichier ayant l'extension .html  (par exemple : test.html  ). Ce sera notre page web.
* Ce fichier peut etre ouvert dans le navigateur web simplement en faisant un double-clic dessus.
* A l'interieur du fichier, nous ecrirons le contenu de notre page, accompagne de balises HTML.
* Les balises peuvent avoir plusieurs formes :
	* `<balise> </balise>`  : elles s'ouvrent et se ferment pour delimiter le contenu (debut et fin d'un titre, par exemple) ;
	* `<balise />`  : balises orphelines (on ne les insere qu'en un seul exemplaire), elles permettent d'inserer un element a un endroit precis (par exemple une image).
* Les balises sont parfois accompagnees d'attributs pour donner des indications supplementaires (exemple : `<image nom="photo.jpg" />`).
* Une page web est constituee de deux sections principales : un en-tete ( `<head>`  ) et un corps ( `<body>`  ).
* On peut afficher le code source de n'importe quelle page web en faisant un clic droit puis en selectionnant *Afficher le code source de la page*.

## Organisez votre texte

* Le HTML comporte de nombreuses balises qui nous permettent d'organiser le texte de notre page. Ces balises donnent des indications comme « Ceci est un paragraphe », « Ceci est un titre », etc.
* Les paragraphes sont definis par la balise `<p></p>`, et les sauts de ligne par la balise `<br/>`.
* Il existe six niveaux de titre, de `<h1></h1>`  a `<h6></h6>`  , a utiliser selon l'importance du titre.
* On peut mettre en valeur certains mots avec les balises `<strong>`  , `<em>`  et `<mark>`  .
* Pour creer des listes, on doit utiliser la balise `<ul>`  (liste a puces, non ordonnee) ou `<ol>`  (liste ordonnee). a l'interieur, on insere les elements avec une balise `<li>`  pour chaque item.

## Pratique

```htm
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Ma passion pour les animaux</title>
  </head>

  <body>
    <h1>Les animaux merveilleux</h1>
    <p>Voici mes animaux préférés :
    <ol>
      <li><strong>La giraffe</strong></li>
      <li>La galinette cendrée</li>
      <li>La rainette</li>
    </ol>
    </p>
  </body>
</html>
```

[Cheat sheet HTML](Resources/HTML-CHEAT-SHEET.png)

## Creez des liens (hyperlink)

* Les liens permettent de changer de page et sont, par defaut, ecrits en bleu et soulignes.
* Pour inserer un lien, on utilise la balise `<a>`  avec l'attribut href  pour indiquer l'adresse de la page cible. Exemple : `<a href="https://openclassrooms.com">`.
* On peut faire un lien vers une autre page de son site, simplement en ecrivant le nom du fichier : `<a href="page2.html">`.
* Les liens permettent aussi d'amener vers d'autres endroits sur la même page. Il faut creer une ancre avec l'attribut id  pour « marquer » un endroit dans la page, puis faire un lien vers l'ancre comme ceci : `<a href="#ancre">`.

## Inserez des images

* Il existe plusieurs formats d'images adaptees au Web :
	* JPEG : pour les photos
	* PNG : pour toutes les autres illustrations
	* GIF : similaire au PNG, plus limite en nombre de couleurs mais qui peut être anime

* On insere une image avec la balise  `<img />`. Elle doit obligatoirement comporter au moins ces deux attributs :  src  (nom de l'image) et  alt  (courte description de l'image).
* Si une image illustre le texte (et n'est pas seulement decorative), il est conseille de la placer au sein d'une balise  `<figure>`  . La balise  `<figcaption>`  permet d'ecrire la legende de l'image.

## Entrainez-vous en structurant votre CV

* etape 1 : Creez une page HTML.
* etape 2 : Ajoutez votre nom et votre prenom en titre principal.
* etape 3 : Ajoutez une photo miniature, sur laquelle on pourra cliquer pour avoir une version agrandie.
* etape 4 : Ajoutez 3 sections avec un titre secondaire (mon experience, mes competences, ma formation). Chaque section contient un paragraphe ou une liste a puce.






