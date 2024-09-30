# Práctica 5.4. Filtrar datos utilizando segmentaciones (Slicers) y líneas de tiempo (Timelines).

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Utilizar líneas de tiempo (Timelines) en tablas dinámicas y gráficos dinámicos para filtrar y visualizar datos específicos, como las ventas del cuarto trimestre en una región determinada. <br>
- Insertar y personalizar segmentaciones (Slicers) para filtrar tablas dinámicas y gráficos dinámicos, permitiendo un análisis más detallado de los datos. <br>
- Aplicar filtros combinados utilizando segmentaciones múltiples para analizar ventas en diferentes estados y por diferentes vendedores. <br>
- Interpretar los resultados filtrados para identificar tendencias y patrones, como la distribución de ventas en regiones específicas y el rendimiento de vendedores particulares. <br>

## Duración aproximada:
- 15 minutos.

## Instrucciones:

### Antes de comenzar:

Revisa que el libro de trabajo _My Sales Data.xlsx_ esté abierto. 

### Escenario:

Estás satisfecho con las modificaciones realizadas en los informes de tablas dinámicas y los nuevos gráficos dinámicos que has creado. Sin embargo, te das cuenta de que las preguntas iniciales para analizar los datos fueron planteadas desde tu propia perspectiva. Para hacer que tanto las tablas dinámicas como los gráficos sean más versátiles, decides agregar una línea de tiempo e insertar segmentaciones. Esto permitirá que tú, y cualquier otra persona, puedan visualizar los datos de ventas de diferentes maneras.

### Tarea 1. Inserta una línea de tiempo para ver los valores de ventas del cuarto trimestre para la región suroeste.

**Paso 1.** Selecciona la hoja de trabajo _Hoja2_ y mueve el gráfico dinámico para ver claramente la tabla dinámica, si es necesario. Haz doble clic a una barra del gráfico y, en los campos de la tabla dinámica, desmarca **State**.

**Paso 2.** Selecciona la tabla dinámica (PivotTable) y, en la pestaña contextual _Analizar tabla dinámica_, selecciona **Insertar escala de tiempo**.

![img217A](../images/img217A.png)

**Paso 3.** En el cuadro de diálogo **Insertar líneas de tiempo** (Insert Timelines), selecciona **Fecha de pedido** (Order Date) y da clic en **OK**.

![img218](../images/img218.png)

**Paso 4.** Si es necesario, mueve la línea de tiempo para poder observar claramente todos los objetos de la hoja de trabajo.

**Paso 5.** Da clic en la flecha desplegable del _Nivel de tiempo_ (Time Level) y selecciona **TRIMESTRES** (QUARTERS).

![img219](../images/img219.png)

**Paso 6.** Selecciona Q4 de 2021 y verifica que, tanto la tabla como el gráfico dinámico, se actualicen para mostrar sólo los valores del cuarto trimestre.

![img220](../images/img220.png)

### Tarea 2. Inserta segmentaciones (slicers) para filtrar la tabla dinámica (PivotTable) y el gráfico dinámico (PivotChart).

**Paso 1.** Selecciona la **Tabla dinámica** (PivotTable) y, si es necesario, en la pestaña contextual _Analizar tabla dinámica_ (PivotTable Analyze), haz clic en **Insertar segmentación** (Insert Slicer).


![img221](../images/img221.png)

**Paso 3.** En el cuadro de diálogo _Insertar segmentación_ (Insert Slicer), marca **Estad**o (State) y **Vendedor** (Salesperson), y da clic en **OK**.

![img222](../images/img222.png)

**Paso 4.** Mueve las segmentaciones de _Vendedor_ (Salesperson) y _Estado_ (State) según sea necesario para observar claramente todos los objetos de la hoja de trabajo.

![img223](../images/img223.png)

### Tarea 3. Utilizar las segmentaciones, filtrar las ventas en Nuevo México y Texas para el vendedor Anderson.

**Paso 1.** En la segmentación de _Estado_ (State), selecciona **Selección múltiple** (Multi-Select).

**Paso 2.** Selecciona **AZ** y **OK** para desactivar esos estados.

![img224](../images/img224.png)

**Paso 3.** En la segmentación de _Vendedor_ (Salesperson), selecciona **Anderson**.

![img225](../images/img225.png)

Verifica que, tanto la tabla dinámica (PivotTable) como el gráfico dinámico (PivotChart), se actualicen para mostrar las ventas totales de Anderson en Texas (TX) en el cuarto trimestre (Q4), observando que Anderson no tiene ventas en Nuevo México (NM).

### Resultado esperado:

![img226](../images/img226.png)

## [Menú principal](../README.md)

## [Práctica 5.3. Presentación de datos con gráficos dinámicos.](../Capítulo5/README_5.3.md)

## [Práctica 6.1. Consolidación de Ventas.](../Capítulo6/README_6.1.md)
