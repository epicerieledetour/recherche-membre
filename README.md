# Doc installation 

## Exigences d'installation

- Familiarisation avec la ligne de commande (CMD ou PowerShell)

  - Voir [cet article](https://www.commentcamarche.net/informatique/windows/197-utiliser-l-invite-de-commandes-de-windows/) ou [cette vidéo](https://www.youtube.com/watch?v=b_njDaEo3wY) pour plus d’info.
  - **Toutes les commandes ci-dessus seront exécutées dans l’invite de commande** ( Windows+R puis CMD).



- Git installé sur l’ordinateur (si c’est pas la première fois, Git est déjà installé).

  -  Pour en savoir plus sur git et ça utilisation [voir ce tutoriel](https://docs.microsoft.com/fr-ca/learn/modules/intro-to-git/0-introduction) ou [cette vidéo](https://www.youtube.com/watch?v=hPfgekYUKgk).

  - Vérifier si il est installé et a jour avec la commande:

  -  `git --version`
    - La version devrait être affichée.

  - Si pas installé ou pas a jour, [télécharger et installer Git](https://git-scm.com/downloads).



- NodeJs installé sur l’ordinateur.

  - Vérifier si il est installé avec la commande:

  - `npm version`
  - La version devrait être affichée.

  - Si pas installé ou pas a jour, [télécharger et installer NodeJs](https://nodejs.org/en/download/). (64 bits)



## Installation


1. Avec la ligne de commande, se déplacer dans le dossier Documents

    `cd ~/Documents`



2. Faire un clone du projet dans le dossier *Documents* avec la commande git:

    `git clone https://github.com/doudbanks/recherche-membre.git`



3. Se rendre dans le dossier du projet avec la ligne de commande

    `cd recherche-membre`
    
    et installer les dépendances en lançant la commande:

    `npm install` (ca peut etre long)

   

4.  Une clé API et un client ID valides doivent être ajoutés au fichier caché *recherche-membre/src/assets/googleKeys.json.* Ce fichier n’est pas inclus dans le projet pour des raisons de sécurité. Ces clés sont générées à partir de [Google Developer Console](https://console.cloud.google.com/apis/dashboard).

    Comme exemple (non fonctionnel) voir le fichier *googleKeys.example.json* fourni dans le dossier du projet *recherche-membre/src/assets/*.



5.  Lancer le serveur du projet avec la commande:

    `npm run serve`



6. Se rendre à l’adresse dans son navigateur http://localhost:4200/



7. En haut à droite, selectioner *Connexion* et utilizer la compte de la caisse.



8.  Placer le racourci *Recherche Utilisateur.lnk* (trouvé dans le dossier racine du projet) sur le Bureau de l'ordinateur pour le lancer faciliment.
