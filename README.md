# Docker OpenJScad - FELIX Jérémy

J'ai créé une image Docker afin d'utiliser OpenJscad.
 
 ## Execution commandes
 
$ git clone https://github.com/JFelix971/uc914-docker-openjscad.git 

$ cd uc914-docker-openjscad 

$ sudo docker build . -t "nom_fichier":latest

## Demarrer/exec image docker

$ sudo docker run -p 80:9000 "nom_fichier":latest

## Stopper image docker

$ sudo docker stop "nom_fichier"
* ou bien un ctrl-C ou exit.
