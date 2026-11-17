---
layout: default
title: Confidentialité
parent: Triade CID
nav_order: 1
has_children: false
has_toc: true
published: false
---

# Confidentialité

La confidentialité consiste à empêcher la divulgation d'informations à des personnes non autorisées. Lorsqu'une donnée est considérée confidentielle, seules les personnes ou les systèmes possédant les autorisations requises doivent pouvoir y accéder. Toute autre personne doit être incapable de consulter cette information, même si elle parvient à obtenir une copie des données ou à intercepter les communications.

La confidentialité est présente dans pratiquement tous les systèmes informatiques modernes. Un dossier médical, un relevé bancaire, un courriel privé ou encore les informations personnelles d'un employé contiennent tous des données qui ne devraient être accessibles qu'à un nombre limité de personnes. Une violation de confidentialité peut entraîner des pertes financières, des poursuites judiciaires, une atteinte à la réputation d'une organisation ou encore le vol d'identité.

Il est important de noter qu'une information n'a pas besoin d'être secrète au sens absolu du terme pour nécessiter un certain niveau de confidentialité. Une entreprise peut, par exemple, rendre publics ses produits et ses services tout en protégeant ses listes de clients, ses données financières ou ses secrets commerciaux.

## Exemples de failles de confidentialité

### Vol de mots de passe

Lorsqu'un attaquant obtient une base de données contenant des mots de passe ou leurs condensés, il peut tenter de réutiliser ces informations afin de compromettre les comptes des utilisateurs. Les nombreuses fuites de données qui surviennent chaque année démontrent qu'une simple erreur de configuration ou une vulnérabilité logicielle peut exposer des millions d'identifiants.

### Interception du trafic réseau

Avant l'aparition de protocoles sécurisés comme HTTPS ou SSH, plusieurs applications transmettaient les informations en clair sur le réseau. Une personne ayant accès au trafic pouvait alors consulter les mots de passe, les courriels ou tout autre contenu transmis.

### Fuite de données

Une mauvaise configuration d'un serveur ou d'un service infonuagique peut exposer des documents sensibles à Internet. Même si le système n'est pas compromis par un attaquant, une simple erreur administrative peut avoir des conséquences importantes.

## Mécanismes de protection

### Contrôle d'accès

Le contrôle d'accès consiste à limiter les ressources auxquelles un utilisateur peut accéder. Sous Linux, par exemple, les permissions et les groupes permettent de déterminer quels utilisateurs peuvent lire, modifier ou exécuter un fichier.

### Authentification

Avant d'accorder l'accès à une ressource, il est nécessaire de confirmer l'identité de l'utilisateur. Cette authentification peut reposer sur un mot de passe, une clé SSH, un certificat numérique ou encore plusieurs facteurs combinés.

### Chiffrement

Le chiffrement constitue l'un des mécanismes les plus importants pour assurer la confidentialité. Même si un attaquant parvient à intercepter les données ou à obtenir une copie des fichiers, celles-ci demeureront inutilisables sans la clé de déchiffrement appropriée.

Les protocoles HTTPS, TLS, SSH et les VPN reposent largement sur ce principe afin de protéger les communications contre l'écoute et l'interception.
