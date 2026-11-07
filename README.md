# Learning Forking on Team Project

## Invitation vers le repo du projet
Dans l'interface de votre repository GitHub, Il faut aller vers (`Settings` -> `Collaborators` -> `Add people` -> tap `Username Collabs` -> Add `Username`). Maintenant, votre collaborateur pourra accepter l'invitation et cloner votre projet.

## Configuration et Clonage du projet
Pour le clonage, on a l'option `https` et `ssh`
```bash
# https
git clone ['Lien https']
# ssh
git clone ['Lien ssh']
```
Pour la configuration, on a l'option `local` et `global`
```bash
# Global
git config --global user.name "Votre nom d'utilisateur"
git config --global user.email "Votre adresse email"
# Local dans le repertoire de votre projet
git config --local user.name "Votre nom d'utilisateur"
git config --local user.email "Votre adresse email"
```
Puis on change de repertoire avec `cd ['Nom du dossier']`.

## Ajout, commit et push des mises a jour
```bash
# Avant tout il faut au moins apporter quelques modifications de l'etat actuel du depot
# comme ecrire sur le fichier README.md.
git add .
git branch -M main
git commit -m "Mettre un Commentaire"
git remote add origin ['Lien https ou ssh']
git push origin main
```