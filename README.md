# Doc installation 

## Exigences d'installation

- Familiarisation avec la ligne de commande (CMD ou PowerShell)

- - Voir [cet article](https://www.commentcamarche.net/informatique/windows/197-utiliser-l-invite-de-commandes-de-windows/) ou [cette vidéo](https://www.youtube.com/watch?v=b_njDaEo3wY) pour plus d’info.
  - **Toutes les commandes ci-dessus seront exécutées dans l’invite de commande** ( Windows+R puis CMD).



- Git installé sur l’ordinateur (si c’est pas la première fois, Git est déjà installé).

- - Pour en savoir plus sur git et ça utilisation [voir ce tutoriel](https://docs.microsoft.com/fr-ca/learn/modules/intro-to-git/0-introduction) ou [cette vidéo](https://www.youtube.com/watch?v=hPfgekYUKgk).

  - Vérifier si il est installé et a jour avec la commande:

  - - `git --version`
    - La version devrait être affichée.

  - Si pas installé ou pas a jour, [télécharger et installer Git](https://git-scm.com/downloads).



- NodeJs installé sur l’ordinateur.

- - Vérifier si il est installé avec la commande:

  - - `npm version`
    - La version devrait être affichée.

  - Si pas installé ou pas a jour, [télécharger et installer NodeJs](https://nodejs.org/en/download/). (64 bits)



## Installation



1. Installer angular cli globalement en lançant la commande:
2. `npm install -g @angular/cli` (ca peut prendre qq minutes)

3. 

4. Note: Si jamais il y a des messages de <<Warning>> c’est correct. du genre :

5. ```bash
   npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
   npm WARN deprecated har-validator@5.1.5: this library is no longer supported
   ```



2. Avec la ligne de commande, se déplacer dans le dossier Documents

1. `cd ~/Documents`



3. Faire un clone du projet dans le dossier désiré (Ex. dossier *Documents)* avec la commande git:

1. `git clone https://github.com/doudbanks/recherche-membre.git`



4. Se rendre dans le dossier du projet avec la ligne de commande `cd recherche-membre` et installer les dépendances en lançant la commande:

   `npm install` (ca peut etre long)

   

5. Une clé API et un client ID valides doivent être ajoutés au fichier caché *recherche-membre/src/assets/googleKeys.json.* Ce fichier n’est pas inclus dans le projet pour des raisons de sécurité. Ces clés sont générées à partir de [Google Developer Console](https://console.cloud.google.com/apis/dashboard).

1. Comme exemple (non fonctionnel) voir le fichier *googleKeys.example.json* fourni dans le dossier du projet *recherche-membre/src/assets/*.



6. Lancer le serveur du projet avec la commande:

1. `ng serve`



7. Se rendre à l’adresse dans son navigateur http://localhost:4200/



9. En haut à droite, selectioner *Connexion* et utilizer le compte de la caisse.



10. Placer le racourci *Recherche Utilisateur.lnk* (trouvé dans le dossier racine du projet) sur le Bureau de l'ordinateur pour le lancer faciliment.



## Development server

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
