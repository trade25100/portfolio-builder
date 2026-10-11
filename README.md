# Portfolio Builder — GitHub Pages

Ouvrir `index.html` dans un navigateur, compléter les champs, ajouter des projets (titre, lien, image URL ou image depuis le PC), puis cliquer sur **Exporter HTML public**.

Le fichier `index.html` téléchargé est une **page publique statique**, sans formulaire d'édition. Les styles sont inclus, et les images importées depuis le PC sont intégrées dans le HTML exporté en base64. Les images distantes nécessitent une connexion et un hébergeur qui autorise leur affichage.

## Publication GitHub Pages

1. Créer un dépôt GitHub.
2. Déposer le **fichier `index.html` exporté** (pas l'éditeur) à la racine du dépôt.
3. Aller dans **Settings → Pages → Deploy from a branch → main → /(root)**.
4. Après chaque modification, exporter de nouveau et remplacer le fichier public.

## Sauvegarde

L'éditeur stocke les données dans le `localStorage` du navigateur. Utiliser **Exporter JSON** pour sauvegarder les projets et **Importer JSON** pour les récupérer sur un autre appareil. L'import remplace les données existantes.

**Attention :** ne pas ajouter de notes privées, mots de passe ou données sensibles dans les liens ou descriptions destinés au public. Les images importées doivent faire moins de 1,5 Mo et peuvent rendre le HTML volumineux.
