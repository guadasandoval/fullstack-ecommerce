# fullstack-ecommerce
Se debe hacer git clone de los tres repositorios
- ecommerce-back
- ecommerce-docker
- ecommerce-front

# docker

Para levantar el entorno agregar los dominios en el archivo **hosts** que puede estar en las siguientes rutas:

Agregar las siguientes lineas:

127.0.0.1       ecommerce.local
127.0.0.1       ecommerce-db.local

- docker-compose up (en la carpeta en la que se encuentre docker-compose.yml)

- una vez que esté levantado phpMyAdmin, ingresar a ecommerce-db.local y crear una bd con nombre ecommerce
- correr el script db.sql
- volver a correr el back

# Datos de ingreso
user: admin@ecommerce.com
pass:123123

## Archivo
En la raiz del proyecto se encuentra un archivo .xlsx para realizar la prueba de carga de productos
