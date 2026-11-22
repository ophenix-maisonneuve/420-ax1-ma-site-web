---
layout: default
title: Disponibilité
parent: Triade CID
nav_order: 3
published: true
---

# Disponibilité

La disponibilité consiste à assurer que les données, les applications et les services demeurent accessibles lorsqu'ils sont nécessaires. Un système peut offrir une excellente confidentialité et une excellente intégrité, mais demeurer inutilisable si les utilisateurs ne sont pas en mesure d'y accéder au moment opportun.

Dans plusieurs organisations, la disponibilité représente un enjeu majeur. Une interruption de quelques minutes peut empêcher les opérations normales, tandis qu'une panne prolongée peut entraîner des pertes financières importantes. Les environnements bancaires, hospitaliers, industriels ou gouvernementaux doivent souvent maintenir des niveaux de disponibilité extrêmement élevés.

Les menaces à la disponibilité sont nombreuses et ne proviennent pas uniquement d'attaques informatiques. Les erreurs humaines, les pannes matérielles, les catastrophes naturelles ou les interruptions de courant peuvent avoir le même effet qu'une attaque malveillante : rendre un service inaccessible.

## Non-disponibilité

Voici quelques exemples de scénarios où des ressources ou services peuvent devenir indisponibles :

### Bris matériel

Les disques durs, les alimentations électriques et les équipements réseau possèdent tous une durée de vie limitée. Une défaillance peut rendre certaines données ou certains services complètement inaccessibles ou même causer des pertes de données permanentes.

### Déni de service

Une attaque par déni de service (ou *denial of service, DoS* en anglais) vise à empêcher les utilisateurs légitimes d'utiliser un service. Dans une attaque distribuée (*DDoS*), plusieurs machines compromises sont utilisées simultanément afin de saturer les ressources visées. Dans les deux cas, la technique reste la même : un pirage trouve une manière d'empêcher un service de répondre (surcharge, *crash* répétitif, etc) et exploite cette faille en continu.

### Erreur humaine

Une mauvaise configuration, la suppression accidentelle d'un fichier ou l'échec d'une mise à jour peuvent interrompre le fonctionnement normal d'un système pendant plusieurs heures.

### Catastrophe

Un incendie, une inondation, un tremblement de terre, des dégâts aux lignes électriques ou toute autre catastrophe majeure peut rendre un centre informatique complètement inaccessible.

## Mécanismes de protection

Il existe plusieurs techniques permettant d'augmenter la résilience et la disponibilité des services et des données, notamment :

### Sauvegardes

Les sauvegardes (*backups*) permettent de récupérer les données après un incident. Une stratégie de sauvegarde efficace inclut généralement des copies multiples, des tests de restauration périodiques et un stockage dans un ou plusieurs emplacement(s) distinct(s).

### Redondance

La redondance consiste à éliminer les points de défaillance uniques. Plusieurs serveurs, plusieurs liens réseau ou plusieurs alimentations électriques peuvent ainsi assurer la continuité des opérations malgré une panne.

### Mode "haute disponibilité"

Certains systèmes sont conçus pour continuer à fonctionner même lorsqu'un composant devient indisponible. Les mécanismes de répartition de charge (*load balancer*) et les agrégats de serveurs (*clusters*) sont des exemples courants de solutions de haute disponibilité. 

### Plan de reprise après sinistre

Il peut être très difficile, voire impossible, de prévoir ou d'empêcher un sinistre. Il vaut donc mieux, pour une organisation, de prévoir la façon dont les services seront rétablis après un incident majeur, peu importe la nature de cet incident. Ce plan définit généralement les responsabilités, les procédures de restauration et les délais de reprise visés.