---
layout: default
title: Clés asymétriques (intro)
parent: SSH
nav_order: 1
---

## Introduction aux clés asymétriques

Plusieurs technologies modernes utilisent une paire de clés appelée **clés asymétriques** :

- une **clé publique** pouvant être distribuée librement à quiconque.
- une **clé privée** devant absolument demeurer secrète en tout temps.

Ces deux clés sont liées mathématiquement de façon à ce qu'une opération effectuée avec l'une des clés peut être renversée avec l'autre clé. Par exemple, le chiffrement avec la clé publique peut être déchiffré avec la clé privée correspondante.

Les clés asymétriques permettent de réaliser certaines opérations impossibles avec les systèmes de chiffrement traditionnels utilisant une seule clé et sont utilisées dans de nombreuses technologies modernes :

- SSH
- HTTPS
- TLS
- Certificats X.509
- Signatures numériques

Dans le contexte de SSH, elles servent principalement à authentifier un utilisateur ou un serveur. Nous reviendrons plus en détail sur leur fonctionnement dans la section consacrée à la cryptographie.