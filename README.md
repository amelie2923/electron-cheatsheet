# Electron

Ce que permet cette techno : framework Javascript (Nodejs) opensource qui permet créer des applications de bureau natives multi-plateformes avec les technologies web comme JS/HTML et CSS. Il est basé sur Node.js et Chromium (la base libre de plusieurs navigateurs web, dont Google Chrome).
Le but : créer des applications de bureau pour Windows, MacOS et d'autres plateformes en utilisant une seule base de code.

**Comment ça fonctionne ?**

Electron permet de construire des applications multi-plateformes en empaquetant des fichiers de code prévus pour un site web et en les transformant en un fichier exécutable comme un programme Desktop classique.
Le but : éviter d’avoir à maintenir en parallèle plusieurs projets de développement dans le cas d’une application multi-plateforme.
Electron donne accès au système de fichier, à toutes les API web de Chromium ainsi que celles du système d'exploitation.
Cependant : si l'application que l'on souhaite développer se base sur les API d'un système en particulier, elle ne fonctionnera pas sur les autres.

**Les +**
-Simple à prendre en main
-Un seul code à maintenir pour une seule application de bureau compatible avec les principaux systèmes d'exploitation
-Maintenance plus facile
-Coûts de développement réduits
-Gestion des mises à jour automatique
-Compatible avec Windows App Store et Mac App Store

**Les -**

-Une app = un navigateur. Consommation en RAM et en CPU sera au moins égale à celle du navigateur sous-jacent. Pas gênant pour une seule app mais peut être problématique si plusieurs apps multi-plateformes tournent en même temps
-Code source visible

**Etapes :**

1. Vérifier les versions de node et npm

**Cette commande devrait afficher la version de Node.js**
node -v

**Cette commande devrait afficher la version de npm**
npm -v

2. Créer un nouveau dossier pour l'appli Electron et lancer npm init depuis ce dossier

npm init

3. Installer eletron en tant que dépendance de développement dans l'application

npm install --save-dev electron

Cela permet de travailler sur de multiples applications avec des versions différentes d'Electron.

4. Créer/configurer les fichiers : main.js, index.html, package.json

5. Lancer l'appli avec npm start

npm start

Il est possible également de démarrer avec l'application QuickStart d'Electron en suivant ces étapes :

1. Installer l'application de demo Quick Start

https://github.com/electron/electron-quick-start

2. Se rendre dans le dossier source

cd electron-quick-start

3. Installer les dépendances

npm install

4. Lancer l'application

npm start






