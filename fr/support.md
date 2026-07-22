---
ref: support
lang: fr
permalink: /fr/support/
title: Assistance
description: Aide, contact et questions fréquentes sur Helmer.
---

<p class="lede">Helmer est une application pour les propriétaires de bateaux sur
les lacs suisses : les zones riveraines légales sur une carte, un compteur GPS,
une veille au mouillage avec alarme de dérive et les données de vent de
MétéoSuisse.</p>

## Contact

E-mail **[support@iperka.com](mailto:support@iperka.com)** — je réponds
généralement en quelques jours. Helmer est développé par une seule personne,
merci donc de votre patience.

Pour m'aider à corriger un problème rapidement, indiquez :

- votre appareil (p. ex. iPhone 15 Pro, Apple Watch Series 9) et la version d'iOS
- la version de Helmer (onglet Réglages, tout en bas)
- ce que vous avez fait, ce que vous attendiez et ce qui s'est passé à la place
- une capture d'écran, si le problème est visible

## Prérequis

<div class="table-scroll" markdown="1">

| Plateforme | Version minimale |
|---|---|
| iPhone / iPad | iOS 17.0 |
| Mac | macOS 14.0 |
| Apple Watch | watchOS 10.0 |
| CarPlay | véhicules compatibles |

</div>

Disponible en français, allemand, anglais et italien.

## Questions fréquentes

### Pourquoi Helmer demande-t-il la localisation en arrière-plan ?

Uniquement pour la veille au mouillage. Pour vous avertir que votre bateau
chasse sur son ancre pendant votre sommeil, l'application doit continuer à lire
le GPS écran éteint. Si vous refusez l'accès « Toujours », tout le reste —
carte, zones, compteur — fonctionne normalement.

### L'alarme de mouillage ne s'est pas déclenchée

Vérifiez trois choses :

1. L'**autorisation de notification**, y compris les *alertes critiques*, est
   accordée dans Réglages → Notifications → Helmer. Ce sont les alertes
   critiques qui permettent à l'alarme de percer le mode silencieux et
   Concentration.
2. La localisation est réglée sur **« Toujours »**, pas sur « Lorsque l'app est
   active ».
3. La **veille est active** — la bannière passe au vert lorsqu'elle surveille.

### Quel rayon régler pour la veille au mouillage ?

Règle simple : longueur de mouillage + longueur du bateau + une marge GPS
d'environ 15 m. Helmer avertit déjà à 80 % du rayon avant de déclencher l'alarme
complète.

### Pourquoi ma vitesse diffère-t-elle légèrement de mon traceur de cartes ?

Helmer lit la vitesse sur le fond depuis le GPS de l'appareil. Un GPS grand
public dérive de quelques dixièmes de km/h ; Helmer applique donc une tolérance
de 1 km/h avant de signaler un dépassement en zone riveraine. Les vagues, les
capotes et les hard-tops dégradent aussi la réception ; l'application affiche la
précision GPS actuelle pour que vous puissiez en juger.

### Helmer fonctionne-t-il sans réseau mobile ?

Oui. La carte, les zones, la position, la vitesse et la veille au mouillage sont
calculées entièrement sur l'appareil et ne nécessitent aucune connexion. Seules
les données de vent demandent un réseau — sans signal, Helmer continue
d'afficher la dernière mesure téléchargée, horodatée pour que vous sachiez de
quand elle date.

### D'où viennent les zones riveraines ?

Elles découlent de l'art. 53 de l'ordonnance sur la navigation intérieure
(RS 747.201.1) :

> **Zone riveraine extérieure (150–300 m)** — max. 10 km/h pour les bateaux
> motorisés.

> **Zone riveraine intérieure (150 m)** — à emprunter uniquement pour accoster,
> mouiller ou franchir un passage étroit, par le trajet le plus court, et jamais
> parallèlement à la rive.

Les lignes sont calculées à 150 m et 300 m de la rive OpenStreetMap.

### D'où viennent les données de vent ?

Des mesures de vent et de rafales sur 10 minutes de MétéoSuisse, publiées en
données ouvertes (© MétéoSuisse). Il s'agit d'un réseau de mesures, pas d'une
prévision.

### Quelle est la fiabilité des ports, stations d'essence et zones réglementées ?

Ces données proviennent de la communauté OpenStreetMap et peuvent être
incomplètes ou obsolètes. Vérifiez sur place avant de compter dessus — en
particulier pour le carburant.

### Les lignes de bateaux sont-elles des positions en direct ?

Non. Ce sont des tracés indicatifs selon l'horaire. Les bateaux de ligne sont
prioritaires : cédez le passage, laissez leur route libre et ne mouillez pas sur
la ligne.

### Comment passer des km/h aux nœuds ?

Dans l'onglet Réglages. Le choix s'applique au compteur, à l'app Watch et à
CarPlay.

### Ma position est-elle envoyée quelque part ?

Non. Voir la [politique de confidentialité](/fr/privacy/) — votre position ne
quitte pas votre appareil.

## Avis de sécurité

> Helmer est une aide et non une carte de navigation officielle. Le chef de bord
> reste responsable du respect des prescriptions. Les zones affichées sont une
> représentation au mieux de la géométrie légale et peuvent s'écarter des
> sources faisant foi. Ne comptez jamais sur la seule alarme de mouillage par
> conditions dangereuses.

## Suggestions et bogues

Vos idées sont bienvenues à [support@iperka.com](mailto:support@iperka.com) —
dites-moi sur quel lac vous naviguez et ce qui rendrait Helmer plus utile.
