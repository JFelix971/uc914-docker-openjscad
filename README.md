# Docker OpenJScad - FELIX Jérémy

Nous avons créé une image Docker afin d'utiliser OpenJscad. 

De ce fait pour executer cette image, nous devons faire quelques commandes:

$ git clone https://github.com/JFelix971/uc914-docker-openjscad.git
$ cd uc914-docker-openjscad
$ sudo docker build -t "nom_fichier":latest


Nous pouvons, maintenant, démarrer notre container:
$ sudo docker run -p 9000:80 "nom_fichier":latest 

Pour arrêter le container : 
$ sudo docker stop "nom_fichier"
ou bien un ctrl-C ou exit.

