# Demo 02 - Utilisation collaborative

## Repository distant
- [Github](https://github.com/)
- [GitLab](https://gitlab.com/)
- [Codeberg](https://codeberg.org/)
- [Azure Repo](https://azure.microsoft.com/en-us/products/devops/repos/)
- [Bitbucket](https://www.atlassian.com/fr/software/bitbucket)

## Commande entre git local et distant
### Lien avec un repo distant
```
# Ajouter
git remote add <remote-name> <url-repo>  

# Supprimer
git remote remove <remote-name>

# Exemple
git remote add origin https://github.com/FormCours/TI_2026__ConsultantBI__Demo_Git_02.git
```

### Récuperation d'un projet
```
# Cloner un repo
git clone <url-repo>

# Cloner un repo en renommant le dossier
git clone <url-repo> <dir-name>
```

### Synchronisation entre local et distant 
```
# Récuperer les commits sans les appliquer
git fetch

# Récuperer les commits en les appliquant
git pull

# Envoyer les commits
git push
```