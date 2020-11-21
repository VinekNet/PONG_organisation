# [Aled tout est cassé](Al_Ed.md)



# PONG_organisation

Le but de ce repo est de maintenir notre PONG en bonne santé.

#### La team
La liste des projets [est visible ici](team.md)

## Semaine du 02 au 9 Nov 2020
Nous devons mettre en ligne notre repo Pong pour que tout le monde puisse y avoir accès ainsi qu'avoir un terrain dans lequel la balle bouge vers le coin en bas à droite.

### Coordinateurs de la semaine
CHAMPOIRAL Jonas, 
DOUILLET Antoine, 
HENG Alexis, 
MAZENC Lucas 
et BORIE David

### Personnes n'ayant pas de lien sur leur repo pour accéder à pong :

Pensez à mettre en ligne et pas juste copier l'url du questionnaire en changeant le nom unserious game par pong.


### Readme vide :

BORIE David

### La balle ne bouge pas :

Quentin Paris


### Commentaires manquants ( ‘ - ‘ signifie qu’ils sont manquants sur seulement un ou deux fichiers) :



Vincent Gauthier
Romain -
Brieux
Anatole
Gaëtan -
Quentin Jeune
Bilal
Loïc
Gregoire
Mickaël
Vincent Callede
Yvain
David

## Semaine du 09 au 15 Nov 2020

### Consignes générales. On attend de vous que:

_ votre projet respecte ce qui a été fait en cours;

_ votre repo soit propre;

_ vos noms de variables soient en français;

_ votre code Javascript et CSS soit bien indenté et commenté avec vos propres mots;

_ votre code javascript respecte les conventions décrites un peu partout ici.

### Objectifs de la semaine. Vous devez:

_ faire démarrer la balle dans une direction ou dans l'autre aléatoirement (aléatoire en anglais ça se dit...);

_ intégrer les raquettes HTML + CSS + classes JS (les raquettes font 25% de la hauteur du terrain et 10px de large);

_ cacher (en css) les murs (les borders) gauche et droite du terrain pour que ça ressemble à notre pong final;

_ faire bouger les raquettes toutes seules de haut en bas open_mouth;

_ faire en sorte que la balle ne dépasse pas du terrain à droite et en bas (soustraction de la taille de la balle).

### Coordinateurs de la semaine:

BARBATO Loïc, 
PARIS Quentin,
FLAESCH-PERREAU Mickaël,
CHATELAIN Gaëtan,
HABIB Corentin.

### Incohérences d'indentations:

Vincent	GAUTHIER;
Loïc	BARBATO;
Quentin	JEUNE-LAPANOUZE;
Maxime	BALANSARD.

### Incohérences dans l'utilisation des commentaires ou de son code (" /* ", " // ", surcharge ou manque de commentaire, ...):

Vincent	GAUTHIER;
Lucas	MAZENC;
Alexis	HENG;
Quentin	JEUNE-LAPANOUZE;
Quentin	PARIS;
Anatole	PAGNUCCO;
Bilal	DENNEL;
Corentin	HABIB;
Grégoire	FONTANELLI;
Maxime	BALANSARD;
Yvain	DI COSTANZO;
David	BORIE.

### Un ou plusieurs objectifs non atteints:

_ La balle ne démarre pas dans une direction et/ou dans l'autre aléatoirement:

Quentin	JEUNE-LAPANOUZE;
Anaïs	BISCARAS;
Bilal	DENNEL;
Corentin	HABIB;
Maxime	BALANSARD;
Maxime	FRERE;
David	BORIE.

_ Les raquettes n'ont pas été intégrées, ou ne respectents pas une ou plusieurs de leurs conditions souhaitées (taille, positionnement, nombre, mouvement...):

Gaëtan	CHATELIN;
Quentin	JEUNE-LAPANOUZE;
Maxime	FRERE;
David	BORIE.

_ Les bordures gauche et droite du terrain sont toujours visibles:

Andréa	MICHEL;
David	BORIE.

_ La balle dépasse du terrain à droite et/ou en bas:

Quentin	JEUNE-LAPANOUZE (condition non vérifiable);
Bilal	DENNEL;
Maxime	FRERE (condition non vérifiable);
David	BORIE (condition non vérifiable).

### La page du Pong ne s'affiche pas (le remplissage des objectifs n'a pas pu être confirmé):

Quentin	PARIS.

## Semaine du 16 au 22 Nov 2020
Tout le monde devrait avoir une balle qui bouge et qui réagit avec les raquettes + des raquettes qui bougent à la main

### Coordinateurs de la semaine
MICHEL Andréa
JEUNE Quentin
DENNEL Bilal
CAQUELIN Brieux 

### Deadline
Samedi 21 Nov dans la nuit du matin

### Objectifs : 
- dans le setInterval 3 lignes seulement
- contrôler les raquettes gauche et droite respectivement avec les touches A/Q et P/M du clavier 
- getters sur bas et droite (balle et raquettes)
- setters sur bas et droite (balle et raquettes)
- faire rebondir la balle sur les raquettes
- si la balle passe à côté des raquettes, on remet la balle au centre (X et Y) et c'est reparti

### Un ou plusieurs objectifs non atteints:
_ dans le setInterval 3 lignes seulement:

  Vincent Gauthier
  
  Gaetan Chatelain
  
  Mickaël Flaesch-Perreau
  
  Lucas Mazenc
  
  Anatole Pagnucco
  
  Andrea Michel
  
  Bilal Dennel
  
  Corentin Habib
  
  Jonas Champoiral
  
  Maxime Balansard
  
  Yvain Di Costanzo
  
  David Borie (je trouve pas le set intervalle dans pong.js)
  
_ contrôler les raquettes gauche et droite respectivement avec les touches A/Q et P/M du clavier

_ getters sur bas et droite (balle et raquettes):

_ setters sur bas et droite (balle et raquettes):

_ faire rebondir la balle sur les raquettes

_ si la balle passe à côté des raquettes, on remet la balle au centre (X et Y) et c'est reparti:

### Commentaires manquants ( ‘ - ‘ signifie qu’ils sont manquants sur seulement un ou deux fichiers) :


### Erreur de contrôle des raquettes et de rebond sur les raquettes :

Vincent Gauthier - pas de controles pas de rebond.

Loïc - pas de rebond et mauvais binding des touches de la raquette gauche ("z-s" au lieu de "a-q").

Gaétan - pas de controles pas de rebond.

Lucas Mazenc - pas de contrôles pas de rebond.

Mickael - pas de contrôles pas de rebond.

Anaïs - la balle sort de l'ecran en bas à droite et pas de contrôles (j'ai pas pu vérifier les rebonds du coup).

Anantole - pas de contrôles pas de rebond.

Antoine - Bug quand la balle touche le bord et pas de contrôles pas de rebond.

Corentin - Raquette décalée et pas de contrôles pas de rebond.

Grégoire - pas de rebond.

Jonas - pas de contrôles pas de rebond.

Maxime	BALANSARD - pas de contrôles pas de rebond.

Maxime	FRERE - Rien en bouge.

Yvain - Raquettes décalé et rien en bouge.


### ERREUR DANS LA MATRICE ET RIEN NE CHARGE:
Quentin Jeune
Quentin Paris
Bilal Dennel
Andréa Michel
David Borie
