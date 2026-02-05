# 📦Análisis de gestión y optimización de inventario

Estudio de caso: Bibitor, LLC (caso académico de PwC)

## 📌Descripción del proyecto

Este proyecto realiza un análisis integral de inventarios, ventas y compras para una empresa minorista de vinos y licores basada en un caso de estudio académico desarrollado por PwC.

El objetivo principal es optimizar la gestión de inventario, reducir costos operativos y mejorar la toma de decisiones mediante técnicas de análisis de datos, visualización y métricas de supply chain.

El análisis se basa en datos reales simulados de Bibitor, LLC, una cadena de licorerías con más de 80 tiendas y ventas anuales superiores a los USD 450 millones.

## 🎯Objetivos del análisis

- Determinar niveles óptimos de inventario
- Reducir desabastecimientos y exceso de stock
  
- Analizar:
  - Rotación de inventario
  - Stock de seguridad
  - Punto de reorden
  - Lead Time (tiempo de entrega)

- Identificar productos:
  - Más vendidos
  - De lento movimiento
  - Con sobrestock
  - Optimizar decisiones de compra y reposición
  - Proponer una estrategia sostenible de gestión de inventario

## 🗂️Conjuntos de datos utilizados

El proyecto utiliza 6 datasets principales (CSV):

- BegInvFINAL12312016.csv – Inventario inicial
- EndInvFINAL12312016.csv – Inventario final
- SalesFINAL12312016.csv – Ventas
- PurchasesFINAL12312016.csv – Compras
- InvoicePurchases12312016.csv – Facturas de compra
- 2017PurchasePricesDec.csv – Precios de compra

Los datos incluyen millones de registros, lo que hace inviable el análisis mediante hojas de cálculo tradicionales.

## 🛠️Tecnologías utilizadas

- Python
- Pandas – manipulación y limpieza de datos
- NumPy – cálculos numéricos
- Matplotlib & Seaborn – visualización de datos
- Regex – estandarización de formatos
- EDA (Exploratory Data Analysis)

## 🔍Metodología

1️⃣ Exploración y limpieza de datos

- Identificación de valores faltantes y duplicados
- Estandarización de formatos de fecha
- Normalización de unidades de volumen (litros)
- Limpieza de inconsistencias en descripciones y proveedores

2️⃣ Análisis de inventario

- Inventario inicial vs final
- Productos con mayor y menor stock
- Identificación de inventario obsoleto
- Análisis de rotación

3️⃣ Análisis de ventas

- Productos más vendidos y de bajo movimiento
- Tendencias temporales de ventas
- Velocidad de ventas por producto

4️⃣ Análisis de compras y proveedores

Proveedores principales por volumen y costo

Duración promedio de suministro

Duración promedio de pago

Distribución de costos entre proveedores

5️⃣ Optimización de inventario

Cálculo de:
  -Stock de seguridad
  - Nivel de stock óptimo
  - Cantidades de reorden
  - Identificación de productos prioritarios para reposición
  - Visualización comparativa de stock actual vs recomendado

## 📊Resultados clave

- Smirnoff 80 Proof lidera en ventas, velocidad y stock recomendado
- Lead Time promedio ≈ 8 días
- Duración promedio de pago ≈ 36 días
- Proveedor dominante: DIAGEO NORTH AMERICA INC
- Detección de:
  - Exceso de stock en productos específicos
  - Productos con inventario cero persistente
  - Necesidad de reorden inmediato en productos clave

## 📈Visualizaciones incluidas

- Histogramas de ventas, stock y lead time
- Gráficos de barras (ventas, proveedores, reposición)
- Comparativas stock actual vs recomendado
- Distribuciones de stock de seguridad
- Tendencias temporales

## 🎓Contexto académico

Este proyecto está diseñado para:

- Cursos de Data Analytics
- Accounting Information Systems (AIS)
- Auditoría avanzada
- Supply Chain & Inventory Management
- Desarrollado como caso práctico universitario (PwC).

## 🚀Posibles mejoras futuras

- Implementación de ABC Analysis
- Modelos de forecasting de demanda
- Automatización con Streamlit / Dash
- Integración con bases de datos SQL
- Simulación de escenarios de inventario
