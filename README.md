Animateur : GILLY
Secrétaire : E Ah J’ai
Gestionnaire : Little Stone
Scribe : Flo

# Prosit 5.1 Allé

## Mots clés :
* HTML
* CSS
*	Mockup
*	Responsive
*	Référencement
*	Footer
*	Web
*	Navigateur

## Analyse du besoin :
*	Pourquoi ?	Adapter le site à différente plateforme
*	Comment ?	Avec le HTML/CSS
*	Quoi ?		En le rendant responsive

## Contraintes :
*	3 semaines

## Problématique :
*	Comment rendre un site web responsive ?

## Généralisation :
*	Design

## Hypothèses :
*	Un site responsive est un site qui se redimensionne
*	Le footer est en bas de la page
*	Le header est en HAUT de la page
*	Le CSS est une mise en forme de l’HTML
*	Le navigateur est un interpréteur Web
*	Chaque navigateur est différent (You don’t say bro)
*	HTML est un langage balise

## Plan d’action :

### **Etudes**

### HTML

HyperText Markup Language. La base de la base d'un site web, défini le contenu et l'agencement de la page (jusqu'a ce qu'arrive le CSS et le JS)

HyperText/HyperLink  est un lien connectant des pages webs.
HTML utilise le markup pour annoter du texte, des images, et autre contenu

HTML inclu des éléments spéciaux comme  <\head> <\title> <\body> <\header> <\footer> <\article> <\section> <\p> <\div> <\span> <\img>

Les tags html ne sont pas case sensitive 


HTML5 

les ressources html5 sont classiié en plusieurs groupes:

* semantique : permet de décrire le contenu : <\section> <\article> <\nav> <\header> <\footer> <\aside>
* connectivité : permet la communication avec le serv
* offline et stockage : permet aux page de stocker des données côté client pour opérer plus efficacement hors ligne 
* Multimedia: vidéo, audio <\audio> <\video>
* 2D/3D graphics and effects: options de présentation
* Performance et integration: permet l'opimisation et une meilleure utilisation du hardware
* Device access : input outpout <\input> <\output>
* Styling: permet de faire des thèmes sophistiqués


code minimal d'une page html:

	<!DOCTYPE html>
	<html>
		<head>
			<meta charset="utf-8" />
			<title>Titre</title>
		</head>
		
		<body>
			
		</body>
	</html>

**liste non exausitve de basiles:**

html : balise principale
head : en tête de la page
body : corp de la page
link / : lisaison avec une feuille de style
meta / : métadonnées de la page
script : code JS
style : code CSS
title : titre de la page
nav : lien principaux de navigation
footer : pied de page
section : section de page
article : article
aside : info complémentaires

texte :

abbr : abréviation
blockquote : citation longue
cite : citation du titre d'une oeuvre ou d'un évènement
q : citation courte
sup : exposant
sub : indice
strong : mise en valeur forte
em : mise en valeur normale
mark : mise en valeur visuelle
h1, h2, h3, etc : titre de niveau x
img / : image
figure : figure
figcaption : description de figure
audio : son
video : vidéo
source : format source d'une balise audio et video
a : lien hypertexte
br / : retour à la ligne
p : paragraphe
hr / : ligne de séparation horizontale
address : adresse de contact
del : texte supprimé
ins : texte inséré
dfn : définition
kbd : saisie clavier
time : date ou heure

balises de listes : 

ul : liste à puce
ol : list numérotée
li : éléments de la liste à puce
dl : liste de définitions
dt : terme à définir
dd : définition du terme

balises tableaux :

table : tableau
caption : titre du tableau
tr : ligne du tableau
th : cellule d'en-tête
td : cellule
thread : section de l'en-tête
tbody : section du corp
tfoot : section de pied

basiles de formulaire:

form : formulaire
fieldset : grope de champs
legend : titre d'un grp de champs
label : libellé d'un champ
input / : champ de formlaire
textarea : zone detexte multiligne
select : liste déroulante
option : élément d'une liste déroulante
optgroup : groupe d'éléments d'une liste déroulante

balises génériques (sans sens sémantique), elles n'ont d'intérêt que si on leur associe un attribut class, id ou style

span : balise générique de type inline
div : balise générique de type block

class indique le nom de la classe css à utiliser
id donne un nom à la balise qui doit être unique sur la pge, on s'en sert pour ,par exemple, créer un lien vers une ancre, un styleCSS de type ID, des manipulations en JS
style permet d'indiquer directement le code css à appliquer, on peut donc l'utiliser et ne pas avoir de feuille css ... à ne pas faire
note : ces 3 attributs ne sont pas propre aux balises génériques 

###CSS

Utilisé pour qu'HTML garde son but qui est de structurer le document, le css s'occupe de la présentation

la présentation d'un site webet quelque chose qui peut changer très vite pour des raisons de marketing afin de ne pas voir à reprendre l'ensemble des pages webs lors du changement de style de présentation des règles ont étés mises en place : une info ne doit être mémorisée qu'à un seul endroit. C'est ce que permet une feuille de style. Le XML va au bout de cette logique : il organise l'info et mermet d'aller la chercher par une requête semblable à celles des bdd et laisse aux feuilles de syle XLS la transformation de l'info pour la présentation

