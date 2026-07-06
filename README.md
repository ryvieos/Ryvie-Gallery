# Ryvie Gallery

Repository centralisé des assets visuels pour le Ryvie App Store.

## 📌 Objectif

**Ryvie Gallery** est un repository de stockage des images et icônes de toutes les applications disponibles dans le **Ryvie App Store**. Ces ressources visuelles sont utilisées pour afficher chaque application dans l'interface du store.

## 📁 Structure

Chaque application possède un dossier contenant :

```
application-name/
├── icon.png          # Icône de l'application (affichée dans le store)
├── image1.png        # Capture d'écran 1
├── image2.png        # Capture d'écran 2
└── image3.png        # Capture d'écran 3
```

## 📦 Applications Disponibles

- Affine
- Docuseal
- Fossflow
- Home Assistant
- Jellyfin
- Linkwarden
- Mealie
- Memos
- N8N
- Open-Notebook
- OpenClaw
- Rdrive
- Rdrop
- Rpictures
- Rtransfer
- Vaultwarden

## 🔗 Intégration

Les images sont référencées par le Ryvie App Store pour :
- Afficher l'icône de chaque application
- Montrer les captures d'écran dans les détails de l'app
- Créer une expérience visuelle complète pour les utilisateurs

## 📝 Ajouter une Nouvelle Application

1. Créer une branche pour la nouvelle application
   ```bash
   git checkout -b FEATURE/application-name
   ```

2. Créer un nouveau dossier avec le nom de l'application
   ```bash
   mkdir application-name
   ```

3. Ajouter l'icône et les captures d'écran
   - `icon.png` (icône de l'application)
   - `image1.png` (capture d'écran 1)
   - `image2.png` (capture d'écran 2)
   - `image3.png` (capture d'écran 3)
   - ...

4. Commiter les changements
   ```bash
   git add application-name/
   git commit -m "feat: add application-name assets"
   ```

5. Créer une Pull Request
   ```bash
   git push origin FEATURE/application-name
   ```
   Puis ouvrir une Pull Request sur le repository

---
