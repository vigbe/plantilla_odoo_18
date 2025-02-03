Odoo 18 - Instalación y Configuración

Requisitos Previos

Antes de comenzar, asegúrate de tener instalados los siguientes programas en tu sistema:

Docker

PostgreSQL

Instalación

Clona este repositorio dentro de una carpeta de preferencia llamada odoo/ o odoo18/:


Accede a la carpeta del proyecto:

cd ~/odoo18

Levanta los servicios de Odoo y PostgreSQL con Docker Compose:

docker-compose up -d

Accede a Odoo en tu navegador:

http://localhost:8069

Administración de Contenedores

Ver contenedores en ejecución:

docker ps

Ver logs de Odoo:

docker logs -f odoo18

Reiniciar Odoo:

docker restart odoo18

Detener todos los servicios:

docker-compose down

Notas

Para agregar módulos personalizados, colócalos dentro de la carpeta addons/ antes de ejecutar docker-compose up -d.

Puedes editar los archivos de los módulos usando PyCharm Community o cualquier editor de texto.

🚀 ¡Listo! Ahora puedes trabajar con Odoo 18 en Docker.

