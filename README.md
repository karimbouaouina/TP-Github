# TP-Github

1. Comment vérifier la configuration actuelle de Git sur votre machine, notamment le nom d’utilisateur et l’adresse e-mail ?
git config --list

2. Comment modifier votre adresse e-mail si vous l'avez mal configurée lors de l'installation de Git ?
git config --global user.email "nouvelle-adresse@email.com"

3. Si vous avez oublié de créer un fichier README.md lors de l’initialisation du projet, comment pouvez-vous l'ajouter après coup et commiter les changements ?
touch README.md
git add README.md
git commit -m "Ajout du fichier README.md"

4. Comment définir un dépôt distant si vous n'en avez pas configuré un lors de la création du projet ?
git remote add origin git@github.com:votre-nom-utilisateur/votre-projet.git

5. Comment annuler les modifications locales d'un fichier avant de les ajouter à l'index ?
git checkout -- nom_du_fichier

6. Comment visualiser les fichiers qui sont prêts à être commités dans Git (staging) ?
git status

7. Comment suivre (track) un dépôt distant et récupérer toutes les branches de ce dépôt ?
git fetch --all

8. Comment supprimer une branche locale après l'avoir fusionnée dans master ?
git branch -d nom-de-la-branche

9. Comment interrompre un rebase en cours si vous avez commis une erreur ?
git rebase --abort

10. Comment lister les commits qui vont être rebasés avant de lancer un rebase ?
git log --oneline nom-de-la-branche..master

11. Comment afficher la liste des branches actives et en cours de développement dans Gitflow ?
git flow feature list

12. Comment annuler une branche de correctif (hotfix) avant de la finaliser si vous constatez une erreur ?
git branch -D hotfix-nom-de-la-branche
