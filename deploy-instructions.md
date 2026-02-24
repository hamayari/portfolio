# 🚀 Déployer ton Portfolio sur GitHub Pages

## Étape 1 : Préparer Git

Ouvre le terminal dans le dossier `portfolio-responsive-complete` et exécute :

```bash
git init
git add .
git commit -m "Initial portfolio commit"
```

## Étape 2 : Créer le Repo GitHub

1. Va sur https://github.com/new
2. Nom du repo : `hamayari.github.io` (IMPORTANT !)
3. Description : "My Professional Portfolio"
4. Public
5. Ne coche RIEN d'autre
6. Clique "Create repository"

## Étape 3 : Pousser le Code

```bash
git remote add origin https://github.com/hamayari/hamayari.github.io.git
git branch -M main
git push -u origin main
```

## Étape 4 : Activer GitHub Pages

1. Va dans ton repo sur GitHub
2. Clique sur "Settings" (en haut)
3. Dans le menu gauche, clique "Pages"
4. Source : "Deploy from a branch"
5. Branch : Sélectionne "main" et "/root"
6. Clique "Save"

## Étape 5 : Attendre

Attends 2-3 minutes, puis va sur :
👉 https://hamayari.github.io

🎉 Ton portfolio est en ligne !

---

## 🔄 Mettre à Jour ton Portfolio

Quand tu modifies ton portfolio :

```bash
git add .
git commit -m "Update portfolio"
git push
```

Attends 1-2 minutes et les changements seront en ligne !

---

## 🌐 Domaine Personnalisé (Optionnel)

Si tu veux un domaine comme `mohamedamine.dev` :

1. Achète un domaine sur Namecheap (~10€/an)
2. Dans GitHub Pages Settings, ajoute ton domaine
3. Configure les DNS chez Namecheap

---

## ❓ Problèmes Courants

### Le site ne s'affiche pas
- Attends 5 minutes
- Vérifie que le repo s'appelle bien `hamayari.github.io`
- Vérifie que GitHub Pages est activé

### Les images ne s'affichent pas
- Vérifie les chemins : `assets/img/perfil.jpg`
- Les chemins sont sensibles à la casse (majuscules/minuscules)

### Erreur 404
- Le repo doit être PUBLIC
- Le nom doit être exactement `hamayari.github.io`

---

## 📧 Besoin d'Aide ?

Si tu as des problèmes, vérifie :
1. Le nom du repo est correct
2. Le repo est public
3. GitHub Pages est activé dans Settings
4. Tu as attendu 5 minutes

Bonne chance ! 🚀
