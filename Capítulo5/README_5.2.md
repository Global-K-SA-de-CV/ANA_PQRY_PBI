# Práctica 5.2. Analizando los datos de la tabla dinámica.

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Modificar informes de tablas dinámicas para extraer y analizar datos específicos, como ventas por trimestre y región. <br>
- Aplicar filtros y personalizar la visualización de datos en tablas dinámicas. <br>
- Formatear datos en una tabla dinámica utilizando opciones de configuración de campos de valor. <br>
- Ordenar datos en una tabla dinámica para identificar tendencias y patrones de ventas. <br>

## Duración aproximada:
-  15 minutos.

## Instrucciones:

### Antes de comenzar:

Asegúrate que el libro de trabajo _My Sales Data.xlsx_ esté abierto.

### Escenario:

Estás satisfecho con los informes de la tabla dinámica que has creado. Ahora deseas ver qué otra información puedes extraer de la tabla dinámica. Para ello, decides ver si puedes responder las siguientes preguntas:

- ¿Cuáles son las ventas del cuarto trimestre? <br>
- ¿Cuáles son las ventas totales para cada trimestre por región? <br>
- ¿Cuáles son las ventas totales para cada región por producto? <br>

### Tarea 1. Modificar el informe de la tabla dinámica en _Hoja1_ para responder a la pregunta: "¿Cuáles son los valores de ventas del cuarto trimestre?".

**Paso 1.** Selecciona la _Hoja 1_ y verifica que la tabla dinámica está seleccionada.

![img199](../images/img199.png)

**Paso 2.** En el panel de tareas _Campos_ de la tabla dinámica, en la opción _Mostrar_, seleeciona **Lista de campos**, arrastra y suelta el campo _Trimestre_ _(Quarter)_ en el área de _Filtros_. Verifica que _Trimestre_ está en la celda **A1** y que hay un filtro en la celda **B1**.

![img200](../images/img200.png)

**Paso 3.** Selecciona la flecha desplegable en la celda **B1** > **Cuarto Trimestre** > **OK**.

**Nota:** Verifica que las ventas totales del cuarto trimestre son _10025418_.

![img201](../images/img201.png)

### Tarea 2. Eliminar el filtro de _Trimestre_ y modifica el informe de la tabla dinámica para responder a la pregunta: "¿Cuáles son las ventas totales por región para cada trimestre?".

**Paso 1.** Da clic en la flecha desplegable de _AutoFiltro_ en la celda **B1**, selecciona **Seleccionar todo** y luego **OK**.

![img202](../images/img202.png)

**Paso 2.**  En el panel de tareas _Campos_ de la tabla dinámica, en la sección _Arrastrar campos_ entre las áreas a continuación, arrastra y suelta _Trimestre_ desde el área de _Filtros_ al área de _Columnas_.

**Nota:** Verifica que el informe de la tabla dinámica se actualiza para mostrarte las ventas totales para cada región por trimestre.

![img203](../images/img203.png)

### Tarea 3. Modificar la tabla dinámica en _Hoja 2_ para responder a la pregunta: "¿Cuáles son las ventas totales para cada región por producto?".

**Paso 1.** Selecciona _Hoja 2_ y verifica que la Tabla dinámica está seleccionada.

**Paso 2.** En el panel de tareas _Campos_ de la tabla dinámica, en la sección _Arrastrar campos_ entre las áreas a continuación, arrastra y suelta _Productos_ desde el área de _Filas_ al área de _Columnas._

**Nota:** Verifica que el informe de la tabla dinámica se actualiza para mostrarte las ventas regionales para cada producto.

![img204](../images/img204.png)

### Tarea 4. Modificar el formato del informe de la tabla dinámica.

**Paso 1.**  En el panel de tareas Campos de la tabla dinámica, en la sección Arrastrar campos entre las áreas a continuación, en el área _Valores_, selecciona la flecha desplegable de _Suma de ventas totales_ y selecciona Configuración de campo de valor.

![img205](../images/img205.png)

**Paso 2.** En el cuadro de diálogo _Configuración_ de campo de valor, selecciona el botón _Formato de número._

**Paso 3.** En el cuadro de diálogo _Formato de celdas_, en la lista de _Categorías_, selecciona **Moneda**.

**Paso 4.** En el cuadro de _Posiciones decimales_, escribe `0` y después da clic en **OK**.

![img206](../images/img206.png)

**Paso 5.** En el cuadro de diálogo _Configuración_ de campo de valor, selecciona **OK** para guardar la configuración del campo de valor.

**Nota:** Verifica que la tabla dinámica ha actualizado los valores totales de ventas con el formato de moneda.

![img207](../images/img207.png)


### Tarea 5. Ordenar los valores de _Total general_ de menor a mayor.

**Paso 1.** Selecciona uno de los valores de _Total general_ en la columna **K**.

**Paso 2.**  Selecciona _Inicio > Ordenar y filtrar > Ordenar de menor a mayor_.

**Nota:** Verifica que los totales generales estén ordenados de menor a mayor.

![img208](../images/img208.png)

**Paso 3.** Guarda el libro de trabajo y conserva el archivo abierto.

### Resultado esperado:

![img208A](../images/img208A.png)

## [Menú principal](../README.md)

## [Práctica 5.1. Crear una Tabla Dinámica.](../Capítulo5/README_5.1.md)

## [Práctica 5.3. Presentación de datos con gráficos dinámicos.](../Capítulo5/README_5.3.md)
