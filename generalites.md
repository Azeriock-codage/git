git commit = La commande git commit sert à enregistrer dans le dépôt les modifications apportées

 git config --global user.name 
 git config --global user.email ==> Deux commandes qui permette de rentrer notre mail et notre identifiant Git

 git config --local user.name 
 git config --local user-email == > Les deux commandes sont à utiliser quand on veut ce focus sur un dépot en particulier 

 Le git init permet d'initialiser le début de l'invité de commande git

le git Status permet de vérifier que tout soit en état de marche dans notre fichier versionné.

Le git add permet de rentrer un dossier dans notre dépot.

git rm --cached permet lui de desindexé un menu

git log lui permet d'avoir un appercu des modifications sur chaque commit.

git add . pour ajouter l'ensemble des fichiers au dépot.

git add - A pour selectionner plus précisément.

git log master. .origin / master pour voir la différence entre deux branches

git log -nombre pour voir le nombre de commit qu'on a choisi

git log -p -nombre log avec différence pourr chaque commit sur le npùbre défini 

git log --stat pour voir les stars sur les modifs des commits

le suite de commande git blame elle permet de savoir qui a fait une modif avec une commande telle que :
git blame -L 40,60 readme.md pour voir qui a fait les modif sur ces lignes.

git mv nom_du_premier_ficher rename_du_ficher pour modifier le nom d'un fichier et qu'il soit pris en compte par Git.

Le git rm quant à lui permet de supprimer un  ficher.

git rm --cached permet de ne plus suivre un fichier

le gitignore quant à lui est un dossier à crée à la racine du dossier qui permet d'ignorer certains fichier dans ses dossiers il suffit d'écrire sa racine, son nom où son .
 Exemple: si j'écris vendor dans mon dossier gitignore, tout les fichiers vendors seront supprimés.
git config --local user.name 
git config --local user.email ==> Dans la situation présente cette commande nous permet de changer le pseudo qui était déjà présent.
