# La Ludothèque Android — version locale

Six jeux hors connexion : échecs, dames, jeu de l’oie, Snakes & Ladders, Puissance 4, Histoires & Images.

## Créer un APK avec GitHub

1. Créer un dépôt GitHub et y envoyer **le contenu de ce dossier** (pas le ZIP).
2. Ouvrir **Actions** > **Construire APK Android** > **Run workflow**. Le workflow s’exécute aussi après un push sur main/master.
3. À la fin du job, ouvrir **Artifacts** et télécharger **ludotheque-android-apk**.
4. Décompresser l’archive téléchargée, puis installer `app-debug.apk` sur le téléphone Android (autoriser l’installation de cette source si demandé).

L’APK est une version de test signée avec une clé de développement. Pour publier sur Google Play, créer un APK/AAB de release signé.

## Lancer dans un navigateur

`npm install` puis `npm run dev`

## Limites

En solo, Puissance 4 propose un adversaire automatique simple. Les autres jeux proposent un mode entraînement où une personne contrôle les deux camps. Les règles des dames et du jeu de narration sont simplifiées. Aucun compte Firebase ni Internet nécessaire pour jouer une fois l’application installée.
