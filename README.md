# homelab
composer for personal homelab setup

The compose file in the root directory has to be executed first since it creates the network
the rest of the compose files can be exeuted seperatly tho the homenetwork does contain the nginx_reverse_proxy which is used in the other compose files as well



This does not use docker swarm for the deployment



finance/compose.yml uses a adjusted version of https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/.env.example as the .env file
it is also based on https://raw.githubusercontent.com/firefly-iii/docker/main/docker-compose.yml
