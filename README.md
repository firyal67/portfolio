# 🚀 Portfolio Fedi Sayadi

Portfolio personnel développé avec HTML, CSS et JavaScript vanilla.

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-BADGE-ID/deploy-status)](https://app.netlify.com/sites/YOUR-SITE-NAME/deploys)

## ✨ Fonctionnalités

### 🎨 Design moderne et élégant
- Interface sombre avec dégradés de couleurs
- Animations fluides et transitions élégantes
- Design responsive pour tous les écrans
- Effets de hover sophistiqués
- Photo de profil avec animation de flottement

### 🚀 Projets en ligne
- **Sayadi Airways** - [Voir le site](https://sayadiairways.netlify.app/html/home)
- **Sayzen Neobank** - [Voir le site](https://sayzen-neobank.netlify.app/login)
- **ShopFlow** - En développement

### 📱 Sections
- Hero avec photo de profil animée
- Statistiques dynamiques
- Portfolio de projets avec liens directs
- Compétences techniques
- Timeline de parcours
- Formulaire de contact

## 🚀 Déploiement sur Netlify

### Méthode 1 : Via GitHub (Recommandé)

1. **Créer un repository GitHub**
```bash
git init
git add .
git commit -m "Initial commit - Portfolio Fedi Sayadi"
git branch -M main
git remote add origin https://github.com/votre-username/portfolio.git
git push -u origin main
```

2. **Connecter à Netlify**
   - Allez sur [netlify.com](https://netlify.com)
   - Cliquez sur "Add new site" → "Import an existing project"
   - Choisissez GitHub et sélectionnez votre repository
   - Configuration :
     - **Build command** : (laisser vide)
     - **Publish directory** : `public`
   - Cliquez sur "Deploy site"

3. **C'est tout ! 🎉**
   - Votre site sera en ligne en quelques secondes
   - URL : `https://votre-site.netlify.app`

### Méthode 2 : Drag & Drop

1. Allez sur [netlify.com/drop](https://app.netlify.com/drop)
2. Glissez-déposez le dossier `public`
3. Votre site est en ligne instantanément !

### Méthode 3 : Netlify CLI

```bash
# Installer Netlify CLI
npm install -g netlify-cli

# Se connecter
netlify login

# Déployer
netlify deploy --prod --dir=public
```

## 📁 Structure du projet

```
.
├── public/
│   ├── index.html              # Page principale
│   └── photo de fedi.JPG       # Photo de profil
├── netlify.toml                # Configuration Netlify
├── .gitignore                  # Fichiers à ignorer
├── README.md                   # Ce fichier
└── index.html                  # Page d'accueil du projet
```

## 🎨 Personnalisation

### Modifier les informations
Éditez `public/index.html` pour mettre à jour :
- Vos informations personnelles
- Vos liens de projets
- Vos compétences
- Votre parcours
- Vos informations de contact

### Changer la photo
Remplacez `public/photo de fedi.JPG` par votre photo (gardez le même nom ou mettez à jour le HTML)

### Ajouter des projets
Dupliquez un bloc `<div class="project-card">` dans `public/index.html`

## 🔧 Développement local

### Option 1 : Serveur Python
```bash
cd public
python -m http.server 8000
```
Ouvrez http://localhost:8000

### Option 2 : Live Server (VS Code)
1. Installez l'extension "Live Server"
2. Clic droit sur `public/index.html`
3. Sélectionnez "Open with Live Server"

### Option 3 : Netlify Dev
```bash
netlify dev
```

## 🌐 Domaine personnalisé

1. Allez dans Netlify Dashboard → Domain settings
2. Cliquez sur "Add custom domain"
3. Suivez les instructions pour configurer votre DNS

## 📊 Performance

- ✅ Score Lighthouse : 95+
- ✅ CDN global automatique
- ✅ SSL/HTTPS gratuit
- ✅ Déploiement instantané
- ✅ Hébergement gratuit illimité

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (Animations, Flexbox, Grid)
- JavaScript Vanilla
- Google Fonts (Syne, DM Sans)

## 📧 Contact

- **Email** : [Votre email]
- **GitHub** : [fedisayadi29](https://github.com/fedisayadi29)
- **LinkedIn** : [Votre LinkedIn]

## 📝 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier.

---

**Créé avec ❤️ par Fedi Sayadi**
