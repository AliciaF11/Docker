# Projet Docker
## Objectif du projet
Ce projet consiste à mettre en place une infrastructure composée d'un firewall, un client et un serveur. Ils seront chacun dans un container docker. Pour faciliter la communication entre les trois nous avons utilisé Docker Compose.

## Installation Docker
On fait une mise à jour: $ apt-get update  
La commande suivante permet d'installer docker: $ apt-get install docker-ce

## Installation Docker-compose
Pour cela: $ curl -L https://github.com/docker/compose/releases/download/v2.0.1/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose  
On vérifie que la nouvelle version est installée: 
![image](version_docker1.png)

## Infrastructure mis en place

![image](infrastructure_11.png)
![image](infrastructure_2.png)
![image](infrastructure_3.png)
![image](infrastructure_4.png)

## Contenu des fichiers

### Client
#### client.py
![image](client1_py.png)
#### Dockerfile
![image](Dockerfile_client.png)

### Server
#### server.py
![image](server_py.png)
#### DockerFile
![image](Dockerfile_server.png)
#### index.html
![image](index_html.png)

### Firewall
#### clean.sh
#### firewall.sh
#### Dockerfile
![image](Dockerfile_firewall.png)

### Docker-compose
#### docker-compose.yml
![image](docker_compose_yml.png)

## Construction de Docker-compose 
Pour cela, on exécute la commande : $ docker-compose build

## Lancement de Docker-Compose
On exécute la commande suivante: $ docker-compose up
