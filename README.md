
## Fichiers Principaux

- **index.html** : Page d'accueil avec un formulaire pour entrer le nom et télécharger une image.
- **kdo/** : Dossier contenant les ressources (images, vidéos, etc.).
- **templates/** : Dossier contenant les modèles HTML pour les différentes pages de vœux.
- **wi.html** : Page de vœux principale avec des fonctionnalités de téléchargement d'image et d'exportation de la section.

## Fonctionnalités

- **Formulaire de Nom** : Permet aux utilisateurs d'entrer leur nom et de le soumettre pour générer une page de vœux personnalisée.
- **Téléchargement d'Image** : Les utilisateurs peuvent télécharger une image qui sera affichée sur la page de vœux.
- **Vidéo en Arrière-Plan** : Utilisation de vidéos en arrière-plan pour une expérience visuelle immersive.
- **Exportation de la Section** : Les utilisateurs peuvent exporter la section de la page de vœux en tant qu'image.

## Utilisation

1. **Cloner le dépôt** :
    ```sh
    git clone <URL_du_dépôt>
    ```

2. **Ouvrir le projet dans un serveur local** (par exemple, avec XAMPP) :
    - Placez le projet dans le dossier `htdocs` de XAMPP.
    - Démarrez Apache depuis le panneau de contrôle de XAMPP.

3. **Accéder à la page d'accueil** :
    - Ouvrez un navigateur et accédez à `http://localhost/Noel/index.html`.

4. **Entrer le nom et télécharger une image** :
    - Remplissez le formulaire avec votre nom et téléchargez une image.
    - Cliquez sur "Valider" pour générer la page de vœux personnalisée.

5. **Télécharger la section de la page** :
    - Cliquez sur le bouton "Exporter 💻" pour télécharger la section de la page de vœux en tant qu'image.

## Dépendances

- **dom-to-image** : Utilisé pour exporter la section de la page en tant qu'image.
    ```html
    <script src="https://cdnjs.cloudflare.com/ajax/libs/dom-to-image/2.6.0/dom-to-image.min.js"></script>
    ```

## Auteurs

- **CHAMINADE DONDAH ADJOLOU** - Créateur et développeur principal

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
