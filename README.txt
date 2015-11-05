Installation Git:
sudo apt-get update --> Mise à jour des paquets
sudo apt-get install git --> Installation de Git

Installation Jekyll:
sudo apt-get update --> Mise à jour des paquets
sudo apt-get install jekyll --> Installation de Jekyll

Contrôler la version de jekyll:
jekyll -v

Installation ruby --> Utilisation de ruby car Jekyll est codé en ruby
sudo apt-get install ruby-full

Installation NodeJS --> 
sudo apt-get install nodejs npm

Mettre à jour la version de jekyll: ?????????

Lancement de Jekyll:
jekyll new myblog --> Création d'un fichier blog contenant un index, etc...
cd myblog --> Placement dans le dossier du blog
jekyll serve -->  Configure le serveur sur le localhost
 
=> Dans l'url du navigateur : http://localhost:4000 


Configuration GIT:(https://pages.github.com/)

Clonage:
git clone https://github.com/username/username.github.io

Création d'un index dans dossier github:
cd username.github.io
echo "Hello World" > index.html


Push it:
git add --all
git commit -m "Initial commit"
git push -u origin master



