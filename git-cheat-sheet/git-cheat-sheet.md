# Cheat-Sheet Git

## Commandes de base

- `git init` : Initialise un nouveau dépôt Git dans le répertoire actuel.
- `git clone <url>` : Clone un dépôt distant existant sur votre machine locale.
- `git add <fichier>` : Ajoute un fichier à l'index pour le suivi des modifications.
- `git commit -m "<message>"` : Crée un nouveau commit avec les modifications de l'index.
- `git status` : Affiche l'état actuel du dépôt, les fichiers modifiés, ajoutés ou supprimés.
- `git log` : Affiche l'historique des commits.
- `git push` : Envoie les modifications locales vers le dépôt distant.
- `git pull` : Récupère les dernières modifications depuis le dépôt distant et les fusionne avec votre branche locale.
- `git branch` : Affiche la liste des branches et met en évidence la branche courante.
- `git checkout <branche>` : Bascule vers une autre branche existante.
- `git merge <branche>` : Fusionne une autre branche dans votre branche courante.
- `git diff` : Affiche les différences entre l'état actuel et le dernier commit.

## Gestion des branches

- `git branch` : Affiche la liste des branches locales.
- `git branch <nom_branche>` : Crée une nouvelle branche.
- `git branch -d <nom_branche>` : Supprime une branche.
- `git checkout <nom_branche>` : Bascule vers une branche existante.
- `git merge <nom_branche>` : Fusionne une branche dans votre branche courante.

## Gestion des remotes

- `git remote add <nom_remote> <url_remote>` : Ajoute un dépôt distant.
- `git remote -v` : Affiche la liste des dépôts distants.
- `git remote remove <nom_remote>` : Supprime un dépôt distant.

## Manipulation des commits

- `git log` : Affiche l'historique des commits.
- `git revert <commit>` : Crée un nouveau commit qui annule les modifications d'un commit spécifié.
- `git reset <commit>` : Défait les commits après le commit spécifié tout en conservant les modifications.
- `git cherry-pick <commit>` : Applique les modifications d'un commit spécifié sur la branche courante.

## Manipulation des fichiers

- `git rm <fichier>` : Supprime un fichier de l'index et de l'arborescence de travail.
- `git mv <ancien_nom> <nouveau_nom>` : Renomme un fichier et met à jour l'index.
