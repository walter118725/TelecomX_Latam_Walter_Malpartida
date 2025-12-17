# TelecomX_Latam_Walter_Malpartida
Análisis de abandono de TelecomX
Este proyecto corresponde a un análisis completo de evasión de clientes (Churn) para la empresa TelecomX LATAM , desarrollado como parte de un desafío de Data Science.

El objetivo es entender los factores que influyen en la cancelación del servicio , generar insights accionables y proponer recomendaciones estratégicas para reducir la evasión .

📂 Contenido del Repositorio
TelecomX_LATAM.ipynb→ Cuaderno con todo el flujo de trabajo y el informe final.
informe_figs/→ Carpeta con las imágenes utilizadas en el informe.
TelecomX_Data.json→ Conjunto de datos original en formato JSON.
TelecomX_Data_Estandarizado.csv→ Conjunto de datos limpio y estandarizado para el análisis.
README.md→ Este archivo de documentación.
🚀 Flujo de Trabajo
Carga de Datos

Se importaron los registros de clientes desde un archivo JSON (API simulada).
Conversión a un DataFramede pandas.
Limpieza y tratamiento

Normalización de cadenas de texto.
Estandarización de variables binarias ( Yes/No → 1/0).
Traducción de columnas al español.
Creación de la columna CargosDiarios.
Análisis Exploratorio (EDA)

Estadísticas descriptivas (media, mediana, desviación estándar).
Distribución de evasión ( Evasion).
Comparaciones por variables categóricas (género, contrato, método de pago).
Comparaciones por variables numéricas (tenure, cargos mensuales/totales).
Correlación de variables numéricas con evasión.
Informe final

Incluido dentro del notebook.
Contiene:
Introducción
Limpieza y tratamiento de datos
Análisis exploratorio con gráficos
Conclusiones y perspectivas
Recomendaciones estratégicas
📊 Principales Insights
Los clientes con contratos mensuales muestran una tasa de evasión significativamente mayor.
La antigüedad baja (primeros meses) está asociada a mayor cancelación.
Servicios adicionales como Seguridad Online y Soporte Técnico reducen la probabilidad de evasión.
Los clientes con cargos mensuales altos presentan mayor riesgo de baja.
🧭 Recomendaciones
Incentivar contratos anuales/bianuales mediante descuentos o beneficios.
Programas de onboarding y retención temprana (primeros 3–6 meses).
Promoción de servicios adicionales de seguridad y soporte técnico .
Alertas y retención proactiva para clientes con cargas elevadas.
Optimización de métodos de pago y facturación electrónica .
🛠️ Tecnologías Utilizadas
Python 3.10+
Pandas → Manipulación y análisis de datos
Matplotlib → Visualización de datos
NumPy → Cálculos numéricos
Jupyter Notebook → Desarrollo interactivo
