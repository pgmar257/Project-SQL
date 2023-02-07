# SQL (Database Building)
![portada](https://soyundba.com/wp-content/uploads/2021/04/Curso-SQL.png)

## Proyecto SQL data base building

### Introducción y primeros pasos:

Según instrucciones previas nos centramos en un  análisis y limpieza de datos, basándonos en los archivos .csv que nos brindan y ejecutándolos mediante Jupiter Notebook para así generar el archivo .ypinb que nos exigen en este proyecto.
También creamos una carpeta llamada 'src' que contenga un archivo .py el que detallamos las funciones utilizadas durante dicha limpieza de datos.

Una vez explorados los archivos .csv descubrimos que se trata de un negocio de alquiler de peliculas y llegamos a la conclusión de que todos los datos de los que disponemos son necesarios para continuar con dicho negocio.



### Load to database:

Creo una nueva base de datos llamada 'blockbuster' en MySQL workbench y procedemos a cargar los datos obtenidos en los archivos .csv.

### EER Diagram:

Al crear la base de datos y visualizarla con EER Diagram, puedo apreciar que tanto la tabla old_HDD como la tabla rental no encajan con la información que me arrojan las demás y procedo a eliminarlas.

### Inserción:

Finalmente y siguiendo las instrucciones del proyecto entre las cuales se me exige que realice una inserción, procedo a insertar 2 nuevas tablas que a su vez si coinciden con las anteriores ya mencionadas. Estas nuevas tablas las denomino "film_category" para crear una relación entre la tabla "category" y "films" y "film_actor" para así poder relacionarlas con las tablas "film" y "actor" y así poder encontrar una nueva unión entre ellas.

