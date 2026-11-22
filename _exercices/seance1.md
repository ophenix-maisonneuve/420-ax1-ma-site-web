---
layout: default
title: Exercice CID
nav_order: 1
published: true
---

# Exercice: La gencive zen

![La gencive zen](../assets/images/gencivezen.png)

## Mise en situation

La dentiste propriétaire de la clinique dentaire **La gencive zen** a récemment assisté à une conférence intitulée ***Vous protégez plus que les dents de vos patients***. Cette conférence portait sur les impacts potentiels d'une cyberattaque ou d'une fuite ciblant les données des patients. Consciente que le réseau de sa clinique dentaire a été mis en place de façon "organique", sans réelle phase de conception ni analyse de sécurité, elle est maintenant inquiète quant à la protection des données de ses patients. 

Il y a plusieurs semaines, elle avait embauché un(e) stagiaire du programme d'AEC en gestion de réseau et sécurité au Collège de Maisonneuve (c'est-à-dire vous!), et votre stage commence justement aujourd'hui! Quelle coïncidence, on pourrait presque croire que c'est arrangé!

Le conférencier avait présenté la triade CID (confidentialité, intégrité, disponibilité) ainsi que divers scénarios hypothétiques afin que les participants réalisent qu'il n'est pas toujours évident de protéger les données correctement. Par contre, votre nouvelle patronne a oublié de prendre des notes et elle a oublié à quelle(s) catégorie(s) appartenait chaque scénario ainsi que les mesures de mitigation qui avaient été présentées. Elle vous demande donc d'analyser les divers scénarios, de les catégoriser correctement ainsi que de proposer des mesures de mitigation applicables.

---

## Objectifs

- Comprendre les trois composants principaux de la triade C, I, D (confidentialité, intégrité, disponibilité)
- Comprendre l'apport de l'authentification et son lien avec la triade CID
- Proposer des solutions à haut niveau permettant d'améliorer la confidentialité, l'intégrité, la disponibilité ou l'authentification

---

## Travail à réaliser

### Scénarios

| Scénario | CID + Auth| Protection possible 
|-----------|-----|-----|
| Un administrateur de la clinique utilise Telnet sur un réseau public et son mot de passe est intercepté. | | | 
| Une hygiéniste dentaire accède au portail web de son ordre professionnel mais ignore si elle est réellement connectée au bon site.  | | |
| Un logiciel téléchargé par un dentiste a été modifié par un attaquant avant sa distribution.  | | |
| Une attaque rend le portail web de la clinique inaccessible pendant plusieurs heures.  | | |
| Un rançongiciel chiffre tous les fichiers de radiographies des patients.  | | |


### Étapes

Pour chaque scénario ci-haut...

1. Analysez le scénario afin de bien comprendre ses implications
1. Associez le scénario à l'une (ou plusieurs) des composantes CID + Authentification
1. Pour chaque scénario, tentez de penser à une mesure de protection couramment utilisée