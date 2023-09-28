# Proyecto de esperanza de vida al nacer

Razones porque se elegió el proyecto de esperanza de vida al nacer:

    Mejorar la calidad de vida: Al comprender los factores que influyen en la esperanza de vida, puedes trabajar en mejorar la calidad de vida de las personas, promoviendo hábitos saludables y medidas preventivas.

    Salud pública: Estudiar y abordar la esperanza de vida es esencial para la salud pública. Puede ayudar a identificar áreas en las que se necesita atención médica y recursos adicionales, como la prevención de enfermedades y la atención a grupos de población vulnerables.

    Planificación personal y financiera: Conocer la esperanza de vida puede ayudar a las personas a planificar sus vidas, incluida la jubilación, la planificación financiera a largo plazo y las decisiones relacionadas con la atención médica.

    Toma de decisiones gubernamentales: Los gobiernos utilizan datos sobre la esperanza de vida para tomar decisiones políticas relacionadas con la atención médica, la seguridad social y otros aspectos de la vida de la población.

    Investigación científica: La investigación sobre la esperanza de vida puede arrojar luz sobre los mecanismos biológicos y sociales que influyen en la longevidad, lo que puede conducir a avances en medicina y ciencias sociales.

    Conciencia pública: Crear proyectos que aborden la esperanza de vida puede aumentar la conciencia pública sobre la importancia de llevar un estilo de vida saludable y cuidar de la salud a lo largo de toda la vida.

## Lenguaje de programación


<div align="center">
  <img src="python.png" alt="Imagen Compuesta" width="200px">
</div>

## Teconología utilizada en el proyecto

<table>
  <tr>
    <td><img src="fastapi.png" alt="Imagen 1" width="200px"></td>
    <td><img src="pyspark.png" alt="Imagen 2"width="200px"></td>
    <td><img src="github.png" alt="Imagen 2"width="200px"></td>
  </tr>
</table>

## Extraccion de los datos

Extraccion de los datos se realizó de la pagina del banco mundial (https://www.bancomundial.org/)

<div align="center">
  <img src="worldBank.svg" alt="Imagen Compuesta" width="200px">
</div>

La actualizacion de la base se realiza de manera automatica con github actions.

Se debe configurar un archivo YAML, que se coloca en un directorio llamado .github/workflows del repositorio. El YAML especifican acciones y scripts que deben ejecutarse.

El proceso de actualizacion no se realiza de manera local. Se ejecuta esta acccion del repositorio de github o mediante un push. 

Esta acción al ejecutarse actualiza datos que se encuentran, el repositorio hace una instalacion de un sistema operativo linux(ubuntu-latest), instalación de las dependencias de python y la posterior ejecución del archivo main.py.
En el caso que se realizara una modificación en el codigo y se realizara un push se actualizara nuestra base de datos.

La idea es simular servicios en la nube como Google Cloud, Amazon werb Services.

<table>
  <tr>
    <td><img src="googleCloud.svg" alt="Imagen 1" width="200px"></td>
    <td><img src="aws.png" alt="Imagen 2"width="200px"></td>
  </tr>
</table>




