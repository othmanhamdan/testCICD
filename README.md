# CI-CD-Workshop

## ÉTAPE 1: Création du Repository
- Aller sur github.com
- Cliquer "New repository"
- Donner un nom
- ✅ Public
- ✅ Add README
- Create repository

## ÉTAPE 2: Activer GitHub Pages
- Allez dans Settings → Pages
- Dans Source choisissez "GitHub Actions" 

## ÉTAPE 3: Ajouter index.html
- Selectionnez Add file → Upload files (choisissez le fichier index.html)

## ÉTAPE 4: Créer le Workflow
- Selectionnez Add file → Create new file
- Donner le nom: `.github/workflows/deploy.yml`
- Copier le contenu du workflow fourni
- Commit

## ÉTAPE 5: Observer l'Exécution
- Onglet "Actions"
- Voir les 3 jobs: Build → Test → Deploy

## ÉTAPE 6: Tester une Modification
- Éditer index.html
- Changer le titre
- Commit
- Actions → nouveau workflow démarre
- Refresh le site → titre changé!
