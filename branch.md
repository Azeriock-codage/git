Pour créer une branch il suffit d'utiliser la commande : git branch

Le Head est un pointeur spécial car il permet d'indiquer au Git dans quelle branche on se situe

Pour passer d'une branche à l'autre on utilise la commande git checkout

git checkout -b feature_header permet de déplacer le header sur une branche

git branch -d permet de supprimer une branch et git branch -D permet de forcer la supression d'une Branch

La commande git merge permet de mélanger plusieurs branch ensemble par exemple si je suis dans la branch master et que je fais un git merge dev, on mélange dev dans master

le git merge dev --no-ff permet de faire un commit de merge même si on est dans une situation sans divergence de branche.

git branch --no-merged permet de lister toutes les branches non mergées.

git stash permet de remiser le code non terminé.

git tag -a v1.0 -m " version 1 de l'application" permet de faire un tag annoté

git tag v1 permet de faire un tag léger mais est moins utilisé

git tag -a v1.0.1 -m "version 1.0.1" 9fceb2permet d'étiquetter après coup sur un commit donné.

git show permet de voir un tag annoté

git --bare init permet de commencer à créer un serveur git

git remote sert à lister les dépots distants

git remote -v permet de lister en mode verbeux

git remote add [alias] [chemin_du_serveur_distant] permet d'ajouter un serveur distant

git remote rm alias / git remote rename alias news_alias permet de renommer un dépôt distant où  de le supprimer

git fetch origin permet de récupérer la branche distante localement sans fusion avec sa branche branche master.

 git log master..origin/master permet de comparer les différences entre master local et disant.

 Le git pull est un équivalent à un git fetch + git merge

 git push [nom-distant] [nom-de-branche] permet de publier le git sur un serveur distant

 git remote show origin permet d'inspecter un dépôt distant.