# Práctica final Prometheus y Grafana

## Iniciar los servicios

Para poder iniciar los servicios que hemos indicado en los ficheros docker-compose.yml y prometheus.yml, se inician de la siguiente manera:

``` docker-compose up -d ```

## Verificar los servicios

Para poder verificar que los servicios se hayan creado correctamente, debemos de ejecutar el siguiente comando:

``` docker-compose ps ```

## Grafana

Una vez ya iniciados los servicios y comprobado que este todo correcto, podemos abrir en el navegador web e ir a ```http://localhost:3000``` para poder abrir e iniciar sesion en **Grafana**

Para iniciar sesión por primera vez, deberas de poner las siguientes credenciales:

- Usuario: ```admin```

- Contraseña: ```admin```

Al iniciar sesión por primera vez, se te solicitará el cambio de la contraseña predeterminada.

## Configurar la fuente de datos de Prometheus en Grafana

1. En Grafana debemos de ir a **Connections** > **Data Sources**

2. Hacer click en **Add data source**

3. Seleccionamos "Prometheus"

4. Configurar la URL: ```http://prometheus:9090```

5. Una vez terminado, hacer click en **Save & Test** para verificar la conexión


