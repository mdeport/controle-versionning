Questions 1:

la difference entre un commit, une branche et un tag est que le commit est une sauvegarde de l'état du projet a un certain moment en local, une branche est une version du projet qui peut etre modifiee sans affecter les autres branches et un tag est souvent utilisé pour marquer les point de version dans l'historisque des commits.

Questions 2:

la commande GIT pour clone un dépôt est : git clone <le lien du depot que l'on veut clone>
la commande pour créer une nouvelle branch est : git branch <nom que l'on veut donner a la nouvelle branche>
la commande pour committer des modifications est : git commit -m "message que l'on veut donner au commit"
la commande pour pousser des modifications sur un depot distant est : git push

Questions 3:

Le workflow Git Flow est un workflow qui va nous permettre de travailler sur plusieurs branches en même temps. Avec les deux branches principales qui sont : la branch Main qui va contenir le code de production et la branche develop qui va contenir le code de développement. Les branches secondaires sont les branches feature qui vont contenir les nouvelles fonctionnalités, les branches release qui vont contenir les fonctionnalités qui vont être bientôt déployées et les branches hotfix qui vont contenir les corrections de bugs.

Questions 4:

Le fichier qui permet de lire la description du projet est le fichier README.md qui est remplie au fur et a mesure du projet par les membres du groupe.
Ce fichier sert à donner des informations sur le projet comme :

- le nom du projet
- les auteurs du projet
- les prérequis du but du projet et le descripit du projet.
- les commandes qui pourraient etre utile a utiliser sur GIT.
- les gros problème qu'il aurait rencontré tout long du projet

Questions 5:

Cette commande permet de cloner le dépôt Github en local sur notre ordinateur pour pouvoir travailler dessus.
Elle est nécessaire pour pouvoir travailler sur le projet en local et pouvoir apporter des modifications sur les different élement du projet.

Questions 6:

Cette commande permet de voir les branches qui sont présentes sur le dépôt distant et les branches qui sont présentes sur le dépôt local.

Questions 7:

Cette commande va nous permettre de directement créer une nouvelle branche qui va s'appeler myfeature et de nous mettre directement dessus.
feature/myfeature représente que la branche va servir a ajouter une nouvelle fonctionnalité dans notre projet et que cette fonctionnalité va s'appeler myfeature.

Questions 8:

Cette commande git log --graph --oneline va nous permettre de voir l'historique des commits qui ont été fait sur le projet.
Et va bien nous permettre de comprendre l'historique de commit fait.

Questions 9:

git add . : permet d'ajouter les fichiers modifiés dans le commit et avant de faire le commit
git commit -m "Fictive Feature" : permet de créer un commit avec le message "Fictive Feature"
git rebase master : permet de mettre à jour la branche feature/myfeature avec les modifications de la branche master
git push origin feature/myfeature : permet de pousser la branche feature/myfeature sur le dépôt distant
Il est important de faire un git rebase master avant de pousser la branche car cela permet de mettre à jour la branche avec les modifications de la branche master et ainsi éviter les conflits lors de la fusion des branches.
