Animateur : GILLY
Secrétaire : E Ah J’ai
Gestionnaire : Little Stone
Scribe : Flo

# Prosit 5.1 Allé

## Mots clés :
* HTML : HyperText Markup Language
* CSS : Cascading Style Sheets
*	Mockup : Terme informatique pour désigner une maquette d'une interface utilisateur
*	Responsive : Approche de la conception web qui vise à avoir une expérience de lecture et de navigation optimale pour l'utilisateur quel que soit l'appareil. 
*	Référencement : Place dans les moteurs de recherches
*	Footer : Bas de page dans une page HTML
*	Web : La toile, permet de consulter avec un navigateur des pages accessibles sur des sites
*	Navigateur : Application qui permet de naviguer sur le web

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

* HTML / CSS (syntaxe)
* Modélisation de site (Mockup, voir les différents outils existants)
* Responsive Design
* Référencement
* Navigateur
* Standards


# 1 - Le HTML :
- HTML (HyperText Markup Language)
- Initialement dérivé du SGML (Standard Generalized Markup Language)
- Définit et décrit le contenu d'une page sous différentes couches
- HyperText réfère aux hyperlien (redirection), liens étant l'aspect fondamentaux du Web
- HTML utilise des balises
- Structurer sémantiquement & logiquement / Inclure ressources (images) / Formulaires / Programmes informatiques / Créer documents
- Souvent compléter par du Javascript et du CSS

**moteur de rendu HTML** : Composant logiciel qui permet aux applications d'afficher les éléments d'une page web. On en retrouve peu de part la complexification des standards :
* SeaMonkey
* Mozilla Firefox
* Servo
* Camino
* {...}

`EXEMPLE - Strucure minimale`

\<!DOCTYPE html>

\<html> => *Balise principale*

    <head> => *En-tête de la page (Liasons, métadonnées, script, css, titre)
        <meta charset="utf-8" />
        <title>Titre</title>
    </head>

    <body> ⇒ Corp de la page
    
    </body>
\</html>

**Mémentos  des balises HTML** : https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/memento-des-balises-html

**DERNIERE VERSION - HTML5** :

- Nouvelle version (nouveaux éléments  attributs & comportements)
- Nouveau set de techno qui permet de construire des sites & applications plus divers et puissants

`Ajouts :`
- **Sémantique** : Décrire plus précisément le contenu de la page (nouvelles balises, formules de maths, parser...) 
- **Connectivité** : Permet de communiquer avec le serveur de nouvelles manières (web socket, évènements serveurs, vidéoconférence)
- **Offline and storage** : Permet aux pages d'enregistrer des données clientes & donc plus efficace (cache, file reader)
- **Multimedia** : Des classes primaires ont étés conçus pour des vidéos et des audio (balises, videoconference, enregistrer depuis caméra, sous-tîtres & chapîtres)
- **2D/3D graphics & effects** : Plus grande diversité de présentation (dessiner avec des canvas (toiles), formats)
- **Performance & intégration** : Fournit une meilleure vitesse, et un meilleur usage du matériel de l'ordinateur (traitement, threads, historique, drag & drop, full screen, pointeur, events)
- **Device access** : Permet l'utilisateur de nombreux équipements en entrée et en sortie (caméra, boutons écrans, geolocalisation...)
- **Styling** : Plus de thèmes pour des auteurs (Compatibilité avec dernières nouveautés CSS)

# 2 - Le CSS :

- CSS (Cascading Style Sheets)
- Compatible avec les navigateurs sous leurs dernières versions (pour avoir toutes les fonctionnalités)
- mettre en forme un document HTML ou XML
- décrit comment les éléments doivent-être interprétés par des règles
- Ces règles peuvent-être appliqués à un ou plusieurs documents et portent sur :
	- Positionnement
	- Alignement
	- Police
	- Couleurs
	- Marges
	- Espacements
	- Bordures
	- Image de fond
	- {...}
- Ces règles sont à appliquer sur des balises, des classes, ou des ID (élément unique)

**Framework**:  (ensemble de composants structurés qui sert à créer les bases et à organiser le code informatique pour faciliter le travail)


**Bootstrap** :

