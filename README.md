Análisis de Desempeño de Tiendas - Challenge Data Science

Este proyecto realiza un análisis exploratorio y comparativo de datos de ventas de cuatro tiendas diferentes. El objetivo es identificar patrones de consumo, eficiencia logística y satisfacción del cliente mediante el uso de Python y la librería Pandas.

📋 Descripción del Proyecto

El análisis se divide en cinco etapas críticas que permiten evaluar la salud financiera y operativa de cada sucursal. Se procesan archivos CSV alojados remotamente que contienen información sobre productos, categorías, precios, valoraciones y logística.

🛠️ Tecnologías Utilizadas

Python 3.x

Pandas: Manipulación y limpieza de datos.

Matplotlib: Visualización de resultados (gráficos de barras).

Google Colab / Jupyter Notebooks: Entorno de ejecución.

📊 Estructura de los Datos

Cada tienda cuenta con aproximadamente 2359 registros y 12 columnas, entre las que destacan:

Producto y Categoría del Producto

Precio y Costo de envío

Calificación (Escala 1-5)

Vendedor y Lugar de Compra

🚀 Etapas del Análisis

1. Análisis de Facturación

Se calcula el ingreso total por tienda.

Resultado: La Tienda 1 lidera con una facturación de $1,150,880,400.00.

Visualización: Gráfico de barras comparativo.

2. Ventas por Categoría

Identificación de la categoría con mayor volumen de transacciones en cada ubicación.

Hallazgo: La categoría "Muebles" es la más popular en las cuatro tiendas de forma unánime.

3. Calificación Promedio

Evaluación de la satisfacción del cliente mediante lógica condicional:

Excelente: $\ge 4.5$

Buena: $> 4.0$

Aceptable: $\ge 3.0$

Mala: $< 3.0$

Resultado: Las tiendas oscilan entre "Aceptable" y "Buena" (Promedio general ~4.0).

4. Productos Más y Menos Vendidos

Análisis de inventario para detectar productos estrella y productos de baja rotación.

Tienda 1: Microondas (Más vendido) vs. Auriculares (Menos vendido).

Tienda 4: Cama box (Más vendido) vs. Guitarra eléctrica (Menos vendido).

5. Envío Promedio

Cálculo del costo logístico por pedido para entender la eficiencia en entregas.

Dato Clave: La Tienda 4 posee el costo de envío promedio más bajo ($23,459.46).

📂 Cómo Ejecutar

Asegúrate de tener instaladas las dependencias:

pip install pandas matplotlib


Ejecuta el script principal para procesar las funciones de análisis de forma modular.

Proyecto desarrollado como parte del Challenge de Data Science Latam.
