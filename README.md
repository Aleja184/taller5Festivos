# Taller 5 - Festivos
## Importante: Al momento de clonar el repositorio se sugiere usar el comando: git clone --recursive 'url' para que se se inicialice y actualice automáticamente cada submódulo en el repositorio

## BackEnd

Para la base de datos que se usa, están los archivos DDL - Festivos.sql y DDM - Festivos.sql, debemos crear una base de datos que se llame festivos para ejecutar estas querys. 

Para el inicio del backend se debe de dirigir a la carpeta API-Festivos, allí en esta ruta:

Api-Festivos>src>main>resources>application.properties

Se pone el User y Password de PostgreSQL: 
spring.datasource.username='user'
spring.datasource.password='password'

Luego en el ApiApplication corremos el back, y estamos listos para hacer uso de esta: 
http://localhost:8080/festivos/2025/11/17, 
http://localhost:8080/festivos/2025

## FrontEnd
Para el front desde la terminal nos dirigimos a la carpeta festivos y allí corremos el comando: 
`npm install`

Luego: 
`ng serve`

Si abrimos el localhost:4200 podremos escoger la fecha para saber si es festivo, si por el contrario abrimos añadimos la ruta **/anio** podremos digitar un año y conocer sus festivos.

**Nota:**Por efectos de tiempo solo se añadió el año 2025 en la base de datos.