Framework CSS et embarque les composants HTML et CSS. Il utilise un système de grille simple et efficace pour mettre en ordre l'aspect visuel d'une page. On y retrouve des styles pour les boutons, les formulaires, et concevoir avec peu de lignes un site web rapidement. Bootstrap vient de Twitter.
- Cross-Browser
- Fait gagner du temps
- Normalisation des styles
- Grille pour le positionnement des éléments
- Éléments complémentaires (boutons / esthétiques...)
- Framework prend en compte le responsive design

MAIS 
- Nécessite de bien le connaître 

# 3 - Le responsive Design :

Approche de la conception web qui vise à avoir une expérience de lecture et de navigation optimale pour l'utilisateur quel que soit l'appareil. 

![](https://developers.google.com/search/mobile-sites/imgs/mobile-seo/transition.png)

Le client doit pouvoir effectuer ses tâches habituelles en toute simplicité. Il faut donc :
- Déterminer les étapes de parcours pour accéder à ce qu'il a besoin
- Offrir de la facilité
- Un seul URL 
- Un même thème (unifié)

En choisissant le responsive Design, on conserve le même URL et le même code HTML (pas besoin d'un site mobile pour le mobile)

**Les médias Queries** = Responsive Design sur lequel on va prendre des données supplémentaires pour changer le style (type écran, impression, taille, téleviseur, couleurs, resolutions, tailles...). On peut y fixer des min et des max. Très utile pour changer la couleur ou la police.

**La diffusion dynamique :**

Configuration dans laquelle le serveur diffuse un code HTML / CSS différent sur le même URL en fonction du user-agent qui demande à accéder à la page, se faisant en conservant la même URL. Pour se faire, il faut détecter ces user-agents (ce qui comporte de nombreux risques)

# 4 - Web & Législation:
https://www.service-public.fr/professionnels-entreprises/vosdroits/F31228

Tout les sites à titre professionnel doivent indiquer : 
- Nom / prénom / domicile
- Pour une société : raison sociale, adresse, montant du capital => CF Registre du commerce
- courrier électronique
- Numéro d'inscription au registre du commerce (RC) + RM (si artisanale)
- Pour un commerce : N° Identification fiscale
- Nom & adresse autorité
- Nom du directeur
- Si vente : prix exprimés en € et TTC
- Numéro de déclaration simplifiée CNIL

Pour les cookies :
- Informer les utilisateurs 
- Donner leur consentement
- Fournir aux internautes le moyen de refuser

# 5 - Référencement :

On y retrouve de nombreuses astuces :
- Réfléchir aux mots clés et les intégrer dans son site 
- Travailler les menus, les URL, et les balises avec ces mots clés
- Prendre en compte les recherches réalisées à l'oral via un smartphone
- Utiliser les balises de manières optimale (descriptions ...) => Facilitent l'indexation & ont une incidence sur le taux de clic
- Optimiser la navigation mobile : Google détecte les sites dont la navigation est optimale (responsive design)
- Améliorer la qualité de ses textes : Contenus aux attentes => Partage par les utilisateurs => référencement
- Booster la vitesse de chargement : Google pénalise les trop longs.
- Eviter bugs & pages d'erreurs 
- Sécuriser votre site pour éviter d'être blacklist de google
- Installer certificat SSL & passer du HTTP à HTTPS
- Google MyBusiness permet d'ajouter toutes les infos pour aider google à comprendre (infos à propos entreprise)
- Gagner en visibilité sur les réseaux sociaux
- Créer un fichier sitemap, c'est un .xml qu'on lui fournit à google pour l'aider à indexer. Il propose aussi des infos détaillés sur des problèmes que peut rencontrer notre site après l'analyse d'un bot de google.


Il est également possible d'acheter des mots clés sur les moteurs de recherches, il s'agir alors d'emplacement publicitaires. Il existe de nombreuses agences spécialisés dedans, cependant un référencement doit-être progressif.

# 6 - Outils :

**W3C ou Markup Validation** Service permet de coller son code et de vérifier que les standards sont respectés.
Son service peut verifier le HTML, le CSS, mais pas le PHP.

http://validator.w3.org/

**Test d'optimisation mobile** Petit site qui teste le responsive desgin du site : on rentre une URL et il nous dis si la configuration ne superpose  pas d'élements... 

https://search.google.com/test/mobile-friendly

**Pencil project** : GUI Open Source, qui permet de faire du maquettage.


![](https://cdn2.techadvisor.fr/cmsdata/features/3656883/meilleur_navigateur_internet_2017.png)



