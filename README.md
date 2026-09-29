# bssid-mapper
A tool to know the position of each wifi ap \ 
The idea is to make an embebed system that use a camera to detect and show the information of an AP in that direction \

# Material to use: 
Raspberry pi 4b 4gb con raspbery OS \
Pi camera o camara XBOX 360 \
Adaptador Wifi RTL8812 o AR9271 \

Posibilidad de evolucion a un sistema portatil embebido

# Paso a paso

## Paso 1:
Instalar raspberry pi os lite en la raspberry\
Comprobar que la web cam y adaptador wifi que tenemos funcionan correctamente y son detectados por el sistema\
Sudo apt update\
sudo apt upgrade

## Paso 2:
Instalar dependencias\
  sudo apt install python3-opencv \
  sudo apt install scapy \
  sudo apt install aircrack-ng 
