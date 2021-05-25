
Bonjour,
Dans ce fichier vous trouverez les étapes pour lancer un projet GIT.
Taper la commande suivante :
git config --global user.name "Nom utilisateur"
git config --global user.email "adresseMail"

Ensuite tapez les commandes suivantes :
git init  #initialisation du repo git
git clone https://gitlab.com/NomProjet/projet.git ##Clonnage du repo distant sur la machine en local
touch README.md ##Création d'un fichier readme
git add README.md ##Ajout du fichier readme pour la prise en compte
git commit -m "add README" ##Commit du fichier readme
git push -u origin master ##Push vers le distant


