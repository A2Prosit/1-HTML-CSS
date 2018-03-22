Animateur : GILLY
Secrétaire : E Ah J’ai
Gestionnaire : Little Stone
Scribe : Flo

# Prosit 5.1 Allé

## Mots clés :
* **HTML:** language balise conçu pour représenter les pages web. Il permet de structurer le contenu de la page
* **CSS:** cascading style sheets, langages info qui décrit la présentation des doc html et xml
*	**Mockup:** maquette visuelle
*	**Responsive:** site ergonomique sur tout média
*	**Référencement:** ordre d'apparition dans un moteur de recherche
*	**Footer:** le bas de la page ou on peut mettre des liens utiles, style réseaux sociaux, contatcs
*	**Web:** www partie d'internet qui peut être accédé avec des hyperliens (via un navigateur)
*	**Navigateur:** logiciel conçu pour naviguer sur le world wide web

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

les ressources html5 sont classifié en plusieurs groupes:

* semantique : permet de décrire le contenu : <\section> <\article> <\nav> <\header> <\footer> <\aside>
* connectivité : permet la communication avec le serv
* offline et stockage : permet aux page de stocker des données côté client pour opérer plus efficacement hors ligne 
* Multimedia: vidéo, audio <\audio> <\video>
* 2D/3D graphics and effects: options de présentation <\canvas>
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

* html : balise principale
* head : en tête de la page
* body : corp de la page
* link / : lisaison avec une feuille de style
* meta / : métadonnées de la page
* script : code JS
* style : code CSS
* title : titre de la page
* nav : lien principaux de navigation
* footer : pied de page
* section : section de page
* article : article
* aside : info complémentaires

texte :

* abbr : abréviation
* blockquote : citation longue
* cite : citation du titre d'une oeuvre ou d'un évènement
* q : citation courte
* sup : exposant
* sub : indice
* strong : mise en valeur forte
* em : mise en valeur normale
* mark : mise en valeur visuelle
* h1, h2, h3, etc : titre de niveau x
* img / : image
* figure : figure
* figcaption : description de figure
* audio : son
* video : vidéo
* source : format source d'une balise audio et video
* a : lien hypertexte
* br / : retour à la ligne
* p : paragraphe
* hr / : ligne de séparation horizontale
* address : adresse de contact
* del : texte supprimé
* ins : texte inséré
* dfn : définition
* kbd : saisie clavier
* time : date ou heure

balises de listes : 

* ul : liste à puce
* ol : list numérotée
* li : éléments de la liste à puce
* dl : liste de définitions
* dt : terme à définir
* dd : définition du terme

balises tableaux :

* table : tableau
* caption : titre du tableau
* tr : ligne du tableau
* th : cellule d'en-tête
* td : cellule
* thread : section de l'en-tête
* tbody : section du corp
* tfoot : section de pied

basiles de formulaire:

* form : formulaire
* fieldset : grope de champs
* legend : titre d'un grp de champs
* label : libellé d'un champ
* input / : champ de formlaire
* textarea : zone detexte multiligne
* select : liste déroulante
* option : élément d'une liste déroulante
* optgroup : groupe d'éléments d'une liste déroulante

balises génériques (sans sens sémantique), elles n'ont d'intérêt que si on leur associe un attribut class, id ou style

* span : balise générique de type inline
* div : balise générique de type block

* class indique le nom de la classe css à utiliser
* id donne un nom à la balise qui doit être unique sur la pge, on s'en sert pour ,par exemple, créer un lien vers une ancre, un styleCSS de type ID, des manipulations en JS
* style permet d'indiquer directement le code css à appliquer, on peut donc l'utiliser et ne pas avoir de feuille css ... à ne pas faire
note : ces 3 attributs ne sont pas propre aux balises génériques 


tags spécifiques à html5 : https://www.w3schools.com/html/html5_new_elements.asp

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

En info un mockup désigne un prototype d'interface utilisateur. Il s'agit donc d'une maquette de ce à quoi ressemblera le logiciel visuellement

pencil pour créer des maquettes, montrer visuellement à quoi le site va ressembler

site pour en trouver déjà faits:

