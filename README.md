# Site Velia

Site web de l'agence Velia - Développement sur-mesure Web & Mobile

## 🚀 Déploiement sur GitHub Pages

### Étapes pour mettre en ligne :

1. **Créer un nouveau dépôt sur GitHub**
   - Allez sur [github.com](https://github.com)
   - Cliquez sur "New repository"
   - Nommez-le (ex: `velia-website` ou `velia-site`)
   - Ne cochez PAS "Initialize with README" (on a déjà un commit)
   - Cliquez sur "Create repository"

2. **Connecter votre dépôt local à GitHub**
   ```bash
   git remote add origin https://github.com/VOTRE-USERNAME/NOM-DU-REPO.git
   git branch -M main
   git push -u origin main
   ```
   (Remplacez `VOTRE-USERNAME` et `NOM-DU-REPO` par vos valeurs)

3. **Activer GitHub Pages**
   - Allez dans les **Settings** de votre dépôt GitHub
   - Dans le menu de gauche, cliquez sur **Pages**
   - Sous **Source**, sélectionnez **Deploy from a branch**
   - Choisissez la branche **main** et le dossier **/ (root)**
   - Cliquez sur **Save**

4. **Votre site sera accessible à :**
   ```
   https://VOTRE-USERNAME.github.io/NOM-DU-REPO/
   ```

## 📝 Notes

- Le fichier `index.html` est la page principale (requis pour GitHub Pages)
- Les ressources (CSS, images) sont chargées depuis les CDN Webflow
- Le site sera mis à jour automatiquement à chaque `git push`

## 🔄 Mettre à jour le site

Après avoir modifié `index.html` :
```bash
git add index.html
git commit -m "Mise à jour du site"
git push
```
