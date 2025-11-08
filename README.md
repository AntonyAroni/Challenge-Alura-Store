AluraStore Latam — Análisis Exploratorio de Ventas y Recomendación Comercial

Este proyecto realiza un análisis exploratorio completo de datos de ventas provenientes de cuatro tiendas que forman parte de la cadena AluraStore.
El objetivo principal es comparar el desempeño de las tiendas y recomendar a cuál de ellas debería vender sus productos un proveedor externo (el Sr. Juan), basándose en indicadores cuantitativos y cualitativos.

--------------------------------------------------------------------------------

OBJETIVOS DEL PROYECTO

- Procesar y limpiar los datos de ventas de las cuatro tiendas.
- Analizar métricas clave como:
  - Ingresos totales
  - Calificaciones promedio de clientes
  - Costo de envío promedio
  - Productos más y menos vendidos
- Identificar patrones de ventas y diferencias estratégicas entre tiendas.
- Realizar visualizaciones para apoyar el análisis.
- Generar una recomendación final basada en evidencia.

--------------------------------------------------------------------------------

ESTRUCTURA DEL NOTEBOOK

1. Importación y carga de datos
2. Análisis descriptivo de cada tienda
3. Comparación de métricas globales
4. Visualizaciones (barras, dispersión, mapas de calor)
5. Identificación de productos más y menos vendidos
6. Actividad Extra (Opcional): Análisis geográfico con lat/lon
7. Conclusión y recomendación final

--------------------------------------------------------------------------------

CONOCIMIENTOS APLICADOS

- Pandas — Manipulación y agrupación de datos
- Matplotlib — Gráficas comparativas y mapas de dispersión
- Estadística Descriptiva — Promedios, recuentos y ranking de productos
- Análisis Comparativo — Evaluación entre tiendas según métricas clave
- Clusterización (Opcional) — Segmentación geográfica con K-Means

--------------------------------------------------------------------------------

DATOS UTILIZADOS

Columnas principales:

Producto — Nombre del producto vendido
Categoría del Producto — Tipo de producto
Precio — Ingreso generado por la venta
Costo de envío — Costo logístico del despacho
Calificación — Evaluación del cliente (1 a 5)
lat / lon — Ubicación geográfica de la venta (actividad extra)

--------------------------------------------------------------------------------

CÓMO EJECUTAR EL PROYECTO

Google Colab (recomendado):
1) Subir el archivo .ipynb a Google Colab
2) Ejecutar las celdas en orden
3) Instalar librerías si es necesario:
   pip install pandas matplotlib seaborn folium scikit-learn

Local:
   git clone <URL_DEL_REPOSITORIO>
   pip install -r requirements.txt
   jupyter notebook

--------------------------------------------------------------------------------

VISUALIZACIONES INCLUIDAS

- Gráficas de barras comparativas
- Gráficas de dispersión
- Mapas de calor geográfico (Heatmaps)
- Rankings de productos más y menos vendidos

--------------------------------------------------------------------------------

ACTIVIDAD EXTRA (OPCIONAL)

Se analiza la distribución espacial de las ventas mediante:
- Scatter Plot de coordenadas (lat, lon)
- Heatmaps de concentración de ventas
- Clusterización geográfica con K-Means (opcional)

--------------------------------------------------------------------------------

RESULTADO Y CONCLUSIÓN

Se recomienda la tienda ideal para el proveedor basada en:
- Desempeño comercial (ingresos totales)
- Satisfacción del cliente (calificación promedio)
- Eficiencia logística (costo de envío promedio)
- Estabilidad en la demanda (productos más vendidos)

--------------------------------------------------------------------------------

AUTOR
Antony Aroni
Proyecto desarrollado como parte del programa “Data Science - Alura + Oracle”.
