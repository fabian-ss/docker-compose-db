# docker-compose-db
Configuración inicial de docker-compose para algunas bases de datos, se cambiaran los parámetros según los requerimientos del proyecto.

  Configuración de MongoDB en Windows por consola:
  
    Entrar al directorio del archivo docker-compose y ejecutar el siguiente comando: 
        $ docker-compose exec mongo /bin/sh   

    Conectamos a la shell mongosh usando las credenciales del docker-compose:
        $ mongosh "mongodb://localhost:27017" --username root --authenticationDatabase admin

  Advertencia: En Windows usar cmd o powershell, ya que no pude hacer esto con git bash