Note : css laisse quand même à désirer en terme de positionnement des éléments


Les specs des feuilles de styles devinrent une recommendation du consortium W3C en décembre 1996 sous le nom CSS1 Cascading Style Sheets , level 1

le level 1 à été révisé en 1999 mais en mai 1998 est sorti css2 qui précise:

des styles pour dofférents médias (écran, impression, braille, etc)
les polices de caractères téléchargeables
le positionnement des éléments html


On peut appliquer le css directement sur une page html ou en référençant une feuille de style interne ou externe

	<h2 style="text-decoration: overline">

ou avec feuille interne avec <\style>

		<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">

	<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="fr" lang="fr">
	  <head>
	    <title>Premiers pas</title>
	    <meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1" />
	    <style type="text/css"> (...) </style>
	  </head>
	  <body> (...) </body>
	</html>

type est obligatoire; il précise le type MIME de la feuille utilisé qui sera généralement "text/css"
media spécifie le type de média auquel la feuille de style est destinée

* screen, valeur par défaut
* tty, ancient système d'affichage à police fixe
* tv, tv faible résolution
* projection, projecteurs
* handheld, appareil de poche
* print, imprimantes
* braille, lecteur de braille
* aural, navigateurs à synthèse vocale
* all, TOUT

ou avec feuille externe : à l'aide de <\link> dans l'en-tête

	<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
	<html lang="fr">
	  <head>
	    <title>Premiers pas</title>
	    <link rel="stylesheet" type="text/css" href="../styles/site.css">
	    <meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
	  </head>
	  <body> (...) </body>
	</html>



**Le "cascade" de CSS**

Il fait référence à la méthode de résolution de conflits. Puisqu'on peut placer plusieursfeuillesde styles de un même document les instructions de style successives peuvent s'opposer (elles sont en cascades)
Il y a donc une hiérarchie : feuille de style extérieure < style dans le head < style dans la balise

syntaxe :

* un sélecteur
* une/plusieurs déclaration(s) qui est une suite propriété: valeur, les déclarations sont séparées par des points virgules et sont placées entre accolades. Ex:

	h2
    {
        text-align : center;
        color : black;
    }

on peut grouper plusieurs balises avec des virgules

	h2, h3, ul
    {
        text-align : center;
        color : green;
    }

et on peut créer des sélecteurs contextuels: il sufit de mettre plusieurs selcturs à la suite séparés par des espaces :

	h2 em
		{
			color : blue;
		}
cette règle s'appliquera uniquement sur les éléments em contenus dans un élément h2, il est toujours possible de faire des regroupement

avec *class*: 

on peut regrouper des éléments différents en leur donnant un même nom de classe 

	<p class="truc">Ceci est un paragraphe d'introduction.</p>
on peut ensuite définir les propriétées de cette classe dans le css
	
	.truc
    {
        color : red;
    }

pseudo classes :

exemple des liens: un lien à trois états différents:

* actif (on click/met la souris dessus)
* à visiter
* déjà visité

on appelle pseudo classe de a ces trois états

	a:active
    {
        text-decoration : overline;
    }

	a:link
    {
        color : blue;
        font-style : italic;
    }

	a:visited
    {
        color : green;
        font-weight : bold;
    }

La syntaxe est donc [selecteur]:[pseudo-classe] {declaration}


**Pseudo-éléments**

CSS1 décrit plusieurs pseudo-éléments :

* first-line : modifie le style de la première ligne d'un paragraphe.

* first-letter : modifie le style de la première lettre d'une phrase.

* first-child : modifie le style du premier élément-enfant du sélecteur courant.

* after : modifie le style de ce qui suit l'élément.

* before : modifie le style de ce qui précède l'élément.

###	Modélisation de site (Mockup, voir les différents outils existants)
###	Responsive Design
###	Référencement
###	Navigateur (moteur)

Un moteur de rendu HTML permet aux logiciels d'afficher les éléments d'une page web.

Depuis la complexifications des standards le nombre de moteur à réduit et plusieurs navigateur utilise le même

Gecko de la fondation Moilla, entre autres utilisés par :

* Mozilla Firefox
* Mozilla Thunderbird
* Camino
* Netscape

KHTML du projet KDE et son dérivé Webkit:

* NetFont
* WebCore d'Apple 

Blink dérivé de WebKit:

* Google chrome
* Chromium
* Opera
* Vivaldi

Trident de Microsoft:

**Internet Explorer**
Netscape
Yahoo Explorer

Tasman de Microsoft

* Version mac d'internet explorer

Elektra d'Opera Software:

* Opera 4  à 6

Presto d'Opera Software:

* Opera 7+
* Adobe Creative Suite 2

iCab de iCab Company

* iCab 4-

Mariner de Netscape Communication Corporation (jamais commercialisé)

* Netscape Communicator 5



### Standards

