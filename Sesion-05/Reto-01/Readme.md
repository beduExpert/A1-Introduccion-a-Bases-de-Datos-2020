[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 05`](../Readme.md) > `Reto 01`
	
## Expresiones regulares

### OBJETIVO 

- Poner en práctica el uso de expresiones regulares.

#### REQUISITOS 

1. MongoDB Compass instalado.

#### DESARROLLO

Usando la base de datos `sample_airbnblistingsAndReviews`, realiza los siguientes filtros:

- Propiedades que no permitan fiestas.
- Propiedades que admitan mascotas.
- Propiedades que no permitan fumadores.
- Propiedades que no permitan fiestas ni fumadores.

<details><summary>Solución</summary>
<p>

- Propiedades que no permitan fiestas.

   ```json
   {house_rules: /No Parties/i}
   ```
   
   ![imagen](imagenes/s5r11.png)

- Propiedades que admitan mascotas.

   ```json
   {house_rules: /Pets Allowed/i}
   ```
   
   ![imagen](imagenes/s5r12.png)
   
- Propiedades que no permitan fumadores.

   ```json
   {house_rules: /No Smoking/i}	
   ```
   ![imagen](imagenes/s5r13.png) 
   
- Propiedades que no permitan fiestas ni fumadores.

   ```json
   {house_rules: /No Smoking|No Parties/i}
   ```
   
   ![imagen](imagenes/s5r14.png)


</p>
</details> 
