# TD7A4

Pour ouvrir l'application, tout d'abord il vous est nécessaire de clone le projet en local à l'aide de git clone <URL_dépôt> ensuite il suffit d'ouvrir le terminal du dossier comportant le Dockerfile et le docker-compose.yaml. Ce dernier va lui même créer les images utiles et mappe le port 5000 du conteneur au port 5000 de la machine hôte. Il va ensuite créer le network pour relier les deux conteneurs, créer un bind mount pour que notre conteneur de l'application python puisse récupérer les données de notre fichier "file.txt" en local et enfin créer un volume pour rendre les données de notre database persistants.
On utilise la commande docker-compose up -d pour run l'application puis cela créera, on peut le voir sur Docker desktop, 2 conteneurs : 1 pour la base de données et 1 pour l'application. On se rend ensuite sur http://localhost:5000/ et on peut bien voir ma base de données + le contenu de mon file.txt. 



                                              ________________________________________________________________


On peut suivre les changements grâce à Github, en accédant au dépôt GitHub que vous souhaitez suivre. Assurez-vous que vous êtes connecté à votre compte GitHub.

Cliquez sur le bouton "Watch" en haut à droite de la page du dépôt. Si vous souhaitez être notifié de tous les changements apportés au dépôt, sélectionnez "Watch".

Vous pouvez également choisir d'être notifié uniquement des changements importants en sélectionnant "Custom" et en choisissant les types de notifications que vous souhaitez recevoir.

Vous pouvez également suivre les activités d'un utilisateur spécifique en accédant à leur profil GitHub et en cliquant sur le bouton "Follow" en haut à droite de la page.

Si vous souhaitez suivre les activités de tous les dépôts d'une organisation, accédez à la page de l'organisation et cliquez sur le bouton "Follow" en haut à droite de la page.

Pour afficher toutes les activités des dépôts que vous suivez, accédez à votre page d'activité GitHub en cliquant sur votre profil GitHub, puis sur "Activity" dans la barre de navigation en haut de la page.

Vous pouvez également recevoir des notifications par e-mail en sélectionnant "Email" dans les paramètres de notification de votre compte GitHub.





