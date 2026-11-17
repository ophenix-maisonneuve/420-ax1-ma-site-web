---
layout: default
title: Intégrité
parent: Triade CID
nav_order: 2
has_children: false
has_toc: true
published: false
---

# Intégrité

L'intégrité consiste à assurer que les données demeurent exactes, complètes et exemptes de modifications non autorisées. Lorsqu'une information possède un bon niveau d'intégrité, les utilisateurs peuvent avoir confiance qu'elle correspond toujours à ce qui a été créé, approuvé ou enregistré à l'origine.

Dans plusieurs contextes, l'intégrité est aussi importante que la confidentialité. Par exemple, dans un système bancaire, le fait qu'un attaquant puisse modifier un montant de transaction représente un risque tout aussi important que la divulgation de cette transaction. De la même façon, dans un établissement d'enseignement, une modification non autorisée des notes des étudiants pourrait avoir des conséquences importantes même si aucune information n'a été divulguée.

L'intégrité ne concerne pas uniquement les attaques malveillantes. Les erreurs humaines, les bogues logiciels et certaines défaillances matérielles peuvent également altérer les données et compromettre leur exactitude.

## Exemples de failles d'intégrité

### Modification non autorisée de données

Un utilisateur possédant des privilèges excessifs pourrait modifier ou supprimer des informations qui ne devraient pas être accessibles. Cette situation est particulièrement préoccupante lorsqu'il s'agit de dossiers financiers, médicaux ou administratifs.

### Logiciel malveillant

Un virus ou un rançongiciel peut modifier des fichiers, corrompre des bases de données ou remplacer des documents légitimes par des versions altérées.

### Attaque de l'homme du milieu

Lorsqu'un attaquant est capable d'intercepter une communication, il peut tenter de modifier certaines données avant qu'elles n'atteignent leur destination. Sans mécanisme de validation, les deux parties pourraient croire que les informations sont légitimes.

## Mécanismes de protection

### Condensés cryptographiques

Les fonctions de hachage permettent de produire une empreinte numérique unique représentant les données d'origine. Une simple modification du contenu entraîne un changement du condensé, ce qui permet de détecter rapidement une altération.

### Signatures numériques

Une signature numérique permet non seulement de détecter les modifications apportées à un document, mais également de confirmer l'identité de son auteur. Les signatures numériques jouent un rôle fondamental dans les certificats X.509 et dans plusieurs protocoles sécurisés modernes.

### Journaux d'audit

Les journaux d'audit enregistrent les actions effectuées sur un système. Ils permettent de retracer les modifications, d'identifier leur auteur et de comprendre la séquence des événements ayant conduit à un incident.

### Contrôle des changements

Les systèmes de contrôle de version comme Git permettent de suivre l'évolution des fichiers et d'identifier précisément quelles modifications ont été apportées et par qui.