# Tablero de Control con Dash y Plotly

Este proyecto es una aplicación interactiva de un **Tablero de Control** desarrollado con **Dash** y **Plotly**. El tablero permite visualizar datos de ventas de una tienda a través de diferentes gráficos y tablas, facilitando el análisis de información clave como ventas por provincia y segmento de cliente.

## Características

- **Visualización de Datos**: Se ofrece una tabla con los registros de ventas, así como diferentes gráficos interactivos:
  - Tabla de datos completa
  - Histograma que muestra el promedio de ventas por provincia
  - Gráfico de dispersión de ventas por fecha de pedido
  - Gráfico de barras apiladas que compara las ventas por provincia y segmento de cliente
- **Interactividad**: Los usuarios pueden cambiar entre distintas visualizaciones mediante pestañas dinámicas.

## Tecnologías

- **Framework**: Dash
- **Gráficos**: Plotly
- **Lenguaje**: Python
- **Datos**: Archivo CSV con datos de ventas de una tienda

## Instalación

1. Clona este repositorio.
2. Instala las dependencias necesarias:
   ```bash
   pip install dash plotly pandas
   ```
3. Ejecuta la aplicación:
   ```bash
   python app.py
   ```

## Datos

El archivo `superstore.csv` contiene información sobre ventas, con columnas como `Province` (provincia), `Sales` (ventas), `Customer Segment` (segmento de cliente), `Order Date` (fecha de pedido) y `Ship Date` (fecha de envío). La aplicación agrupa y analiza estos datos para generar las visualizaciones.
