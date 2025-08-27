
# Proyecto Moodle con Docker

## DESCRIPCION

Este proyecto implementa una plataforma Moodle en un entorno visualizado con Debian y Docker, aplicando principios de UX/UI y buenas practicas de configuracion.
La propuesta surge de la necesidad institucional de mejorar la experiencia de estudiantes y docentes de la APN, ya que la plataforma original presentaba problemas de lentitud, interfaz poco intuitiva, baja automatizacion y escasa trazabilidad.
 

## Problema
- Acesso lento y tiempos de carga altos. 
- Interfaz poco intuitiva para usuarios.
- Comunicacion deficiente.
- Baja automatizacion en avisos y recordatorios.

## Solucion 

- Interfaz estable: Despliegue de docker y MariaDB 
- Experiencia mejorada: Tema Bostunion y plantilla de curso 
- Comunicacion y seguimiento: Calendario y notificaciones 
- Trazabilidad del aprendisaje: Plugins Checklist y Completion Progress
- Centralizacion: Foros y mensajeria interna

## Objetivos
Transformar la plataforma moodle aplicando principios de UX/UI y desplegandola con docker, mejorando la experiencia de usuario y la gestion academica

## Tecnologias
- Sitema operativo: Debian12 - VirtualBox
- Contenedores: Docker - Docker Compose
- Aplicaciones: Moodle - MariaDB 
- Administracion DB: pyMyAdmin 
- Plugins de Mooodle: Checklist, Completion Progress, Game, Blockxp
- Herramientas de diseño: Canva
- Gestion de proyecto: Notion, Gantt, Metodologias ADDIE + Agil 

## Como ejecutar
1. clonar el repositorio 

git clone https://github.com/YARELAR/docker-moodle.git

cd docker-moodle/src

2. Levanta contenedores 

docker-compose up -d

3. Acceder al navegador 

http://IP_DE_MV:8080
 
4. Instala los plugins desde: 

| ADMINISTRACION DEL SITIO --> EXTENSIONES --> INSTALAR PLUGINS |


### ESTRUCTURA DEL REPOSITORIO 

- SRC/ -> CONTIENE EL ARCHIVO DOCKER-COMPOSE.YML PARA EL DESPLIEGUE
- PLUGINS -> PLUGINS MOODLE UTILIZADOS EN EL PROYECTO 
- GUIDES/ -> MANUAL DE INSTALACION Y USO 
- TESTS/ -> EVIDENCIAS DE PRUEBAS UNITARIAS E INTEGRACION 
- README.MD -> DESCRIPCION DEL PROYECTO

