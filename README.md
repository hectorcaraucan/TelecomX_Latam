
# Telecom X - Análisis de evasión de clientes (Churn) 
Este proyecto forma parte del desafío "Churn de Clientes" para la empresa ficticia Telecom X. El objetivo principal es identificar, procesar y analizar los factores que influyen en la pérdida de clientes, proporcionando insights estratégicos basados en datos para reducir la tasa de evasión.
Objetivo del Proyecto
El análisis busca entender por qué los clientes cancelan sus servicios. Utilizando técnicas de ETL y Análisis Exploratorio de Datos (EDA), se identificaron patrones críticos relacionados con el tipo de contrato, la antigüedad del cliente y los cargos financieros.
Tecnologías utilizadas
•	Python 3.x
•	Pandas: Manipulación y limpieza de datos.
•	Matplotlib & Seaborn: Visualización de datos y análisis estadístico.
•	JSON: Procesamiento de estructuras de datos anidadas.
•	Google Colab: Entorno de desarrollo y ejecución.
Estructura del repositorio
•	TelecomX_Analysis.ipynb: Notebook principal con el código, visualizaciones y conclusiones.
•	TelecomX_Data.json: Dataset original con información demográfica, de servicios y facturación.
•	TelecomX_diccionario.md: Documentación de las variables y su significado técnico.
Instalación y uso
1.	Clonar el repositorio:
Bash
git clone https://github.com/hectorcaraucan/telecom-x-churn.git
2.	Entorno: Se recomienda ejecutar el archivo .ipynb en Google Colab.
3.	Carga de Datos: Es necesario subir los archivos TelecomX_Data.json y TelecomX_diccionario.md a la sesión de Colab antes de ejecutar las celdas de código.
Hallazgos Principales (Insights)
•	Tasa de abandono: La evasión actual se sitúa en un 26.5%.
•	Factor contrato: Los clientes con contratos "Mes a mes" representan el mayor volumen de fugas.
•	Riesgo por antigüedad: El periodo de mayor vulnerabilidad ocurre en los primeros 6 meses de relación con la empresa.
•	Soporte técnico: La falta de suscripción a soporte técnico adicional está fuertemente correlacionada con una mayor probabilidad de abandono.
Proceso de datos (Pipeline)
1.	Extracción: Carga de datos desde archivos JSON locales.
2.	Transformación: Aplanamiento de estructuras anidadas (Flattening) y conversión de tipos de datos de texto a numéricos (float/int).
3.	Limpieza: Eliminación de inconsistencias y registros sin etiquetas de Churn (aprox. 3% del dataset).
4.	Ingeniería de características: Creación de métricas de gasto diario y cuantificación de servicios contratados.
Contribuciones
Este proyecto fue desarrollado como parte de un proceso de aprendizaje y especialización en Ciencia de Datos. ¡Las sugerencias y comentarios son bienvenidos!

Autor: Héctor Rafael Caraucán Dávila











