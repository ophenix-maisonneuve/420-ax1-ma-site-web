---
layout: default
title: Exercice CID - Corrigé
parent: Exercice CID
nav_order: 1
published: true
---

# Exercice: La gencive zen

## Corrigé

### Scénarios

| Scénario | CID + Auth | Protection possible
|-----------|-----|-----|-----|
| Un administrateur de la clinique utilise Telnet sur un réseau public et son mot de passe est intercepté. | C | Chiffrement des communications, par exemple utilisation de SSH |
| Une hygiéniste dentaire accède au portail web de son ordre professionnel mais ignore si elle est réellement connectée au bon site. | Authentification (+ C/I indirectement) | Utilisation de certificats X.509 avec HTTPS(TLS) |
| Un logiciel téléchargé par un dentiste a été modifié par un attaquant avant sa distribution. | I | Condensés, signatures numériques |
| Une attaque rend le portail web de la clinique inaccessible pendant plusieurs heures. | D | Analyse des vulnérabilités (Nessus, nmap, etc), pare-feu |
| Un rançongiciel chiffre tous les fichiers de radiographies des patients. | D + I | Sauvegardes et restauration, plan de reprise après sinistre solide |
