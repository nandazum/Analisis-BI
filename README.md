El presente proyecto tiene como objetivo analizar el desempeño comercial mediante la comparación entre ventas reales y metas establecidas, utilizando herramientas de Business Intelligence en Power BI.

1. Obtención de datos
Se integraron múltiples fuentes de datos, específicamente un archivo Excel con información de ventas y un archivo CSV con metas comerciales. Esto permitió contar con distintas perspectivas del negocio para su análisis.

2. Preparación de datos (Power Query)
Se realizó un proceso de limpieza y transformación de datos para asegurar su calidad. Entre las principales acciones se incluyen:

-Corrección de nombres de columnas para estandarización.
-Eliminación de espacios en blanco y caracteres erróneos.
-Unificación de formatos de texto (mayúsculas/minúsculas).
-Conversión de tipos de datos (especialmente fechas y valores numéricos).
-Manejo de valores nulos y eliminación de errores.
**Este proceso permitió contar con datos consistentes y listos para el análisis.

3. Modelado de datos
Se construyó un modelo de datos tipo estrella, incorporando una tabla de calendario para facilitar el análisis temporal.
Las tablas de ventas y metas fueron relacionadas a través de la dimensión de fechas, evitando relaciones directas entre tablas de hechos y asegurando una correcta propagación de filtros.

4. Creación de medidas (DAX)
Se desarrollaron medidas para el cálculo de indicadores clave (KPIs), tales como:

-Ventas totales
-Metas totales
-Porcentaje de cumplimiento
-Ventas acumuladas
**Estas medidas permiten analizar dinámicamente el desempeño comercial en distintos niveles de detalle.

5. Visualización de datos
Se diseñó un reporte interactivo que incluye:

-Gráficos de barras para comparar ventas vs metas
-Tarjetas con indicadores clave
-Gráfico de tendencia de ventas acumuladas
-Segmentadores para filtrar por región, producto y período

**Esto facilita una exploración dinámica y comprensible de la información.

6. Dashboard final
Se organizó la información en un dashboard claro y estructurado, incorporando un resumen ejecutivo que permite interpretar rápidamente los resultados y apoyar la toma de decisiones.

**Análisis general
Durante el período analizado, las ventas presentan un comportamiento variable en relación con las metas establecidas, evidenciando meses con bajo cumplimiento y otros con sobrecumplimiento. El total de ventas anual alcanza M$ 31.231, concentrándose principalmente en el primer cuatrimestre, donde se registra una recaudación de M$ 28.072. Este período también coincide con los únicos meses en que se cumplen las metas comerciales, mientras que en los meses posteriores el desempeño tiende a ser más irregular. A pesar de esta variabilidad, se identifica una tendencia general de crecimiento en las ventas.

**Recomendaciones
Revisar la estrategia comercial en los meses posteriores al primer cuatrimestre, donde se observa una disminución en el cumplimiento de metas.
Identificar factores de éxito del primer cuatrimestre, con el fin de replicarlos en otros períodos (por ejemplo, campañas, promociones o estacionalidad).
Fortalecer el seguimiento de indicadores de desempeño, utilizando dashboards como herramienta de monitoreo continuo.
Mejorar la calidad y consistencia de los datos de origen, ya que la presencia de datos erróneos o inconsistentes puede afectar el análisis.
