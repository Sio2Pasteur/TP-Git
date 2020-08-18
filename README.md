﻿Git par la pratique
===================

* Mettez vous par trois,
* Créez un compte sur GitHub,
* Dupliquez (*fork*) le projet TP-Git dans votre espace public,
* Récupérez sur votre disque dur les sources du projet,

        git clone git@github.com:votrecompte/TP-Git.git

* Indiquez le dépôt officiel :

        cd TP-Git
        git remote add official git@github.com:Sio2Pasteur/TP-Git.git 

* Sur votre disque dur, ajoutez à la fin de ce fichier le prénom et le nom d'un des membres du binôme. La ligne doit commencer par une étoile. Corrigez la liste pour que la dernière ligne se termine par un point et les autres par des virgules,
* Faites une révision :

        git add README.md
        git commit

* Publiez-la dans votre espace public:

        git push

* Dans GitHub faites une demande d'intégration (*pull request*),
* Ajoutez le prénom et le nom de l'autre membre du binôme selon les mêmes règles que tout à l'heure,
* Faites une révision :

        git add README.md
        git commit

* Mettez à jour votre disque dur jusqu'à ce que vous récupériez les modifications de quelqu'un d'autre,

        git pull official master

* Réglez le conflit, modifiez la mise en page de la liste pour qu'elle soit correcte,
* Une fois que le conflit est réglé par une révision, publiez l'ensemble des révisions dans votre espace public :

        git push

* Dans GitHub faites une demande d'intégration (pull request),

Liste des étudiants ayant réussi ce TP
--------------------------------------

* Axel GRANGER.
