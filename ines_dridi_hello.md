Git
====
installation [voir le lien](https://www.atlassian.com/fr/git/tutorials/install-git)

mkdir nom_répertoir

cd nom_répertoir

git clonne http://......../username/le_réferentiel.git (copier l'adresse sur github)

cd referentiel

touch fichier.txt/md         (créer un fichier)

git status

git add ficher.txt/md

git commit -m "commentaire" fichier.txt/md

git log (voir les commits du plus recent au plus ancien)

git push origin nom_branch  (master ou ...)

Créer une branche
==================
git branch nom_branche

git branch (voir les branches exixtantes)

git checkout nom_branche (se positionner sur la branche volue)

Merger sur la branche principale
=================================
git checkout branche_principale (aller sur la branche principale)

git branch (verifier ou on est)

git branch nouv_branch (creer une nouvelle branche)

git merge nouv_branch

git push origin master  (on peut aussi merger sur la nouv_branche)

Dépot distant
==============
créer un dépot sur Github [le lien Github](https://github.com)

git remote add origin http://...............git

git remote >>> cela va afficher origin 

git push origin master

Récupération d'un projet
=========================
git remote add http://...........git

git pull origin master

pour inviter une autre personne pour travailler sur le projet on fait:
- sur le repertoir en question sur Github on va sur settings
- on marquer le nom de la ou les personnes dans la barre collaborators
- cliquer sur add collab 
