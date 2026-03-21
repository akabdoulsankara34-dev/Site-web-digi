# DIGITALE SOLUTION – Site Web

Site de présentation des services digitaux de **DIGITALE SOLUTION**, basé à Karpala, Ouagadougou, Burkina Faso.

---

## 🚀 Déploiement sur Vercel

### Méthode 1 — Vercel CLI (recommandée)

```bash
# 1. Installer Vercel CLI
npm install -g vercel

# 2. Se connecter à votre compte Vercel
vercel login

# 3. Déployer (depuis ce dossier)
vercel

# 4. Pour la production
vercel --prod
```

### Méthode 2 — Via GitHub (sans terminal)

1. Créez un compte sur [vercel.com](https://vercel.com)
2. Créez un dépôt GitHub et uploadez tous ces fichiers
3. Sur Vercel → **"Add New Project"** → Importez votre dépôt GitHub
4. Cliquez **"Deploy"** — votre site sera en ligne en moins d'1 minute !

### Méthode 3 — Drag & Drop (le plus simple)

1. Allez sur [vercel.com/new](https://vercel.com/new)
2. Cliquez **"Deploy without Git"**
3. **Glissez-déposez** ce dossier entier dans la zone
4. Votre site est en ligne ! 🎉

---

## 📁 Structure du projet

```
digitale-solution/
├── index.html      ← Site complet (single-file)
├── vercel.json     ← Configuration Vercel
├── package.json    ← Métadonnées du projet
├── .gitignore      ← Fichiers à ignorer
└── README.md       ← Ce fichier
```

---

## ✏️ Personnalisation

Tout le site est dans `index.html`. Pour modifier :

| Élément | Où chercher dans le fichier |
|---|---|
| Numéros WhatsApp | Rechercher `22676127809` |
| Localisation | Rechercher `Karpala` |
| Couleur principale | CSS variable `--green: #00e676` |
| Textes Hero | Section `<!-- HERO -->` |
| Services | Section `<!-- SERVICES -->` |
| Tarifs | Section `<!-- PRICING -->` |
| FAQ | Tableau `FAQS` dans le JS |
| Témoignages | Tableau `TST` dans le JS |

---

## 📞 Contact

- WhatsApp : +226 76 12 78 09
- WhatsApp : +226 78 54 83 17
- WhatsApp : +226 71 68 22 39
- Localisation : Karpala, Ouagadougou, Burkina Faso 🇧🇫
