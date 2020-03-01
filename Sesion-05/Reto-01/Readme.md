[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 04`](../Readme.md) > `Reto 01`
	
## Colecciones, Documentos y Proyecciones

### OBJETIVO 

- Proyectar columnas sobre distintos documentos para repasar algunos conceptos.

#### REQUISITOS 

1. MongoDB Compass instalado.

#### DESARROLLO

Usando la base de datos `sample_mflix`, proyecta los datos que se solicitan.

- Fecha, nombre y texto de cada comentario.
- Título, elenco y año de cada película.
- Nombre y contraseña de cada usuario.

<details><summary>Solución</summary>
<p>

- Fecha, nombre y texto de cada comentario.

   ```json
   {date:1, name:1, text:1}
   ```
   
   ![imagen](imagenes/s4r11.png)

- Título, elenco y año de cada película.

   ```json
   {title:1, cast:1, year:1}
   ```
   
   ![imagen](imagenes/s4r12.png)
   
- Nombre y contraseña de cada usuario.

   ```json
   {name:1, password:1}	
   ```
   ![imagen](imagenes/s4r13.png) 

</p>
</details> 
