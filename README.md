# Desafío Alura Store - Análisis de Datos

## 📋 Descripción del Proyecto

Este proyecto forma parte del desafío de Alura para la especialización en Data Science. El objetivo es realizar un análisis exhaustivo de datos de ventas de 4 tiendas diferentes utilizando Python y técnicas de análisis de datos. 

## 🎯 Objetivos

Analizar el rendimiento de 4 tiendas de e-commerce en Colombia, evaluando métricas clave como facturación, productos más vendidos, satisfacción del cliente y costos de envío.

## 📊 Dataset

El proyecto utiliza 4 archivos CSV ubicados en la carpeta `base-de-datos-challenge1-latam/`:
- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

### Estructura de los datos: 
Cada dataset contiene las siguientes columnas:
- **Producto**: Nombre del producto vendido
- **Categoría del Producto**: Clasificación del producto (Electrónicos, Muebles, Juguetes, Electrodomésticos, Deportes y diversión)
- **Precio**: Precio de venta del producto (COP)
- **Costo de envío**: Costo del envío (COP)
- **Fecha de Compra**: Fecha de la transacción
- **Vendedor**: Nombre del vendedor
- **Lugar de Compra**: Ciudad colombiana donde se realizó la compra
- **Calificación**: Puntuación del cliente (1-5)
- **Método de pago**: Forma de pago utilizada
- **Cantidad de cuotas**: Número de cuotas para el pago
- **lat/lon**: Coordenadas geográficas

## 🔍 Análisis Realizados

### 1. Análisis de Facturación
Cálculo del ingreso total por tienda:
- **Tienda 1**: $1,150,880,400 COP
- **Tienda 2**: $1,116,343,500 COP
- **Tienda 3**: $1,098,019,600 COP
- **Tienda 4**: $1,038,375,700 COP

**Resultado**: La Tienda 1 es la que genera mayor facturación. 

### 2. Ventas por Categoría
Identificación de las categorías más vendidas en cada tienda:
- **Categoría líder**: Muebles (presente en todas las tiendas)
- **Segunda categoría**: Electrónicos
- Las categorías principales son consistentes entre tiendas

### 3. Calificación Promedio
Evaluación de la satisfacción del cliente: 
- **Tienda 1**: 3.98 ⭐
- **Tienda 2**: 4.04 ⭐
- **Tienda 3**: 4.05 ⭐
- **Tienda 4**: 4.00 ⭐

**Resultado**: La Tienda 3 tiene la mejor calificación promedio.

### 4. Productos Más y Menos Vendidos
**Productos más vendidos por tienda**:
- Tienda 1: Microondas, TV LED UHD 4K, Armario
- Tienda 2: Iniciando en programación, Microondas, Batería
- Tienda 3: Kit de bancas, Mesa de comedor, Cama king
- Tienda 4: Cama box, Cubertería, Dashboards con Power BI

**Productos menos vendidos**:  Varían por tienda, incluyendo guitarras, auriculares y algunos electrodomésticos.

### 5. Análisis de Costos de Envío
Cálculo del costo promedio de envío por tienda para optimizar la logística. 

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas**:  Manipulación y análisis de datos
- **Matplotlib**:  Visualización de datos
- **Jupyter Notebook**: Desarrollo interactivo

## 📁 Estructura del Proyecto

```
desafio-alura-store/
├── README.md
├── AluraStoreLatam.ipynb
└── base-de-datos-challenge1-latam/
    ├── tienda_1 .csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

## 🚀 Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**: 
   ```bash
   git clone https://github.com/RazorZ7X/desafio-alura-store.git
   cd desafio-alura-store
   ```

2. **Instalar dependencias**:
   ```bash
   pip install pandas matplotlib jupyter
   ```

3. **Abrir el notebook**:
   ```bash
   jupyter notebook AluraStoreLatam.ipynb
   ```

## 📈 Visualizaciones

El proyecto incluye visualizaciones como:
- Gráficos de barras para comparar facturación entre tiendas
- Gráficos de torta para distribución de calificaciones
- Gráficos agrupados para ventas por categoría
- Comparativas de productos más/menos vendidos

## 💡 Insights Principales

1. La Tienda 1 lidera en facturación pero no en satisfacción del cliente
2. Los muebles son la categoría más vendida en todas las tiendas
3. Existe una correlación entre productos más vendidos y la categoría dominante
4. Las calificaciones son consistentemente altas (>3.9) en todas las tiendas
5. Productos educativos (cursos de programación) tienen buena demanda

## 📝 Licencia

Este proyecto es parte de un desafío educativo de Alura Latam.