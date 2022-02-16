node -v // Pour verifer la version de node (>= 14)
npm init -y // Initialiser le projet en acceptant les paramètres par défaut
npm i --save-dev electron // Installer electron
package.json > "main": "main.js" // Préciser le point d'entrée de l'application
scripts > "start": "electron ." // Ajouter le script start pouvant être lancer avec "npm run start"
"author": "Moustapha Kachab" // Mettre à jour le nom de l'auteur

// Se rendre dans la doc officielle https://www.electronjs.org/fr/docs/latest/tutorial/quick-start
// Copier main.js preload.js et index.html

// Lancer npm run start pour lancer l'application

npm i electron-packager --save-dev // Installer electron-packager pour pouvoir générer un executable
npx electron-packager . // Générer un éxecutable