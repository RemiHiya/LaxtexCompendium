<h1 align="center">
  Bienvenue dans le giga résumé
</h1>
<h4 align="center">
  Proposé par Cyprien, adapté par Rémi
</h4>


  

# Commandes git

| **commande**                             |               **utilité**               |
|:-----------------------------------------|:---------------------------------------:|
| git add "fichier"                        | permet d’ajouter le fichier dans le git |
| git commit -m "message"                  | creer une version et ajouter un message |
| git status                               |      affiche l’état de la version       |
| git log                                  |      affiche la liste des versions      |
| git init                                 |  demande a git de suivre le repertoire  |
| git diff \[fichier\]                     |  affiche les modification d’un fichier  |
| rm -fr .git                              |            supprimer le git             |
| git config –global user.name/email       |    modifier le nom de l’utilisateur     |
| git commit –amend –reset-author –no-edit |      appliquer les modif ci dessus      |
| git push                                 |       envoyer l’update à git lab        |
| git pull                                 |      recevoir l’update de git lab       |
| git clone "url"                          |     clone le git lab sur notre git      |


# .gitignore typique pour Latex
```
*.toc
*.aux
*.log
*.pdf
*.gz
```

# Petit mémo pour les quotes
### Y'avait ca dans le doc de Cyprien alors pourquoi pas
|       **nom**       |   **anglais**   | **utf8** |   **code** LaTeX    | **rendu** |
|:-------------------:|:---------------:|:--------:|:-------------------:|:---------:|
| simples guillemets  | *simple quotes* |  ‘hey’   |   `` ` `` hey `'`   |   ‘hey’   |
| doubles guillemets  | *double quotes* |  “hey”   | ``` `` ``` hey `''` |   “hey”   |
| guillemets français | *french quotes* |  «hey»   |  ` \og` hey `\fg`   |  « hey »  |


