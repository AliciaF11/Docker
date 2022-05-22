# Projet Docker
## Objectif du projet
Ce projet consiste à mettre en place une infrastructure composée d'un firewall, un client et un serveur. Ils seront chacun dans un container docker. Pour faciliter la communication entre les trois nous avons utilisé Docker Compose.

## Installation Docker
On fait une mise à jour: apt-get update
La commande suivante permet d'installer docker: sudo apt-get install docker-ce

## Installation Docker-compose
Pour cela: sudo curl -L https://github.com/docker/compose/releases/download/v2.0.1/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
On vérifie que la nouvelle version est installée: 
![image](version_docker.png)

## Infrastructure mis en place

![image](infrastructure1.png)
![image](infrastructure2.png)
![image](infrastructure3.png)
![image](infrastructure4.png)


## Construire Docker-Compose 
Pour cela, on tappe la commande : docker-compose build

## Exécution Docker-Compose
docker-compose up

