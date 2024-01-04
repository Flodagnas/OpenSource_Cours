# Introduction à Git

Git est un système de gestion de versions distribué qui permet de suivre les modifications du code source d'un projet au fil du temps. Il facilite la collaboration entre les développeurs en permettant le suivi des changements, la fusion de branches et la gestion des versions.

## Installation de Git

Avant d'utiliser Git, assurez-vous de l'avoir installé sur votre machine. Vous pouvez le télécharger à partir du [site officiel de Git](https://git-scm.com/).

## Configuration initiale

Une fois Git installé, configurez votre nom d'utilisateur et votre adresse e-mail, qui seront associés à vos contributions. Utilisez les commandes suivantes dans votre terminal :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre@email.com"
```

## Cycle de vie des fichiers dans Git

Les fichiers dans un référentiel Git passent par trois états principaux :

- **Working Directory (Répertoire de travail)** : C'est l'endroit où vous modifiez les fichiers de votre projet.
- **Staging Area (Zone de transit)** : Les fichiers modifiés sont ajoutés à la zone de transit en utilisant la commande **git add**.
- **Repository (Référentiel)** : Les fichiers confirmés et ajoutés à la zone de transit sont enregistrés dans le référentiel avec la commande **git commit**.

## Commandes Git courantes

- **git status** : Affiche l'état des fichiers dans votre répertoire de travail et dans la zone de transit.
- **git add <fichier>** : Ajoute un fichier spécifique à la zone de transit.
- **git add** . : Ajoute tous les fichiers modifiés à la zone de transit.
- **git commit -m "Message de commit"** : Enregistre les modifications dans le référentiel avec un message descriptif.
- **git log** : Affiche l'historique des commits.

## Branches

Les branches permettent de travailler sur des fonctionnalités isolées du reste du code. Les commandes principales sont :

- **git branch** : Affiche la liste des branches et met en évidence la branche actuelle.
- **git branch <nom_branche>** : Crée une nouvelle branche.
- **git checkout <nom_branche>** : Basculer vers une branche existante.
- **git merge <nom_branche>** : Fusionne une branche dans la branche actuelle.

## Remontée et téléchargement des modifications

- **git push** : Envoie les modifications locales vers un référentiel distant.
- **git pull** : Récupère les modifications du référentiel distant et les fusionne dans la branche actuelle.

## Conclusion

Git est un outil puissant qui facilite le suivi des modifications, la collaboration entre développeurs et la gestion des versions d'un projet. En comprenant les concepts de base et en utilisant les commandes appropriées, vous pouvez tirer parti de Git pour gérer efficacement votre code source.

```rust
Vous pouvez copier-coller ce contenu dans un fichier avec l'extension `.md` pour l'afficher correctement en Markdown.
```