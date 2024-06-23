# Documentation du tutoriel Github avec Git effectué Par Hassim Diallo

## Initialisation du dépôt
 
```bash
git init
git add ou git remote add  origin SSH_REPO
```

## Rédiger un commit (Bonne Pratiques)

```
Titre du commit 

Description de notre commit avec des informations sur l'évolution du projet

```
## Envoyer un commit sur le dépôt distant


```bash
 git add .
 git commit -m "Titre du commentaires "
 git push origin main

```
## Création d'une Branche

```bash
git checkout -b NOM_BRANCH

```
Pour les bonnes pratiques on va intégrer  la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer une pull request pour demander une revue de code 


