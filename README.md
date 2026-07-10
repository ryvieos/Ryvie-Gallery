# Ryvie Gallery

**English** · [Français](README.fr.md)

Centralized visual assets (icons and screenshots) for the [Ryvie](https://github.com/ryvieos/Ryvie) App Store, the self-hosted personal cloud OS. Part of the Ryvie ecosystem. Learn more at [ryvie.fr](https://ryvie.fr).

## 📌 Purpose

**Ryvie Gallery** stores the images and icons of every app available in the **Ryvie App Store**. These visual assets are used to display each app inside the store interface.

## 📁 Structure

Each app has its own folder:

```
application-name/
├── icon.png          # App icon (shown in the store)
├── image1.png        # Screenshot 1
├── image2.png        # Screenshot 2
└── image3.png        # Screenshot 3
```

## 📦 Available apps

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

## 🔗 Integration

The images are referenced by the Ryvie App Store to:

- Show each app's icon
- Display screenshots in the app details
- Build a complete visual experience for users

## 📝 Add a new app

1. Create a branch for the new app
   ```bash
   git checkout -b FEATURE/application-name
   ```

2. Create a new folder named after the app
   ```bash
   mkdir application-name
   ```

3. Add the icon and screenshots
   - `icon.png` (app icon)
   - `image1.png` (screenshot 1)
   - `image2.png` (screenshot 2)
   - `image3.png` (screenshot 3)
   - ...

4. Commit the changes
   ```bash
   git add application-name/
   git commit -m "feat: add application-name assets"
   ```

5. Open a Pull Request
   ```bash
   git push origin FEATURE/application-name
   ```
   Then open a Pull Request on the repository

---
