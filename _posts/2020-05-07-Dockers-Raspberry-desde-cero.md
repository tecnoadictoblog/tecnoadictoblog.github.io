---
layout: post
title: Instala Dockers en una RaspberryPi desde cero
---
Descarga [Raspberry Pi Imager](https://www.raspberrypi.org/downloads/)

Instala Raspbian Lite (sin desktop)

SD 32GB

`raspberrypi login: pi`
`Password: raspberry`

`pi@raspberrypi:$ sudo raspi-config`
>ojo que puede que el teclado no esté en tu idioma y el "-" esté arriba en la "?"

## Dockers useful links
https://www.atareao.es/tutorial/docker/ejecutar-contenedores-docker/

https://github.com/gcgarner/IOTstack/wiki/Getting-Started

https://medium.com/@airman604/installing-docker-in-kali-linux-2017-1-fbaa4d1447fe

## Commands

docker pull 

docker run -d --name el-mioxx nodered/node-red

docker ps -a

docker stop el-mioxxx

docker start el-mioxxx

docker rm el-mioxx

docker image ls

docker image rm nodered/node-red

docker image pull

docker container ls

## Node-red

https://github.com//node-red/node-red-docker

`docker run -it -p 1880:1880 --name mynodered nodered/node-red`

`docker start mynodered`

## IoTstack

https://github.com/gcgarner/IOTstack

`sudo apt-get install git`

`git clone https://github.com/gcgarner/IOTstack.git ~/IOTstack`

`cd IOTstack` y después ejecutar

`./menu.sh`
