[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 03`](../Readme.md) > `Ejemplo 01`

## Ejemplo 1: Clasificación de Joins

### OBJETIVO

- Analizar la relación que existe entre dos o más tablas.
- Comprender las distintas formas de relacionar tablas mediante el uso de las cláusulas `JOIN`, `LEFT JOIN` y `RIGHT JOIN`.

#### REQUISITOS

1. MySQL Workbench instalado.

#### DESARROLLO

1. Abre MySQL Wokbench y conectate a la base de datos del curso.

2. Para poder relacionar tablas, necesitamos conocer las *llaves primarias* y *foráneas* presentes en una tabla. Una forma de encontrar esto es usando la primitiva `SHOW KEYS`. Por ejemplo, a continuación se muestran las llaves para la tabla `venta` del esquema `tienda`.

   ```sql
   SHOW KEYS FROM venta;
   ```
   
   ![imagen](imagenes/s2we12.png)
   
   La llave primaria se resalta pues en el campo `Key_name` aparece el valor `PRIMARY`, mientras que el resto de las llaves se consideran llaves foráneas.
   
3. Los joins son usados para obtener información de varias tablas. Para obtener esta información, existen tres variantes de join: por la izquierda, por la derecha y el join simple.

   *`JOIN`/`INNER JOIN`*
   
   Es el tipo de join más común y regresa todos los registros de múltiples tablas donde se cumplan la condición del join (*join codition*). Por ejemplo, podemos relacionar la tabla `empleado` con `puesto`.
   
   ```sql
   SELECT *
   FROM empleado AS e
   JOIN puesto AS p
     ON e.id_puesto = p.id_puesto;
   ```

   ![imagen](imagenes/s2we12.png)
   
   *`LEFT JOIN` / `LEFT OUTER JOIN`*  
 
