# Instalación de Odoo mediante docker compose

## Creamos el docker compose
Vamos a crear el documento yml, para ello vamos a abrir el editor de texto o con el comando:

```nano docker-compose.yml```

En el directorio que queremos qeu este el archivo. Dentro escribimos los servicios que necesitamos para la instaclación de Odoo.

- Base de datos: Postgresql
- Administrador de base de datos: pgAdmin
- Odoo

[](docker-compose)

[! IMPORTANTE]
> Como vemos en el docker compose, tenemos que especificar la version de las imagenes que querramos
> descargar. Esto es importante ya que Odoo tiene diferentes módulos segun sus versiones.


