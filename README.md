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
