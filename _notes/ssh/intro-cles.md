---
layout: default
title: Clés asymétriques (intro)
parent: SSH
nav_order: 1
---

## Introduction aux clés asymétriques

Plusieurs technologies modernes utilisent une paire de clés appelée **clés asymétriques** :

- une **clé publique**
- une **clé privée**

La clé publique peut être distribuée librement à quiconque souhaite communiquer avec son propriétaire. À l'inverse, la clé privée doit demeurer secrète en tout temps.

Ces deux clés sont liées mathématiquement et permettent de réaliser certaines opérations impossibles avec les systèmes de chiffrement traditionnels utilisant une seule clé.

Les clés asymétriques sont utilisées dans de nombreuses technologies modernes :

- SSH
- HTTPS
- TLS
- Certificats X.509
- Signatures numériques

Dans le contexte de SSH, elles servent principalement à authentifier un utilisateur ou un serveur.

Nous reviendrons plus en détail sur leur fonctionnement dans la section consacrée à la cryptographie.