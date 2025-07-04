# Alura Challenge - Análisis de Tiendas con Python Nativo

Este proyecto es una implementación de conceptos nativos de Python para el análisis de datos en el Challenge Alura Store. Utiliza cuatro bases de datos, cada una correspondiente a una tienda ficticia de la cadena Alura Store, las cuales contienen información estructurada en columnas como: Producto, Categoría del Producto, Precio, Costo de envío, Fecha de Compra, Vendedor, Lugar de Compra, Calificación, Método de pago, Cantidad de cuotas, lat y lon. A partir de estos datos, se analiza el rendimiento comercial, logístico y la satisfacción del cliente, con el objetivo de identificar cuál de las tiendas presenta el desempeño más bajo y recomendar su venta para financiar un nuevo emprendimiento

---

## Estado del proyecto: Finalizado.

---

## Funcionalidades implementadas:

- **Cálculo de ingresos totales por tienda**  
  Se suman todos los precios de venta para obtener la facturación de cada tienda.

- **Categorización y conteo de productos vendidos**  
  Agrupación de productos por tipo y conteo usando listas y diccionarios nativos.

- **Cálculo de valoración promedio por tienda**  
  Promedio simple de las calificaciones otorgadas por los clientes.

- **Detección de productos más y menos vendidos**  
  Se determina cuál categoría de productos se vendió más y cuál menos por tienda.

- **Cálculo del costo promedio de envío por tienda**  
  Promedio de los valores de la columna "Costo de envío".

- **Visualización de datos con Matplotlib**  
  Se generan gráficos de barra, línea y pastel para ilustrar los hallazgos.

- **Recomendación final basada en datos**  
  Se genera un informe en lenguaje natural recomendando la venta de la tienda menos eficiente.

---

## Estructura del código:

El código se encuentra en un archivo `.ipynb` de Google Colab, y se organiza de la siguiente manera:

- **Variables y estructuras principales**:  
  Se utilizan listas, diccionarios y estructuras de control como `for`, `if`, `zip`, `enumerate`, etc.

- **Funciones definidas**:
  - `ventas_por_categoria(tienda)`: agrupa y cuenta productos por categoría.
  - `Productos_mas_y_menos_vendidos(tienda)`: determina los productos por máximo y mínimo volumen de ventas.
  - Lógica con `for` y `print` para calcular y mostrar el costo promedio de envíos, promedio de calificaciones y total de facturación por tienda.

- **Visualizaciones**:
  - `matplotlib.pyplot` se usa para representar los ingresos, calificaciones y costos de envío.

- **Informe final**:
  - Redacción en Markdown explicando la recomendación basada en los resultados.

---

## Cómo ejecutar el proyecto:

1. Abre el archivo del proyecto en [Google Colab](https://colab.research.google.com/).
2. Ejecuta las celdas en orden para calcular las métricas de cada tienda.
3. Observa los gráficos generados que comparan rendimiento, calificaciones y logística.
4. Lee el informe final que recomienda qué tienda vender.

---

## Requisitos:

- Python 3.x (Google Colab)
- Biblioteca `matplotlib` para gráficos

---

## Resultado:

Tras el análisis completo, se concluye que **la Tienda 4** es la menos eficiente, ya que tiene el menor ingreso, ventas bajas en categorías clave y una calificación promedio ligeramente inferior, aunque con un costo de envío más bajo. Por lo tanto, se recomienda vender esta tienda.