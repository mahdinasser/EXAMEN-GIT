Partie de branches.

git branch pour voir l'ensemble des branches existantes.
git branch dev permet de creer la branche dev par exemple.

git checkout master permet d'entrer dans la branche master par exemple.
git merge dev permet de merger dev avec master en tenant compte du "git checkout master.
git merge dev(branche par exemple) --no-ff fait un commit de merge meme si on est dans une situation sans divergence de branche.

gti branch -d master permet de supprimer la branche master par exemple.
git branch -D master permet de forcer la supppression de la branche master par exemple.

git stash permet de quitter la branche en cours et d'y revenir plus tard en recuperant le code remiser pour continuer votre feature.
git stash apply pour recuperer ce qu'on a dans la remise(stash).
git stash list permet de lister les remises
git statsh drop supprime ce qui se trouve dans la stash.
