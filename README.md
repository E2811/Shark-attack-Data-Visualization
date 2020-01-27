# Shark-attack-Data-Visualization


## SELACOFOBIA 

Puede que este termino os sea familiar o por el contrario nunca hayais oido hablar de él. Se refiere al miedo irracional a los tiburones. 

Relacionamos a estos animales con peligro y ataque. Esto puede ser debido a peliculas como "tiburon" entre otras, pero, ¿Es realmente este miedo justificado? 

Para responder a esta pregunta se ha realizado un analisis de un dataset con informacion acerca de distintos ataques de tiburones. 
Gracias a los datos proporcionados, se han extraido ciertas conclusiones. Las areas estudiadas incluyen:
 -¿los ataques producidos suelen ser provocados?
 -¿Son realmente frecuentes?
 -¿En que zonas han sido mas recurrentes?
 -¿Que actividades se realizaban durante estos ataques? 
 -¿Se ven más afectados los hombres o las mujeres? ¿Fatales?
 
 ## Método
 
 ### Filtrado de columnas innecesarias

En primer lugar, las columnas con mas de un 90% de datos nulos se eliminaron. 
Seguidamente, se compararon columnas similares. Aquellas que compartían más del 90% de los datos iguales tambien fueron eliminadas. 

A partir de aquí se ha hecho un filtrado por categorias

### Filtrado de tipo de ataque

Para comprobar si hay mayor numero de ataques provocados o de forma involuntaria, se normalizaron los datos estableciendo cinco posibles categorias. A partir de aquí se sumaron todos los casos para poder calcular porcentajes. 

### Filtrado de paises 

Se agruparon los ataques por países para establecer el país con mayor número de ataques registrados. Una vez obtenido ese dato, se obtuvo el area y la localidad más afectada. 

### Filtrado actividades 

Para poder normalizar la columna de actividades se dividieron 5 actividades principales (Swimming,Fishing,Water_Sports,Surfing,Near_shore). 

### Filtrado de fechas

A partir de los Case Numbers, se obtuvo la fecha y el año de cada ataque. Luego se divieron en decadas para comprobar si se han aumentado los ataque.

### Filtrado de sexo y fatality

Por ultimo se calcula si el numero de hombres es mayor que el de mujeres, y si los ataques provocados son mortales. 

A partir de aqui tenemos un dataset más estructurado que nos permitiria hacer un estudio de distintas relaciones e hipotesis. Se podría seguir el proceso de filtrado. 

## Conclusiones

Los datos señalan que USA es el país con mayor registro de ataques, especialmente en Florida y en la localidad de New Smyrna Beach, Volusia County. La mayoria de los ataques no son provocados, ni fatales. Las actividades más repetidas durante los ataques son el surf (principalmente en los ultimos años) y nadar/bucear en el agua. Se produce un mayor numero de ataques hacia hombres en comparación con mujeres. Se desconoce la causa, podría ser debido a que tiene un mayor interés en el surf o las actividades acúaticas. 