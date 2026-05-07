# Fiche d'Entrée Ouvrier Chantier

Application web bilingue (Français / Arabe) pour la gestion des fiches d'entrée des ouvriers de chantier.

## Fonctionnalités
- Formulaire complet : Identité, CNSS, Chantier, Poste, Salaire, Sécurité, Signatures
- Signatures digitales (canvas) — souris, stylet, doigt
- Impression / export PDF sur une seule page A4
- Validation des champs obligatoires
- Numéro de fiche et date auto-générés
- Compatible : iOS Safari, Android Chrome, desktop

## Compatibilité
| Plateforme | Support |
|---|---|
| iOS Safari (iPhone / iPad) | ✅ |
| Android Chrome (mobile / tablette) | ✅ |
| Desktop Chrome / Firefox / Edge | ✅ |
| Impression A4 une page | ✅ |

---

## Déploiement GitHub Pages

```bash
# 1. Créer un repo GitHub (ex: fiche-chantier)
# 2. Pousser le code
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/VOTRE_USER/fiche-chantier.git
git push -u origin main

# 3. Dans GitHub → Settings → Pages → Source: main / root
# URL : https://VOTRE_USER.github.io/fiche-chantier/
```

---

## Déploiement Railway

```bash
# 1. Installer Railway CLI
npm install -g @railway/cli

# 2. Se connecter
railway login

# 3. Créer le projet et déployer
railway init
railway up

# Ou via l'interface : railway.app → New Project → Deploy from GitHub repo
```

### Variables d'environnement Railway
Aucune variable requise. Le port est détecté automatiquement via `process.env.PORT`.

---

## Lancer en local

```bash
npm install
npm start
# → http://localhost:3000
```
