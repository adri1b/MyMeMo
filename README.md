# MyMeMo
Un petit logiciel de notes

J'avais besoin d'un petit logiciel de saisie rapide de notes, ainsi que la possibilité d'y attacher des fichiers, à l'instar d'un courrier électronique.
Le design peut être considéré basique, mais je préfère m'attarder sur des fonctionnalités plutôt qu'une apparence esthétique.

Par la même occasion, cela permettra de montrer certaines possibilités de WinDev.

Ce qu'il faut donc savoir :
- Utilisation de WinDev 27 Update 3 (01F270103n)
- Les fichiers sont au format texte
- Utilisation du moteur de base de données SQLite
- Aucune analyse

Fonctions et techniques utilisées :
- Compilation dynamique
- Pagination sur la table principale
- Options des menus contextuels affichées ou masquées selon le contexte
- Utilisation du timestamp UNIX pour les dates et heures
- Utilisation de requêtes SQL
- Utilisation de la technique WDMémoBinaire pour enregistrer les fichiers en base de données
