# snippet_docker

## source 
* https://docs.docker.com/engine/install/centos/

## Installation docker engine
* sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
* sudo yum install docker-ce docker-ce-cli containerd.io
* y
* y
* docker version

## Démarrage du process
* sudo systemctl start docker
* sudo systemctl status docker

## Monitoring
* sudo docker images
* sudo docker ps
