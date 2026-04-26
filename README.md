# Pizza Master (TP 6)

## Aperçu
Pizza Master est une application Android native présentant une interface utilisateur moderne et dynamique avec un élégant thème sombre. Elle propose une sélection gastronomique de pizzas, offrant aux utilisateurs les recettes, la liste des ingrédients, les prix et les étapes de préparation détaillées.

## Fonctionnalités
- **Catalogue Gastronomique :** Parcourez une liste exhaustive de pizzas soigneusement sélectionnées, accompagnées d'images uniques et appétissantes.
- **Thème Sombre Moderne :** Profitez d'une interface utilisateur (Material3) très contrastée qui adopte les codes esthétiques du design moderne.
- **Pages de Recettes Détaillées :** Plongez dans les détails des ingrédients et les instructions de préparation étape par étape pour chaque délicieuse pizza.
- **Interface Réactive :** Utilisation d'effets de barre d'outils rétractable (CollapsingToolbar) fluides avec de légers dégradés assombris lors du défilement.

## Vidéo de Démonstration

https://github.com/user-attachments/assets/demo/demo.mp4

---
*Si le lecteur vidéo ne s'affiche pas correctement selon votre outil de lecture Markdown, vous pouvez également consulter le fichier directement :*
<br>**[Cliquez ici pour voir la Vidéo de Démonstration](assets/demo/demo.mp4)**
<br>Ou utilisez ce lecteur : <br>
<video src="assets/demo/demo.mp4" controls="controls" width="300"></video>

## Technologies Utilisées
- **Langage :** Java
- **Android SDK :** API Minimum 24, Target SDK 34
- **Composants UI :** Vues Android, Material Design 3 (MaterialCardView, CollapsingToolbarLayout)

## Architecture
L'application s'exécute dans le package `com.gourmet.pizzamaster`. La modélisation des données utilise une classe statique `VaultManager` non modifiable en mémoire, offrant un flux de données factices robuste parfaitement intégré aux Adapters (adaptateurs) personnalisés.

## Comment Démarrer
Pour essayer cette application localement :
1. Ouvrez ce dossier de projet dans Android Studio.
2. Laissez Gradle synchroniser les dépendances de l'application.
3. Sélectionnez un émulateur ou un appareil physique.
4. Appuyez sur le bouton "Run" (Exécuter) (`Shift + F10` / `./gradlew assembleDebug`).
