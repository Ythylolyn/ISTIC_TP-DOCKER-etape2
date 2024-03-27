objectif : Construisre le fichier docker file permettant de créer l'image docker pour cette application : https://github.com/barais/TPDockerSampleApp

dépendances nécessaires : 
apt-get update
apt-get install -y openjdk-8-jdk
apt-get install -y maven
apt-get install -f libpng16-16
apt-get install -f libjasper1
apt-get install -f libdc1394-22

Sur le terminal : se rendre dans le dossier où se trouve le Dockerfile
Compiler l'image : docker build 
Afficher toutes les images : docker image ls
Renommer une image : docker tag « id » « nom_app »
Executer l’application : docker run -p « port à exposer»:8080 -t -i « nom_app »
