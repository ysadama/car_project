# Projet

On retrouve ici tous les codes et fichiers de notre projet.

## Commandes Git courantes

### Initialisation d'un dépôt
```bash
git init
```

### Cloner un dépôt
```bash
git clone <url-du-dépôt>
```

### Vérifier l'état du dépôt
```bash
git status
```

### Ajouter des fichiers au suivi
```bash
git add <nom-du-fichier>  # pour ajouter un fichier spécifique
git add .                 # pour ajouter plusieurs fichiers
```

### Valider les modifications (faire un commit)
```bash
git commit -m "Message de validation"
```

### afficher l'historique des commits
```bash
git log
```

### Pousser les modifications vers le dépôt
```bash
git push origin <branche>
```

### Récupérer les modifications du dépôt
```bash
git pull origin <branche>
```

### Créer une nouvelle branche
```bash
git branch <nom-de-la-branche>
```

### Changer de branche
```bash
git checkout <nom-de-la-branche>
```

### Fusionner une branche
```bash
git merge <nom-de-la-branche>
```

### Supprimer une branche
```bash
git branch -d <nom-de-la-branche>
```

### Annuler des modifications
```bash
git checkout -- <nom-du-fichier>
```

### Réinitialiser un commit
```bash
git reset --hard <hash-du-commit>
```

### Afficher les différences
```bash
git diff
```

### Configurer Git
```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```