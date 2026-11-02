# Documentation de l'initialisation a GIT
# Git-practice1
## Initialiser un depot

´´´´Bash
git init
git remote add origin SSH_REPO

## Resolution de mon probleme de push
´´´´bash 
En effet je n'arrivais pas a push mes mise a jour
sur GitHub parceque j'avais renommer le nom du 
fichier contenant la cles SSH
´´´´

## Rediger un commit

´´´´
Titre du commit

Description de notre commit avec des informations
sur l'evolution du projet
´´´´

## Envoyer un commit sur le depot a distance

´´´´bash
git add .
git commit -m "Titre du commit"
git push origin master

´´´´

## Creation d'une branche

´´´´bash
git checkout -b NOM_BRANCHE

´´´´
