[`Introducción a Bases de Datos`](../Readme.md) > `Sesión 03`

## Joins y Vistas

### OBJETIVOS 

- Escribir consultas que relacionen dos o más tablas mediante el uso de joins.
- Definir vistas que guarden el resultado de una consulta.

### TEORÍA  

- **Llaves primarias y foráneas**   

Una llave primaria permite identificar de manera única los registros de una tabla. Para relacionar tablas se usan las llaves. A los campos que aparecen como  llaves primarias de otras tablas se les llama llaves foráneas.  

> Se recomienda primero repasar el tema de forma teórica, posteriormente explicar el comando SHOW KEYS y explicar los tipos de relaciones: uno a uno, uno a muchos y muchos a muchos. Dibujar algún diagrama entidad-relación en el pizarrón que muestre cómo se unen las tablas.  

- **NUESTRO MODELO**: Diagrama entidad-relación de la tienda  

![Sin titulo](<a href="https://imgbb.com/"><img src="https://i.ibb.co/gVzc8qG/Diagrama.png" alt="Diagrama" border="0"></a>)    

*Analizar el diagrama de la base de datos del curso: ¿Qué tipos de relaciones aprecias?*  



- **Joins**    

Son operaciones que permiten relacionar dos o más tablas mediante la condición del join. Existen tres tipos en MySQL:  
- INNER JOIN  
- LEFT OUTER JOIN  
- RIGHT OUTER JOIN  
  
![Sin titulo](https://www.ionos.es/digitalguide/fileadmin/DigitalGuide/Screenshots_2018/Outer-Join.jpg)  

> Explicar qué es la teoría de conjuntos, algunas de sus operaciones y cómo se aplican mediante joins en mysql.  



- **Vistas**      
Permiten preservar los resultados de una consulta como si se tratara de una nueva tabla. Son tablas *virtuales*.     

> Mencionar los principales beneficios de usar vistas y explicar cómo crearlas (CREATE VIEW).


  
--- 

#### ORGANIZACION DE LA CLASE

- Clasificación de Joins
   - [Ejemplo 1](Ejemplo-01/)
   - [Reto 1](Reto-01/)
- Definición de vistas
   - [Ejemplo 2](Ejemplo-02/)
   - [Reto 2](Reto-02/)
- [Proyecto](Proyecto/)   
- [Postwork](Postwork/)	
