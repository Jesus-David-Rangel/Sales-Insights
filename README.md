# Sales Insights

Este proyecto, **Sales Insights**, es un análisis de datos de ventas realizado sobre un dataset de transacciones comerciales. El objetivo principal es descubrir patrones de comportamiento, tendencias y oportunidades para la toma de decisiones en el ámbito comercial, utilizando herramientas de análisis y visualización de datos en Python.

## Descripción del Proyecto

El proyecto consiste en el procesamiento, limpieza, análisis exploratorio y visualización de un conjunto de datos de ventas. A través de este análisis, se busca obtener conclusiones relevantes respecto a:

- Las tendencias de ventas por producto y por mes.
- Los productos más vendidos y los menos populares.
- El comportamiento de las ventas según la ubicación geográfica.
- La identificación de patrones estacionales o picos de ventas.
- Recomendaciones para mejorar las estrategias comerciales.

## Tecnologías Utilizadas

- **Python 3.11**: Lenguaje principal para el análisis de datos.
- **Jupyter Notebook**: Entorno interactivo para el desarrollo y documentación del análisis.
- **Pandas**: Manipulación y limpieza de datos.
- **NumPy**: Soporte para operaciones numéricas.
- **Matplotlib** y **Seaborn**: Visualización de datos.
- **os**: Manejo de archivos.

## Metodología

1. **Carga y Limpieza de Datos:**  
   Se importó el dataset de ventas, verificando la presencia de valores nulos o inconsistencias. Se aplicaron técnicas de limpieza, como el formateo de fechas y la conversión de tipos de datos, para asegurar la calidad del análisis.

2. **Análisis Exploratorio:**  
   Se realizaron cálculos descriptivos (promedios, sumas, conteos) y se generaron visualizaciones para comprender la distribución de las ventas, identificar productos más y menos vendidos, y analizar las ventas por ciudad y por mes.

3. **Visualización de Resultados:**  
   Se crearon gráficas de barras, líneas y mapas de calor para ilustrar los hallazgos principales. Estas visualizaciones facilitaron la identificación de tendencias y patrones relevantes.

4. **Conclusiones y Recomendaciones:**  
   Se interpretaron los resultados obtenidos para generar recomendaciones prácticas orientadas a mejorar el rendimiento comercial.

## Resultados del Análisis

A continuación se presentan las conclusiones extraídas del análisis realizado sobre el dataset de ventas, utilizando datos reales y resultados de agrupaciones y visualizaciones:

### Estructura y Volumen del Dataset

- El dataset contiene **51,290 registros** y **17 columnas** con información sobre pedidos, clientes, productos, ventas, ganancias, descuentos, costos de envío y más.

### Desempeño por Categoría

- **Ventas Totales por Categoría:**
  - Technology: **$4,744,557.50**
  - Furniture: **$4,110,874.19**
  - Office Supplies: **$3,787,070.23**

- **Cantidad Total Vendida por Categoría:**
  - Office Supplies: **108,182** unidades
  - Technology: **35,176** unidades
  - Furniture: **34,954** unidades

- **Ganancia Total por Categoría:**
  - Technology: **$663,778.73**
  - Office Supplies: **$518,473.83**
  - Furniture: **$285,204.72**

- **Ganancia Promedio por Venta:**
  - Technology: **$65.45**
  - Furniture: **$28.88**
  - Office Supplies: **$16.58**

- **Venta Promedio por Pedido:**
  - Technology: **$467.86**
  - Furniture: **$416.25**
  - Office Supplies: **$121.10**

### Estacionalidad y Meses Clave

- El análisis mensual revela variaciones destacadas en el volumen de ventas por mes (ver gráfico de ventas por mes en el notebook).
- Se observa una acumulación significativa de ventas en determinados meses, lo que sugiere estacionalidad y posibles campañas exitosas.
- Los meses con mayores ventas pueden identificarse claramente en la visualización (consultar gráfico en el notebook para ver los picos exactos).

### Patrones por Subcategoría

- Las subcategorías con mayor cantidad de productos vendidos destacan en el análisis, permitiendo identificar los artículos más populares para enfocar inventario y promociones.
- Consulta el gráfico de barras horizontal para ver el ranking exacto de subcategorías.

### Relación de Variables

- Existe una relación visible (aunque dispersa) entre el **descuento aplicado y la ganancia**: descuentos elevados tienden a reducir la rentabilidad, como muestra el gráfico de dispersión.
- También se analiza la relación entre el **costo de envío y la ganancia**, útil para identificar oportunidades de optimización logística.

### Recomendaciones y Oportunidades

- **Enfocar estrategias de promoción e inventario** en Technology y Office Supplies, por su volumen y rentabilidad.
- Ajustar políticas de descuento para evitar erosión de márgenes, especialmente en categorías de baja ganancia promedio.
- Profundizar en la estacionalidad detectada para lanzar campañas específicas en los meses de mayor venta.
- Revisar costos logísticos, ya que el costo de envío impacta de forma variable en la ganancia.

> Para visualizar los gráficos y detalles completos, consulta el notebook original:
> [sales-analysis.ipynb (GitHub)](https://github.com/Jesus-David-Silva-Rangel-19/Sales-Insights/blob/b52e148483bf72ae4ac2e258b20b0eaa6284751e/sales-analysis.ipynb)

## ¿Cómo usar este proyecto?

1. Clona el repositorio.
2. Abre el archivo `sales-analysis.ipynb` en Jupyter Notebook.
3. Asegúrate de contar con las dependencias mencionadas instaladas.
4. Ejecuta las celdas del notebook para reproducir el análisis y visualizar los resultados.

## Conclusión

Este proyecto es un ejemplo práctico de cómo el análisis de datos puede ofrecer ventajas competitivas en el ámbito comercial. A través de técnicas de ciencia de datos y visualización, es posible transformar información bruta en conocimiento útil para la toma de decisiones empresariales.

Desarrollado por [Jesus-David-Silva-Rangel-19](https://github.com/Jesus-David-Silva-Rangel-19)
