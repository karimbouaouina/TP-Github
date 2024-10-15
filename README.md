# TP-Github

1. Comment vérifier la configuration actuelle de Git sur votre machine, notamment le nom d’utilisateur et l’adresse e-mail ?
Pour vérifier la configuration actuelle de Git, y compris le nom d’utilisateur et l’adresse e-mail, il faut utiliser la commande appropriée qui affiche tous les paramètres de configuration globaux et locaux de Git.

2. Comment modifier votre adresse e-mail si vous l'avez mal configurée lors de l'installation de Git ?
Si l’adresse e-mail a été mal configurée lors de l’installation, il est possible de la modifier en mettant à jour l’adresse pour tous les futurs commits à l’aide d'une commande Git spécifique.

3. Si vous avez oublié de créer un fichier README.md lors de l’initialisation du projet, comment pouvez-vous l'ajouter après coup et commiter les changements ?
Si le fichier README.md n’a pas été créé lors de l’initialisation du projet, il peut être créé par la suite, ajouté à l'index (staging), puis validé dans l’historique des commits avec un message explicatif.

4. Comment définir un dépôt distant si vous n'en avez pas configuré un lors de la création du projet ?
Si aucun dépôt distant n’a été configuré lors de la création du projet, il est possible de le définir après coup en ajoutant l’URL du dépôt distant, ce qui permet de synchroniser le projet local avec le serveur distant.

5. Comment annuler les modifications locales d'un fichier avant de les ajouter à l'index ?
Pour annuler les modifications locales d’un fichier avant de les ajouter à l’index (staging), il est nécessaire d’utiliser une méthode spécifique qui réinitialise le fichier à sa dernière version enregistrée dans le dépôt.

6. Comment visualiser les fichiers qui sont prêts à être commités dans Git (staging) ?
Pour visualiser les fichiers qui sont prêts à être commités, Git propose une commande qui liste les fichiers dans la zone de staging, indiquant ceux qui sont prêts à être enregistrés dans le prochain commit.

7. Comment suivre (track) un dépôt distant et récupérer toutes les branches de ce dépôt ?
Pour suivre un dépôt distant et récupérer toutes ses branches, il est important de récupérer les informations du dépôt sans fusionner les modifications dans la branche courante, ce qui permet de suivre l'évolution du projet hébergé.

8. Comment supprimer une branche locale après l'avoir fusionnée dans master ?
Une fois une branche fusionnée avec succès dans master, elle peut être supprimée localement afin de nettoyer l'environnement de travail et éviter la confusion avec des branches non nécessaires.

9. Comment interrompre un rebase en cours si vous avez commis une erreur ?
Si une erreur est commise lors d’un rebase, il est possible d’interrompre le processus en cours et de restaurer l’état initial de la branche, annulant ainsi toutes les modifications effectuées pendant le rebase.

10. Comment lister les commits qui vont être rebasés avant de lancer un rebase ?
Avant de lancer un rebase, il est possible de lister les commits qui vont être intégrés dans la nouvelle base, permettant de visualiser les changements qui seront appliqués à la branche.

11. Comment afficher la liste des branches actives et en cours de développement dans Gitflow ?
Dans Gitflow, il est possible d’afficher la liste des branches de fonctionnalités actives en cours de développement, permettant ainsi de suivre l’avancement des différentes tâches et fonctionnalités en cours.

12. Comment annuler une branche de correctif (hotfix) avant de la finaliser si vous constatez une erreur ?
Si une erreur est constatée avant la finalisation d’une branche de correctif (hotfix), il est possible d’annuler cette branche en la supprimant, ce qui permet d’éviter de fusionner des modifications incorrectes dans le projet.
