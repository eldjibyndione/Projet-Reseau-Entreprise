# Historique des versions

## v0.2 — Configuration de base Cisco

Date : 23 septembre 2026

### Ajouts

- Configuration du hostname de S1, S2 et R1
- Désactivation de la recherche DNS automatique
- Configuration du mot de passe privilégié
- Configuration de la console
- Configuration des lignes VTY
- Ajout d’une bannière de sécurité
- Activation du chiffrement des mots de passe simples
- Configuration d’un délai d’inactivité de 10 minutes
- Sauvegarde des configurations dans la startup-config
- Ajout des captures de vérification
- Ajout des configurations texte
- Ajout de la documentation de la version 0.2

### État

- Les trois hostnames sont corrects
- Les mots de passe console fonctionnent
- Le mot de passe privilégié fonctionne
- Les bannières apparaissent à la connexion
- Les configurations sont conservées après réouverture du projet


## v0.1 - Topologie de base

Date : 22 septembre 2026

### Ajouts

- Création du projet Ndione Technologies.
- Ajout d’un routeur Cisco 2911.
- Ajout de deux commutateurs Cisco 2960.
- Ajout de six ordinateurs.
- Ajout d’une imprimante réseau.
- Ajout d’un serveur interne.
- Connexion des appareils aux commutateurs.
- Connexion de S1 à S2.
- Connexion de R1 à S1.
- Attribution de noms professionnels aux appareils.
- Création de la première capture de la topologie.

### État

- Les connexions entre les appareils finaux et les switches sont actives.
- La connexion S1-S2 est active.
- La connexion R1-S1 reste rouge, car l’interface du routeur n’est pas encore activée.
- Aucune adresse IPv4 n’est encore configurée.
- Aucune configuration Cisco IOS n’est encore réalisée.