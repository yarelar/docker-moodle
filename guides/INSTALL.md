# GUIA DE INSTALACION 

Este documento explica el proceso de instalacion del proyecto desplegando docker sobre debian.

## Preparacion del sistema

1. **Actualizacion de paquetes**

```bash 

sudo apt update && sudo apt upgrade -y

## Instalacion dependencias basicas

sudo apt install -y ca-certificates curl

## Instalacion de docker y docker compose

1. Agregar claves de docker 

```bash
 
sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo tee /etc/apt/keyrings/docker.asc > /dev/null
sudo chmod a+r /etc/apt/keyrings/docker.asc

2. Agregar repositorio 


