# Doc installation

Installer nodeJS à cette adresse: https://nodejs.org/en/download/, et Git ensuite: https://git-scm.com/downloads.

Faire un clone du projet à l'endroit désiré.
`git clone https://github.com/doudbanks/recherche-membre.git`

Installer angular cli globalement en lancant cette commande: `npm install -g @angular/cli`.

Ensuite, se rendre dans le dossier du projet avec la ligne de commande et installer les dépendances en lancant cette commande: `npm install`.

Une fois terminé (ça prend généralement un peu de temps), on peut lancer la commande `ng serve` et se rendre à cette adresse dans son navigateur http://localhost:4200/ (de préférence chrome, firefox ou IE en version Edge).

Une clé API et un client ID valides doivent être ajoutés au fichier caché `src/assets/googleKeys.json` (voir `googleKeys.example.json`). Ces clés sont generées à partir de [Google Developer Console](https://console.cloud.google.com/apis/dashboard).

# Doc developer RechercheUtilisateur

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.


For a guide and details of how this app uses OAuth to work with the Google API, see [Using OAuth 2.0 to Access Google APIs](https://developers.google.com/identity/protocols/oauth2/javascript-implicit-flow).

For the full documentation see (Google API Client Library for JavaScript)[https://github.com/google/google-api-javascript-client
]

## API Keys & Client ID for 

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
