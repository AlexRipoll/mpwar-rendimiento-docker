# MPWAR (Rendimiento en Aplicaciones web)

## Instalación

- [Instalar Docker](https://docs.docker.com/install/)
- [Instalar docker-compose](https://docs.docker.com/compose/install/)
- Exportar las variables de entorno necesarias para el [correcto funcionamiento de Blackfire](https://blackfire.io/docs/integrations/docker) y crear el alias `blackfire-curl`
- Ejecutar `docker-compose up -d`

## Servicios

- Mysql: 3306
- Nginx: 8080
- Redis: 6379
- RabbitMQ: 15672
- Elasticsearch: 9200
- Kibana: 5601
- Blackfire