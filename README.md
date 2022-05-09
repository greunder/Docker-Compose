# Projet-Docker


Consigne : Etablir une infrastructure Docker compose associée à l'Intelligence Artificielle (Machine Learning dans ce cas ci).

Ce projet consiste a tester un model simple de regression linéaire.

On utilisera des libraries comme numpy , Scikit learn et pour la visualisation des résultats.


# Installation des pré-requis
sudo apt install apt-transport-https ca-certificates curl software-properties-common

# Se procurer la source officiel
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

# Mettre a jour les paquets
sudo apt update

# Installation de Docker ce
sudo apt install docker-ce

# Demarrage de Docker
#sudo systemctl status docker

# Installation docker-compose

sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose
# On verifie que Docker Compose à bien été installé en verifiant sa version
docker-compose --version



