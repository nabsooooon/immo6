## Cursor Cloud specific instructions

Ce dépôt est un site statique HTML pur (une seule page `index.html` + un fichier `CNAME` pour GitHub Pages).

- **Aucune dépendance** à installer (pas de `package.json`, pas de build, pas de framework).
- **Pour servir le site localement** : `python3 -m http.server 8080` depuis la racine du dépôt, puis ouvrir `http://localhost:8080`.
- **Pas de linter, tests automatisés, ni étape de build** — la validation se fait visuellement dans le navigateur.
- Le fichier `CNAME` contient `immo6.com` pour le déploiement GitHub Pages.
