git --no--pager log -3 --online = permet de voir les logs et de sortir de la console.

git --no-page log -nombre --oneline = permet de voir le nombre commit que l'on choisit et de sortir ensuite de la console.

git log --author permet de voir les logs d'un auteur en particulier

le git log since et before permette de regarder les logs d'un jours précis

le git log nom_du_dossier permet de regarder l'historique d'un dossier

git log -p lui s'applique à l'ensemble des commits.

git log --stat permet de voir les statistiques par rapport au modification faites au projet.

git log -E -i --grep = permet de rechercher des logs précis E pour parler des occurences et i pour insensible à la case.

git diff = permet de visualiser la modification d'un fichier avant de l'indexé

le Head-1 permet de remonter d'un commit en arrière

Le git restore quant à lui permet de restaurer le fichier dans l'état dans le quel il était avant modification.

le git reset HEAD-1 Permet d'annuler le dernier commit et met tout dans le WD sans perte

git reset --soft HEAD-1 fait à peu près la même chose sauf qu'il met tout dans la staging area sans perte

git reset --hard HEAD~1 Permet d'annuler le dernier commit et il supprime toute les modifications appliqué

 git checkout permet de retourner à l'état initial d'un fichier

 La commande git revert permet de crée un commit revert d'annulation du dernier du dernier commit réalisé.
