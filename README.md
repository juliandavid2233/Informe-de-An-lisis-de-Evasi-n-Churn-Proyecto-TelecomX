# 📊 Análisis de Retención de Clientes (Churn) - TelecomX

Este proyecto aplica técnicas de **Ciencia de Datos** y **Análisis Exploratorio (EDA)** para identificar los motivos por los cuales los clientes de una empresa de telecomunicaciones cancelan sus servicios.

## 🎯 Objetivo del Proyecto
El propósito principal es analizar el comportamiento de los usuarios, procesar datos estructurados en JSON y proponer estrategias basadas en datos para reducir la tasa de evasión (Churn), la cual se sitúa actualmente en un **26%**.

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** * `Pandas` (Limpieza y manipulación de datos)
    * `Seaborn` & `Matplotlib` (Visualización estadística)
    * `JSON` (Procesamiento de fuentes externas)

## 🧹 Proceso de Datos
1. **Limpieza:** Eliminación del 3% de registros con datos nulos/vacíos en la variable objetivo.
2. **Ingeniería de Características:** Creación de métricas como `Cargo_Diario` y `Total_Servicios` para un análisis más profundo.
3. **Estandarización:** Traducción de variables al español y encodificación binaria (0 y 1) de categorías textuales.

## 📈 Hallazgos Clave (Insights)
* **Factor Antigüedad:** Los clientes con menos de **12 meses** de permanencia representan el mayor volumen de fugas.
* **Factor Precio:** Existe una correlación positiva entre facturas altas y la probabilidad de abandono. Los clientes con cargos mensuales superiores a la media son un segmento crítico.
* **Tipo de Contrato:** Los contratos "Mes a Mes" tienen una tasa de rotación significativamente más alta que los contratos a largo plazo.



## 💡 Recomendaciones Estratégicas
* **Fidelización Temprana:** Implementar campañas de retención específicas para el primer semestre del cliente.
* **Incentivos de Migración:** Promover la transición de planes mensuales a contratos anuales mediante beneficios en servicios de valor agregado (Streaming).
* **Optimización de Planes:** Revisar la competitividad de los precios en los segmentos de alto consumo.

## 🚀 Cómo ejecutar este proyecto
1. Clona el repositorio: `git clone https://github.com/tu-usuario/telecom-churn-analysis.git`
2. Instala las dependencias: `pip install pandas seaborn matplotlib`
3. Ejecuta el notebook: `jupyter notebook` o abre el archivo en **Google Colab**.

---
**Autora:** Jessica Daniela  
**Rol:** Data Analyst / Data Scientist en formación
