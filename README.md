# Challenge1_Tiendas

## Descripción

Este proyecto tiene como objetivo analizar los datos de ventas, envío y calificaciones de distintas tiendas pertenecientes al señor Juan. A partir de los datos de ingresos totales, costos de envío y ponderación de satisfacción del cliente, se generan métricas clave para evaluar el desempeño de cada tienda y tomar decisiones estratégicas (por ejemplo, cuál tienda podría venderse).

## Estructura del repositorio

* `AluraStoreLatam.ipynb` : Notebook de análisis en Jupyter que carga los datos, realiza el cómputo de ingresos, costos, promedios de calificación, ganancias netas y presenta conclusiones.

## Datos utilizados

Se trabajaron los siguientes indicadores por tienda:

1. **Ingresos totales**

   * Tienda 1: 1.150.880.400
   * Tienda 2: 1.116.343.500
   * Tienda 3: 1.098.019.600
   * Tienda 4: 1.038.375.700
2. **Costo de envío total**

   * Tienda 1: 61.377.900
   * Tienda 2: 59.485.100
   * Tienda 3: 58.516.600
   * Tienda 4: 55.317.400
3. **Promedio de calificación (satisfacción del cliente)**

   * Tienda 1: 3,98
   * Tienda 2: 4,04
   * Tienda 3: 4,05
   * Tienda 4: 4,00
4. **Ganancias netas** = Ingresos − Costo de envío

   * Tienda 1: 1.089.502.500
   * Tienda 2: 1.056.858.400
   * Tienda 3: 1.039.503.000
   * Tienda 4: 983.058.300

## Metodología

* Se calculan las métricas de ingresos, costo de envío y calificaciones.
* Se calcula la ganancia neta para cada tienda restando los costos de envío de los ingresos.
* Se analizan los resultados para identificar fortalezas, debilidades y posibles acciones estratégicas (como la venta de una tienda).

## Resultados clave

* La Tienda 1 presenta la **mayor ganancia neta**, aunque su promedio de calificación (3,98) es inferior al de las tiendas 2 y 3.
* La Tienda 3, aunque no tiene la mayor ganancia, registra la **mejor calificación** (4,05), lo que indica un mayor nivel de satisfacción de cliente.
* La Tienda 4 muestra la **menor ganancia** del grupo (983.058.300) y una calificación de 4,00, lo cual la posiciona como la opción menos rentable dentro del conjunto analizado.

## Conclusión y Recomendación

Con base en los datos, se recomienda que se considere la **venta de la Tienda 4**, pues es la menos rentable y permite liberar recursos o centrarse en las otras tres tiendas con mejor desempeño. Mantener las tiendas 1, 2 y 3 ofrece mayor potencial tanto desde el punto de vista financiero como de satisfacción del cliente.

## Cómo reproducir el análisis

1. Descarga o copia este repositorio:
2. Asegúrate de poder abrir el archivo python.`AluraStoreLatam.ipynb`.
4. Ejecuta todas las celdas.
5. Puedes modificar los datos o parámetros para experimentar con diferentes escenarios.

## Contacto
Para dudas, sugerencias o contribuciones, puedes contactar al autor del repositorio (usuario: jonatanbejarano) mediante GitHub.
