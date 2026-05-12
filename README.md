# GraceTone — Jazz Music Production

Site officiel du label GraceTone.

## Structure du projet

```
gracetone/
├── public/
│   └── index.html        # Site complet (HTML + CSS + JS)
├── server.js             # Serveur Express
├── package.json
└── .gitignore
```

## Déploiement sur Render via GitHub

### Étape 1 — Mettre sur GitHub
```bash
git init
git add .
git commit -m "Initial commit — GraceTone website"
git remote add origin https://github.com/TON_USERNAME/gracetone.git
git push -u origin main
```

### Étape 2 — Déployer sur Render
1. Aller sur https://render.com → "New Web Service"
2. Connecter votre repo GitHub
3. Configurer :
   - **Build Command** : `npm install`
   - **Start Command** : `npm start`
   - **Environment** : Node
4. Cliquer "Create Web Service"

Votre site sera en ligne sur `https://gracetone.onrender.com` 🎷
