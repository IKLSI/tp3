**Nom :  Lecomte Arthur** <br>
**Groupe : D**     <br>	
**Année : 2023**

# Compte-rendu TP1 Introduction GIT

### Dans ce TP, nous allons apprendre à travailler avec git. <br><br>


## Notions importantes 

La commande `git status` permet de **voir** les fichiers à inclure dans le dépôt git.

La commande `git add <fichier>` permet de **sélectioner** le fichier (stage) que nous voulons suivre dans le dépôt git.

La commande `git commit -m "Ajoutez ici un petit commentaire pour décrire ce commit"` permet de **valider/enregistrer** les changements dans le dépôt git.

La commande `git log` nous permet de voir toutes les différentes versions enregistrés dans notre dépôt.

## Dans un dépôt GIT un fichier peut avoir 3 états différents :

**Modifié (modified)**: il a des modification locales, il faut sélectionner (stage) pour ensuite valider (commit) ses modifications.

**Sélectionné (staged)**: ses modification ont été sélectionnées (staged) pour être validées (commited).

**Validé (commited)**: il est synchrone avec le dépôt et ne requière pas de validation.

## Ces états correspondent à 3 zones dans un GIT :

**La copie de travail (directory)**, c’est le système de fichier local, zone où les fichiers sont modifiés.

**La zone de sélection (staging area)**.
Le dépôt où les modifications sont enregistrées sous **forme de validations (commits)**.

## Le passage entre ses 3 états se fait par 3 actions:

**Sélection** (stage) qui sélectionne les fichier pour la validation(commande : `git add`).

**Validation** (commit) qui crée le commit et l’envoie dans le dépôt (commande: `git commit`).

**Récupération** (checkout) qui récupère un snapshot depuis le dépôt vers la copie de travail (commande : `git checkout`).