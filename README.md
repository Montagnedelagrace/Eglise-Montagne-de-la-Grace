# Église Montagne de la Grâce – Application de Gestion

Cette application permet de gérer :
- ✅ Les membres
- 💰 Les dons
- 🙏 Les requêtes de prière
- 📊 Un tableau de bord admin
- 🌙 Un mode sombre intégré
- 📄 Génération de PDF
- 📧 Envoi automatique d'emails (ex. EmailJS)

---

## ⚙️ Installation locale

1. Décompressez ce projet
2. Ouvrez un terminal :

```bash
cd montagne-de-la-grace-enhanced
npm install
```

3. Créez un fichier `.env` à la racine :

```
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key
```

4. Lancez le serveur de développement :
```bash
npm run dev
```

---

## 🚀 Build et Déploiement

### ➤ Créer le build :
```bash
npm run build
```

Cela génère un dossier `/dist`

### ➤ Déploiement sur [Netlify Drop](https://app.netlify.com/drop) :
1. Exécutez :
```bash
npm run build
```
2. Faites glisser le dossier `/dist` sur Netlify Drop
3. Ajoutez vos variables dans Site Settings > Environment

---

## ✨ Déploiement Vercel (optionnel)

```bash
npm install -g vercel
vercel
```

---

## 📂 Structure du projet

- `src/pages/Login.tsx` → Page de connexion
- `src/pages/AdminDashboard.tsx` → Tableau de bord
- `src/pages/Forms.tsx` → Formulaires membres/dons/prière
