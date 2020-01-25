[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 01`](../Readme.md) > `Ejemplo 04`

## Ejemplo 4: Ordenamientos y límites

### OBJETIVO

- Aprender a ordenar los resultados de una consulta.
- Limitar el número de registros de una consulta.

#### REQUISITOS

1. Conexión al servidor de bases de datos que se configuró en el Ejemplo 1.
2. MySQL Workbench instalado.

#### DESARROLLO

1. Adicional a la restricción `WHERE`, es posible añadir otras restriccioens, por ejemplo, la restricción `ORDER BY` que permite ordenar los resultados de una consulta de manera ascendente (`ASC`) o descendente (`DESC`) a partir de un campo. Por ejemplo, la siguiente consulta muestra los resultados ordenados de mayor a menor a partir del campo `porcentaje`.

   ```sql
   SELECT *
   FROM Rubro
   ORDER BY porcentaje DESC;
   ```
   
   ![imagen](imagenes/s1-w41.png)

2. Para ordenar de forma ascendente puede añadirse la opción `ASC` u omitirse, pues el ordenamiento por defecto es ascentende.

   ```sql
   SELECT *
   FROM Rubro
   ORDER BY porcentaje ASC;
   
   SELECT *
   FROM Rubro
   ORDER BY porcentaje;
   ```
   
   ![imagen](imagenes/s1-w42.png)

3. Otra restricción es `LIMIT` que permite limitar el número de registros en una consulta. Esto es útil principalmente cuando se tienen miles de millones de registros y no se necesitan mostrar todos.

   ```sql
   SELECT *
   FROM Usuario
   LIMIT 3;
   ```
 
   ![imagen](imagenes/s1-w43.png)
   
