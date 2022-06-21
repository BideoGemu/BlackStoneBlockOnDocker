# BlackStone block on Docker

This repository was created for people who want to run Black Stone Block Modpack on a Docker based server.

Thanks to itzg (https://github.com/itzg) for his work on itzg/docker-minecraft-server

To download the modpack go to https://www.curseforge.com/minecraft/modpacks/blackstone-block

To run this server, it is imperative that docker-compose is installed.

How to install docker-compose: https://docs.docker.com/compose/install/

How to do :

- Download or copy the docker-compose.yml file and place it on your server in the directory of your choice
- Download files from BlackStone Block server to curse forge and put all files in minecraft directory (with this docker-compose file, in directory: ./files)
- run: `docker-compose up -d` in the directory where your docker-compose is located

Enjoy ! :)

Environment option:
OPS: "name,of,operators"
MEMORY: "Memory allocated to server(16G)"
ENFORCE_WHITELIST: "TRUE or FALSE"
TZ="Your time zone"

For more information on environment variables, do not hesitate to consult: https://github.com/itzg/docker-minecraft-server
