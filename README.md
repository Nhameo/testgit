

# testgit


Cette doc s'ameliore sans arrêt !


Apprentissage des commandes git

## clonnage

Pour copier un nouveau projet sur mon disque local la commande est :

  git clone git@github.com:Nhameo/testgit.git

Regarder le status

  git status

Ajouter un fichier pour le prochain commit

  git add <nom du fichier>

Astuce : toujours regarder le statut avant d'ajouter des fichiers

Sauvegarder en local

  git commit ou git commit -m ""

Pusher sur Github

  git push origin master

## Les branches

Fabriquer une nouvelle branche

    git branche <nom>

Aller dans une branche

    git checkout <nom de la branche>

Verifier la branche courante

    git status

Pusher sur une branche

    git push origin <nom de la branche>


## DRAFT

    Ceci est un paragraphe realisé dans la branche Draft que je souhaite voir un jour dans ma branche master.

    Je continue à travailler dans draft c'est rigolo c'est le pied et c'est pas en master!
