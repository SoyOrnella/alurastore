# alurastore
challenge Alura Store para ONE
# Análisis de Ventas – Alura Store LATAM

## Propósito del Proyecto

Este proyecto tiene como objetivo analizar el rendimiento de las tiendas de **Alura Store LATAM** para ayudar al señor Juan a tomar una decisión estratégica: determinar cuál de las cuatro tiendas tiene el menor desempeño y debería ser vendida para invertir en un nuevo negocio.

El análisis se realizó utilizando **Python y bibliotecas de análisis de datos**, explorando métricas clave de ventas, desempeño y satisfacción del cliente.

---

# Análisis Realizados

Durante el proyecto se analizaron cinco aspectos principales:

### Facturación total

Se calculó el monto total de ventas considerando el precio de los productos y el costo de envío.

### Ventas por categoría

Se analizaron las categorías de productos para identificar cuáles generan mayor volumen de ventas.

### Calificación promedio de clientes

Se evaluó el nivel de satisfacción de los clientes mediante el promedio de calificaciones otorgadas.

### Productos más y menos vendidos

Se identificaron los productos con mayor y menor volumen de ventas.

### Costo promedio de envío

Se analizó el costo de envío promedio según el lugar de compra.

---

# Estructura del Proyecto

```
alura-store-analysis
│
├── AluraStoreLatam.ipynb   # Notebook principal con el análisis
├── README.md               # Documentación del proyecto
```

El análisis se realizó en **Google Colab**, utilizando archivos CSV almacenados en GitHub.

---

# Tecnologías Utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* GitHub

---

# Ejemplos de Visualizaciones

Durante el análisis se generaron gráficos como:

* Ventas totales por categoría
* Productos más y menos vendidos
* Costo de envío promedio
* Comparación de ventas

Estas visualizaciones permiten identificar patrones de consumo y desempeño entre las tiendas.

---

# Principales Insights

Al analizar los datos se observaron algunos patrones importantes:

* Las categorías **Electrónicos** y **Electrodomésticos** generan la mayor facturación.
* Algunos productos presentan una alta concentración de ventas, destacándose como los más populares.
* La calificación promedio de los clientes es **4.01**, lo que indica una buena percepción general de las tiendas.
* El costo de envío varía significativamente según la ciudad de compra.

Estos indicadores permiten evaluar el rendimiento de cada tienda y detectar oportunidades de mejora.

---

# Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/alura-store-analysis.git
```

2. Abrir el archivo **.ipynb** en **Google Colab** o Jupyter Notebook.

3. Ejecutar las celdas para reproducir el análisis.

Los datos se cargan directamente desde GitHub utilizando `pandas.read_csv()`.

---

# Autora

Proyecto realizado por **Ornella Mazzoni** como parte del desafío de **Data Science de Alura Latam**.

---

# Conclusión

El análisis de datos permite comprender el rendimiento de las tiendas de Alura Store a través de métricas de ventas, categorías de productos y satisfacción del cliente.

A partir de estos resultados, el señor Juan puede tomar una decisión estratégica basada en datos para optimizar sus inversiones y fortalecer su negocio.
