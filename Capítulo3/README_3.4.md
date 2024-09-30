# Práctica 3.4. Aplicando validación de errores.

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Identificar y corregir datos inválidos utilizando herramientas de validación en Excel. <br>
- Gestionar y comprender configuraciones de validación de datos. <br>
- Detectar y solucionar errores en fórmulas utilizando la comprobación de errores de Excel.

## Duración aproximada:
- 10 minutos.

## Instrucciones:

### Escenario:
Continuando en tu rol como gerente financiero para Develetech Industries, has hecho todo lo posible por verificar que los datos ingresados para cada región sean correctos. Ahora, deseas revisar datos inválidos y cualquier problema con las fórmulas. Para ello, decides señalar los datos inválidos y corregir las entradas incorrectas.

**Nota:** Continúa en el archivo llamado *Regional expenses*.

### Tarea 1. Buscar entradas de datos inválidos en la hoja de trabajo de Europa.

**Paso 1.** Selecciona la hoja de trabajo *European*.

**Paso 2.** En la pestaña _Datos_, selecciona la flecha desplegable en el botón _Validación de datos_ y después **Rodear datos inválidos**.

![Img111](../images/img111.png)

**Nota:** Verifica que haya dos celdas que contienen datos inválidos.

![Img112](../images/img112.png)

### Tarea 2. Corregir los datos inválidos en la hoja de trabajo.

**Paso 1.** Selecciona la celda **B6** e ingresa `280`.

##### Nota: Después de ingresar el valor correcto, el círculo de datos inválidos debería desaparecer. En caso de que esto no ocurra, en esta actividad elimina los círculos de validación más adelante.

**Paso 2.** Selecciona la celda **B3** y haz clic en la flecha desplegable que aparece a la derecha de la celda.

**Paso 3.** Selecciona _Jerald Maldonado_.

##### Nota: Los ajustes de validación de datos de _Mensaje de entrada_ y _Alerta de error_ en la hoja de trabajo Europea no son los mismos que los ajustes de validación de datos en la hoja de trabajo de América del Norte.

![Img113](../images/img113.png)

**Paso 4.** En la pestaña _Datos_, selecciona la flecha desplegable en el botón _Validación de datos_ y luego da clic en **Borrar círculos de validación**.

![Img114](../images/img114.png)

### Tarea 3. Revisar la hoja de trabajo en busca de errores en las fórmulas.

**Paso 1.**  Navega a la celda A1.

**Paso 2.** Selecciona _Fórmulas > Comprobación de Errores_.

**Nota:** Verifica que el cuadro de diálogo de _Comprobación de Errores_ encontró un error en la celda B10.

![Img115](../images/img115.png)

**Paso 3.** Selecciona _Modificiar en la Barra de Fórmulas_.

**Paso 4.** Corrige el error escribiendo un dos puntos (:) entre el rango B6. La fórmula debe ser:

```
=SUMA(B6:B9)
```

![Img116](../images/img116.png)

**Paso 5.** Presiona **Enter**.

**Paso 6.**  En el cuadro de diálogo _Revisión de Errores_, selecciona **Reanudar**.

**Paso 7.**  En el cuadro de diálogo de _Microsoft Excel_, verifica que la revisión de errores se ha completado y selecciona **OK**.

![Img117](../images/img117.png)

### Resultado esperado:

![Img118](../images/img118.png)

## [Menú principal](../README.md)

## [Práctica 3.3. Aplicando validación de datos.](../Capítulo3/README_3.3.md)

## [Práctica 4.1. Trabajando con Funciones Lógicas.](../Capítulo4/README_4.1.md)