https://www.pixeden.com/free-graphics/
https://medialoot.com/free-resources/



###	Responsive Design

Permet la lecture opimale d'un site sur différents appareil (pc, mobile, tablette, liseuse,...)

Cela implique donc des redimensionnements (zooms), recadrages et défilement multidirectionnel

Pour avoir un site adapté au miéa on a trois solutions: 

* un site dédié : on créé plusieur versions du site, un test côté serveur détecte le type d'appareil et renvoie vers l'adresse dédiée (m.siteweb.com par exemple). **Av:** on peut modifier précisément la structure et le contenu du site, alternative "rapide" en attendant une refonte du site. **Inc:** contenu dupliqué, doit maintenir plusieurs sites et adresses, moins facile d'être indexé par un moteur de recherche
* une application native: appli dev en différents "langages" pour différents supports (iOS, Android, WindowsPhone) téléchargeable depuis le store.  **Av:** prise en charge des fonctionnalitées natives (accélérometre, GPS, etc), ergonome, l'utilisateur à un raccourci vers mon site sur son phone. **Inc :** dev spécifique dans plusieurs langages, coût de dev, licenses, maintenance, contenu non indexable par un moteur de recherche 
* un site responsive: coûts et délais inférieurs aux autres techniques, maintenance facilitée, MAJ multi-plateformes, on peut modifier un site déjà existant, google met en avant ces sites. **Inc :** nécessite des connaissances techniques, prévoir des tests sur différents médias pendant le dev, prob d'ergonomie et de perf, 25% plus long qu'une site non responsive

####différents web designs:

**Static**: 
dimension fixes (960px) peu importe l'écran

**Fluide/liquid :**

toutes les largeures sont en pourcentage de fenêtre jusqu'a un min/max

**Adaptative**

statique amélioré : largeur fixe mais différentes selon la taille de l'écran. On la détecte avec CSS3 Media Queries. On a des points de rupture (480px, 768px,1024px, etc) et on a autant de gabarit fixes que de points de rupture

**Responsive :**

Amélioration du design fluide associé à des méthodes ***CSS3 Media Queries*** pour modifier les style pour s'adapter à la taille de l'écran peu importe le point de rupture

###	Référencement

SEO en anglais Search Engine Optimization: ensemble des techniques permettant d'améliorer la visibilité d'un site web, son positionnement dans les résultats d'un moteur de recherche

Repose avant tout sur la notion de mos clés, ce que l'utilisateur va chercher. 

on peut check si son site est référencé en cherchant " site:nomdusite.com"
pour faire référencer son site on peut remplir des formulaires en ligne comme google analytics ou AT internet

https://www.google.com/webmasters/tools/submit-url
http://www.bing.com/toolbox/webmaster
https://fr.aide.yahoo.com/kb/SLN2217.html
http://www.exalead.com/search/web/submit/


On ne peut pas utiliser le pouvoir de l'argent afin de mieux référencer son site car les moteurs de recherche indexent gratuitement le contenu des sites. On peut cependant payer pour avoir de la pub autour des résultats "naturels" (= le lien sponso) on parle alors de SEM (Marketing) plutôt que SEO


Optimiser le référencement: ne pas tout mettre sur la page d'acceuil et négliger le reste puisque c'est le reste qui interesse les utilisateurs.
Bien choisir les titres, les URL, lesmétas, etc adaptés **pour chaque page**

tips:
contenu original et attractif
titre bien choisi
URL adaptées
corp de texte lisible par les SE
balises META décrivant le contenu de la page: meta description et meta robots (index,follow; noindex,follow;indexnofollow;noindex,nofollow
liens
attributs ALT pour décrire le contenu des images
MAJ régulière pour augment la fréquence des bots d'indexation
mettre les pages inutiles ou doublon dans robots.txt
si on a du contenu dupiqué ajouter une balise canonical ( <link rel="canonical" href="http://votresite/pagefinale"/> )


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

**Internet Explorer !**
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

world wide web consortium W3C fondé en 94 chargé de promouvoir la compatibilité des technologies du world wide web : html5, html, xhtml, xml, rdf, sparql, css, xsl, png, svg, soap
