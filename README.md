<h1 align="center">
  Bienvenue dans le giga résumé
</h1>
<h4 align="center">
  Proposé par Cyprien, adapté par Rémi
</h4>


<br>

*Le document complet proposé par Cyprien est disponible en prévisualisation [ici](https://github.com/RemiHiya/LaxtexCompendium/blob/main/latexresume.tex).*
  

# Commandes git

| **commande**                             |               **utilité**               |
|:-----------------------------------------|:---------------------------------------:|
| git init                                 |  Crée un nouveau répertoire git         |
| git add "fichier"                        | Ajoute le fichier au suivi de git       |
| git commit -m "message"                  | Crée une nouvelle version avec un message |
| git status                               |      Affiche le statut du répo          |
| git log                                  |      affiche la liste des versions      |
| git diff \[fichier\]                     |  affiche les modification d’un fichier  |
| rm -fr .git                              |            supprimer le git             |
| git config –global user.name/email       |    modifier le nom de l’utilisateur     |
| git commit –amend –reset-author –no-edit |      appliquer les modif ci dessus      |
| git push                                 |       envoyer l’update à git lab        |
| git pull                                 |      recevoir l’update de git lab       |
| git clone "url"                          |  clone le repo dans le dossier courant  |


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


