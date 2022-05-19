# Servicio de GPS en base a Traccar

## Crear un directorio de trabajo en path donde gaurdaremos los volumenes de la imagen

### Ejemplo mi maquina

mkdir -p ~/Proyectos/docker/traccar/app/logs 

### Creamos el archivo de configuracion xml por default

docker run --rm --entrypoint cat gps  /opt/traccar/conf/traccar.xml > ~/Proyectos/docker/traccar/app/traccar.xml


