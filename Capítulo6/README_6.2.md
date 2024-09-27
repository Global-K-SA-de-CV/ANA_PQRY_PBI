# Unificación de Nombres en una Celda utilizando Power Query


## Objetivo de la práctica:
Al finalizar la práctica, serás capaz de:

- Aprender a utilizar Power Query para combinar columnas de texto en una sola celda y formatear los datos de manera eficiente. En este caso, unificar los campos de Nombre, Apellido Paterno y Apellido Materno en una nueva columna denominada Nombre Completo.



## Duración aproximada:
- 10 minutos.

## Escenario
Tienes una base de datos de clientes con los campos separados en Nombre, Apellido Paterno y Apellido Materno en distintas columnas. Sin embargo, para algunos informes, necesitas tener el nombre completo de cada cliente en una sola celda. En lugar de hacerlo manualmente, vas a utilizar Power Query para automatizar el proceso y unir estos campos en una columna denominada Nombre Completo.

Esta tarea es común cuando se tiene que preparar una lista de correos electrónicos, un informe de clientes o datos para otros análisis, donde se necesita mostrar el nombre completo de las personas.

### Tarea 1. Cargar los datos

Paso 1. Descarga y guarda el archivo llamado: [Registros clientes](<Registros clientes.csv>) que está en formato csv.

verás las columnas separadas de Nombre, Apellido Paterno y Apellido Materno.

Paso 2. Ve a la pestaña Datos > Obtener datos > Desde archivo > De texto/CSV.

![img243A](../images/img243A.png)

Paso 3. Selecciona el archivo  llamado *Registro Clientes* que contiene los nombres, apellidos paternos y maternos.

Paso 4. En el panel de Navegador, selecciona la tabla que contiene estos datos y haz clic en Transformar datos para abrir el editor de Power Query.

![img244](../images/img244.png)

### Tarea 2. Combinar columnas

Paso 1. En el editor de Power Query dar clic en el cuadro izquierdo que aparece a lado de la Column1 y seleccionar la opción de usar la primera fila como encabezado.

![img248](../images/img248.png)

Paso 2. Selecciona las 3 columnas que traen información del nombre y los apellidos 

![img245A](../images/img245A.png)

Paso 3. Da clic derecho y selecciona la opcion combinar columnas 

![img246A](../images/img246A.png)

Paso 4. Escobe como separador la opción de espacio y en Nuevo nombre columna escribe *Nombre completo*


![img247A](../images/img247A.png)

Paso 5. Selecciona la columa ID, da clic derecho y quitala.
![img251](../images/img251.png)

Paso 6. Seleccionamos la columna *Nombre completo* , damos clic en *cerrar y cargar en*

![img253](../images/img253.png)

Paso 7. Dejamos marcado la opción Tabla , marcamos la opción de Hoja de cálculo existente, seleccionamos la cela E1, clic en aceptar
![img252](../images/img252.png)

Paso 8. Se tendrá la nueva columna de nombre completo, solo le damos el mismo formato que la tabla original. 

![img254](../images/img254.png)

Paso 9. Guarda los cambios y cierra el archivo.

### Resultado esperado

![img255](../images/img255.png)
