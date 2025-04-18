# Checkpoint-REST-API

## Votre Objectif
    Dans ce point de contrôle, vous allez effectuer une série d'instructions guidées pour créer une API REST en manipulant votre base de données avec mongoose.
  
    - PS : n'oubliez pas de commenter votre code avant de le soumettre.

## Instructions
  1. Démarrer un nouveau projet Node JS avec npm init.
  2. Installer Mongoose, Express et .env.
  3. Configurer les variables d'environnement avec .env.
  4. Lancer un serveur avec Express dans le fichier server.js.
  5. Connecter votre base de données localement ou avec Mongo Atlas.
  6. La structure des dossiers devrait être comme ceci :Copier config/ .env server.js
  7. Créer un dossier models et un fichier User.js à l'intérieur.
  8. Dans User.js, définir un schéma Mongoose et exporter le modèle. Vous l'utiliserez dans server.js.
  9. La structure des dossiers devrait être comme ceci : Copier config/ .env models/User.js server.js
  10. Dans server.js, créer quatre routes :
      
    - GET : RETOURNER TOUS LES UTILISATEURS
      
    - POST : AJOUTER UN NOUVEAU UTILISATEUR À LA BASE DE DONNÉES
    
    - PUT : ÉDITER UN UTILISATEUR PAR ID
    
    - DELETE : SUPPRIMER UN UTILISATEUR PAR ID
  12. Utiliser Postman pour tester chaque route.

## Liens utiles :

    - .env : https://www.npmjs.com/package/dotenv
    
    - Express.js : https://expressjs.com/
      
    - req.params && req.query : https://coursework.vschool.io/express-params-and-query/
      
    - Mongoose : https://mongoosejs.com/
      
    - REST API : https://www.youtube.com/watch?v=SLwpqD8n3d0
