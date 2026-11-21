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

La confidentialité consiste à empêcher la divulgation d'informations à des personnes non autorisées. Une donnée est considérée confidentielle lorsque seules les personnes ou les systèmes possédant les autorisations requises peuvent y accéder. Toute autre personne doit alors être incapable de consulter cette information, même si elle parvient à obtenir une copie des données ou à intercepter les communications.

De nos jours, la confidentialité est omniprésente dans les systèmes informatiques. Un dossier médical, un relevé bancaire, un courriel privé ou encore les informations personnelles d'un(e) employé(e) contiennent tous des données qui ne devraient être accessibles qu'à un nombre limité de personnes. Un bris de confidentialité peut entraîner des pertes financières, des poursuites judiciaires, une atteinte à la réputation d'une organisation ou encore le vol d'identité.

Il est important de noter que toutes les informations ne nécessitent pas le même niveau de protection. Certaines données sont destinées à être publiques, alors que d'autres doivent demeurer confidentielles.

Par exemple, une entreprise peut rendre publics ses produits, ses services et les coordonnées de son service à la clientèle tout en protégeant sa liste de clients, ses données financières ou ses secrets commerciaux. Le niveau de confidentialité à appliquer dépend donc de la nature et de la sensibilité de l'information à protéger.

## Bris de confidentialité

Voici quelques exemples de scénarios où un bris de confidentialité est constaté :

### Vol de mots de passe

Lorsqu'un attaquant obtient une base de données contenant des mots de passe ou leurs condensés (*hash*), il peut tenter de réutiliser ces informations afin de compromettre les comptes des utilisateurs. Les nombreuses fuites de données qui surviennent chaque année démontrent qu'une simple erreur de configuration ou une vulnérabilité logicielle peut exposer des millions d'identifiants.

### Interception du trafic réseau

Avant l'aparition de protocoles sécurisés comme HTTPS ou SSH, plusieurs applications transmettaient les informations en clair sur le réseau. Une personne ayant accès au trafic pouvait alors consulter les mots de passe, les courriels ou tout autre contenu transmis.

### Fuite de données

Une mauvaise configuration d'un serveur ou d'un service infonuagique peut exposer des documents sensibles à Internet. Même si le système n'est pas compromis par un attaquant, une simple erreur administrative peut avoir des conséquences importantes.

## Mécanismes de protection

Il existe heureusement plusieurs mécanismes et protocoles permettant de protéger la confidentialité des données. En voici quelques exemples :

### Contrôle d'accès

Le contrôle d'accès consiste à limiter les ressources auxquelles un utilisateur peut accéder. Sous Linux, par exemple, les permissions et les groupes permettent de déterminer quels utilisateurs peuvent lire, modifier ou exécuter un fichier.

### Authentification et autorisation 

Avant d'accorder l'accès à une ressource, il est nécessaire de confirmer l'identité de l'utilisateur. Cette authentification peut reposer sur un mot de passe, une clé SSH, un certificat numérique ou encore plusieurs facteurs combinés. Une fois l'utilisateur authentifié, un contrôle des accès (appelé autorisation ou *authorization* en anglais) peut être appliqué.

### Chiffrement

Le chiffrement constitue l'un des mécanismes les plus importants pour assurer la confidentialité. Même si un attaquant parvient à intercepter les données ou à obtenir une copie des fichiers, celles-ci demeureront inutilisables sans la clé de déchiffrement appropriée.

Plusieurs protocoles comme HTTPS, TLS, SSH et les VPN reposent largement sur ce principe afin de protéger les communications contre l'écoute et l'interception.
