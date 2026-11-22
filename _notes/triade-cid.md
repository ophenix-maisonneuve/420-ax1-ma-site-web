---
layout: default
title: Triade CID
nav_order: 2
has_toc: true
published: true
---

# Introduction

La sécurité informatique regroupe l’ensemble des mécanismes, procédures et politiques visant à protéger les systèmes informatiques et les données contre les accès non autorisés, les modifications malveillantes et les interruptions de service.

Dans un environnement informatique moderne, les données circulent constamment entre les utilisateurs, les serveurs, les applications et les équipements réseau. Qu’il s’agisse d’un service bancaire en ligne, d’une boutique électronique ou du réseau interne d’une entreprise, la sécurité vise à protéger ces données afin qu’elles demeurent accessibles uniquement aux bonnes personnes, qu’elles restent exactes et qu’elles soient disponibles au moment où l'on en a besoin.

Afin de mieux comprendre les objectifs de la sécurité informatique, on utilise généralement la **triade CID** (ou **CIA** en anglais) :

- **Confidentialité**
- **Intégrité**
- **Disponibilité**

La grande majorité des mécanismes de sécurité que nous mettons en place dans les environnements professionnels visent à protéger ces trois propriétés.

## Confidentialité

La confidentialité vise à empêcher les personnes non autorisées d'accéder à l'information.

Exemples :

- Chiffrement des communications avec HTTPS
- Chiffrement d'un disque dur
- Contrôle des permissions de lecture sous Linux

## Intégrité

L'intégrité garantit que les données n'ont pas été modifiées de façon non autorisée.

Exemples :

- Condensés cryptographiques (*hash*)
- Signatures numériques
- Contrôle de version
- Journaux d'audit

## Disponibilité

La disponibilité permet d'assurer que les ressources sont accessibles lorsqu'elles sont requises.

Exemples :

- Sauvegardes
- Alimentation redondante
- Réplication des données
- Protection contre les attaques par déni de service


{: .highlight-title}
> Et l'authentification dans tout cela ?
>
> Une quatrième propriété joue aujourd'hui un rôle extrêmement important en sécurité informatique : l'**authentification**. Cette propriété vise à confirmer qu'un utilisateur, un système ou l'émetteur d'une information est bien celui qu'il prétend être. Historiquement, l'authentification était souvent considérée comme un mécanisme contribuant à la confidentialité, à l'intégrité, ou aux deux à la fois, et elle n'a donc pas été incluse formellement dans le modèle CID. Avec l'évolution des réseaux et l'apparition de nouveaux protocoles de sécurité, son importance est toutefois devenue de plus en plus évidente.
>
> Des technologies telles que SSH, TLS et les certificats X.509 reposent fortement sur l'authentification afin de permettre aux utilisateurs et aux systèmes de vérifier avec qui ils communiquent avant d'échanger de l'information.