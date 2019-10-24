Partie de l'historique

git log pour consulter l'historique
git --no-pager log --oneline pour l'affichage des logs et sortir de la commande
git log fichier pour consulter uniquement les commits de ce fichier.
git log -p fichier pour visualiser les modifications au sein d'un fichier.
git log --stat fichier pour visualiser les statiques des modifications du fichier.

git blame fichier pour savoir qui a travailler dans ce fichier dans les cas ou il ya plusieurs utilisateurs.
git diff pour visualiser les modifications avant d'indexer un fichier.
pour visualiser les modifications precedentes on utilise la commande git dif HEAD~1(par exemple).  
git diff --cached affiche les differences entre le dernier commit et l'index.
git restore fichier pour remettre l'etat dans lequel se trouvait un fichier avant une modification.
git restore --staged permet d'ajouter le fichier dans l'index apres qu'on refait une modification.

git reset HEAD~1 annule le dernier commit et met tout dans le WD sans le perdre
git reset --soft HEAD~1 annule egalement le dernier commit mais cette fois-ci met tout dans la staging area sans perte.
git reset code de commit supprime les autres commandes
git checkout code de commit fichier permet de revenir avant la refonte
git check-ignore **/** retire le suivi de version de fichier demande.
git revert pour annuler un commit
git revert code de commit cree un commit revert d'annulation du dernier commit realiser.



