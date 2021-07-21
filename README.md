# Archivo Readme:

- Hacer comando `docker-compose up` para levantar el contenedor que tenemos preparado con el archivo docker-compose.yml
- Para desmontar el contenedor  hacer `docker-compose down`

- Para lanzar este stack, crear un fichero .env cpon el siguiente contenido:

```
ROOT_PASSWORD=<poner aqui la contraseña de root>
USER_PASSWORD=<poner aqui la contraseña del usuario>

```

- podemos levantar el stack en segundo plano con el comando `dcoker-compose up -d`