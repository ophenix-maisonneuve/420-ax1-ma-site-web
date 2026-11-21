---
layout: default
title: Exercice CID - Corrigé
parent: Exercice CID
nav_order: 1
published: false
---

# Exercice: La gencive zen

## Corrigé

### Scénarios

| Scénario | CID | Protection possible | Sujet introduit |
|-----------|-----|-----|-----|
| Un administrateur utilise Telnet sur un réseau public et son mot de passe est intercepté. | C | Chiffrement des communications | SSH |
| Un utilisateur accède à un site bancaire mais ignore s'il est réellement connecté à sa banque. | Authenticité (+ C/I indirectement) | Certificats numériques | TLS / Certificats X.509 |
| Un logiciel téléchargé a été modifié par un attaquant avant sa distribution. | I | Signature numérique | Cryptographie |
| Une attaque rend un site Web inaccessible pendant plusieurs heures. | D | Filtrage réseau et contrôle du trafic | pare-feu (pfSense), analyse des vulnérabilités (Nessus, nmap) |
| Un rançongiciel chiffre tous les fichiers d'une entreprise. | I + D | Sauvegardes et restauration | Sauvegardes |
