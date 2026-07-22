---
ref: privacy
lang: fr
permalink: /fr/privacy/
title: Politique de confidentialité
description: Helmer ne collecte aucune donnée personnelle. Votre position ne quitte pas votre appareil.
---

<p class="meta">
App : <code>com.iperka.helmer</code> · En vigueur depuis le 22 juillet 2026 · Dernière mise à jour le 22 juillet 2026
</p>

> **En bref.** Helmer ne collecte **aucune donnée personnelle**. Il n'y a ni
> compte utilisateur, ni outil d'analyse, ni traçage, ni publicité, ni SDK
> tiers. Votre position, votre vitesse et les données de la veille au mouillage
> ne quittent pas votre appareil.

## Responsable du traitement

Michael Beutler, Suisse — un développeur indépendant, pas une entreprise.

Questions sur cette politique : [support@iperka.com](mailto:support@iperka.com)

## Données de localisation

Helmer demande l'accès à votre position afin d'afficher votre position sur la
carte, votre vitesse GPS, les zones riveraines de 300 m et 150 m de l'art. 53 de
l'ordonnance sur la navigation intérieure (RS 747.201.1) autour de votre bateau
et — si vous activez la veille au mouillage — de combien votre bateau a dérivé.

- La position est lue depuis le GPS de votre appareil et **traitée entièrement
  sur l'appareil**.
- Elle n'est **jamais transmise**, ni à moi, ni à un serveur, ni à un tiers.
- Si vous activez la veille au mouillage, Helmer enregistre la position de
  l'ancre, le rayon d'alarme et la trace de dérive dans le stockage local de
  l'application, afin que l'alarme survive à un redémarrage de l'app ou du
  téléphone. Arrêter la veille efface ces données.
- L'accès à la position en arrière-plan (« Toujours ») sert **uniquement** à
  l'alarme de dérive, pour qu'elle puisse surveiller le bateau écran verrouillé.
  Vous pouvez le refuser et continuer à utiliser toutes les autres fonctions.

Vous pouvez révoquer l'accès à la position à tout moment dans **Réglages →
Confidentialité et sécurité → Service de localisation → Helmer**.

## Réglages enregistrés sur votre appareil

Les préférences telles que l'unité de vitesse (km/h ou nœuds), la vitesse de
croisière, les options d'itinéraire et les couches de carte affichées sont
enregistrées localement sur votre appareil. Elles ne contiennent aucune
information personnelle et ne sont synchronisées avec aucun service cloud.

## Suppression de vos données

Toutes les données de Helmer sont locales à votre appareil. Supprimer
l'application les supprime entièrement. Il n'y a rien à supprimer de mon côté,
puisque je ne reçois jamais rien.

## Connexions réseau

Helmer a exactement **une** connexion réseau :

**Mesures de vent de MétéoSuisse.** Pour afficher le vent actuel et les
avertissements de tempête, Helmer télécharge les fichiers publics de mesures de
vent sur 10 minutes, publiés en données ouvertes de l'administration fédérale
sur `data.geo.admin.ch`. L'application télécharge le fichier de mesures
**national** et sélectionne les stations pertinentes localement — elle
n'envoie **pas** votre position, votre identité ni aucune information vous
concernant dans la requête. Comme pour toute requête sur internet, l'adresse IP
de votre appareil est techniquement visible pour ce serveur ; son traitement
relève de la déclaration de confidentialité de l'administration fédérale. Les
données de vent sont mises en cache sur votre appareil afin que l'application
continue de fonctionner sans réseau sur l'eau.

Helmer ne contient aucun autre code réseau. Il n'a pas de backend, et je
n'exploite aucun serveur avec lequel Helmer communique. La géométrie des lacs,
les zones riveraines, les ports, les stations d'essence, les zones réglementées
et les lignes de bateaux sont **intégrés à l'application** et ne nécessitent
aucune connexion.

## Cartes

La carte est affichée avec le framework MapKit d'Apple. Les tuiles, la recherche
et les points d'intérêt proviennent d'Apple Plans et relèvent de la
[politique de confidentialité d'Apple](https://www.apple.com/legal/privacy/).
Je n'en reçois aucune donnée.

## Notifications

L'alarme de dérive utilise uniquement des notifications **locales**, y compris
les alertes critiques d'Apple pour que l'alarme puisse percer le mode silencieux
et Ne pas déranger. Il n'y a ni serveur push ni jeton d'appareil — les
notifications sont programmées par l'application sur votre appareil.

## Étiquette de confidentialité de l'App Store

Helmer est déclaré **« Aucune donnée collectée »** sur l'App Store, ce qui
correspond à ce qui est décrit ci-dessus.

## Enfants

Helmer ne collecte de données de personne, y compris des enfants, et ne contient
ni publicité, ni achat intégré, ni contenu généré par les utilisateurs.

## Vos droits

Cette politique est rédigée pour satisfaire la loi fédérale suisse sur la
protection des données (LPD) et le règlement général sur la protection des
données de l'UE (RGPD). Comme aucune donnée personnelle vous concernant n'est
collectée, transmise ou conservée par moi, il n'existe aucun ensemble de données
sur lequel exercer un droit d'accès, de rectification, d'effacement ou de
portabilité. N'hésitez pas à m'écrire à
[support@iperka.com](mailto:support@iperka.com) pour toute question à ce sujet.

## Modifications de cette politique

Si une future version de Helmer modifie le traitement des données, cette page
sera mise à jour et la date de « dernière mise à jour » ci-dessus changera. Les
modifications importantes seront également signalées dans les notes de version
sur l'App Store.
