[`Introducción a Bases de Datos`](../../Readme.md) > [`Sesión 01`](../Readme.md) > `Postwork`

## Postwork

### OBJETIVOS

- Continuar practicando los conceptos de la sesión.
- Iniciar con el planteamiento del problema que resolverás a lo largo de todo el programa.

#### REQUISITOS

1. MySQL Workbench instalado.

#### DESARROLLO

##### Parte I: Películas

Durante la sesión, hicimos la conexión a la base de datos llamada `cursos` ahora, usarás las base de datos `Movies` para contestar algunas preguntas mediante la generación de consultas.

Es importante que al momento de diseñar tus consultas trates de dividir cada una de éstas por partes y no de un jalón. La idea es que analices qué datos necesitas, de dónde los obtendrás y cómo los procesarás para obtener la respuesta a cada pregunta.

Dicho esto, responde las siguientes preguntas, recuerda revisar antes la estructura de cada tabla.

1. ¿Qué usuarios son del género femenino?
2. El campo edad se define de acuerdo a los siguientes criterios:
   ```
   *  1:  "Under 18"
   * 18:  "18-24"
   * 25:  "25-34"
   * 35:  "35-44"
   * 45:  "45-49"
   * 50:  "50-55"
   * 56:  "56+"
   ```
   ¿Cuáles usuarios son menores de edad?
3. ¿Qué usuarios son del género femenino y además son menores de edad?
4. El campo ocupación se define de acuerdo a la siguiente tabla:
   ```
   *  0:  "other" or not specified
   *  1:  "academic/educator"
   *  2:  "artist"
   *  3:  "clerical/admin"
   *  4:  "college/grad student"
   *  5:  "customer service"
   *  6:  "doctor/health care"
   *  7:  "executive/managerial"
   *  8:  "farmer"
   *  9:  "homemaker"
   * 10:  "K-12 student"
   * 11:  "lawyer"
   * 12:  "programmer"
   * 13:  "retired"
   * 14:  "sales/marketing"
   * 15:  "scientist"
   * 16:  "self-employed"
   * 17:  "technician/engineer"
   * 18:  "tradesman/craftsman"
   * 19:  "unemployed"
   * 20:  "writer"
   ```
   ¿Cuáles usuarios son estudiantes o desempleados?
5. ¿Cuáles usuarios no son estudiantes ni desempleados y son menores de edad?
6. ¿Cuál es el top 5 de ratings más alto?

##### Parte II: Planteamiento del proyecto

A lo largo del programa deberás desarrollar un proyecto. En este postwork, debes definir con qué conjunto de datos vas a trabajar, si es un proyecto de datos propios o vas a seleccionar algún conjunto de datos público.

Si haces uso de los datos públicos a continuación algunas sugerencias para buscar y descargar conjuntos de datos
   - https://datos.gob.mx
   - https://grouplens.org
   - https://www.kaggle.com
   - https://archive.ics.uci.edu/ml/datasets.php

Una vez que sepas con qué datos vas a trabajar, define cómo los usarás y qué problema vas a resolver. Ten esto muy en cuenta pues lo usaremos en la siguientes sesiones.
