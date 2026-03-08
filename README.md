🛠️ Tecnologías Utilizadas
Python 3.x: Procesamiento y limpieza de datos.
Pandas & NumPy: Manipulación de estructuras de datos y generación de datos sintéticos.
Matplotlib & Seaborn: Visualización de tendencias y distribución de ingresos.
SQLite / PandasQL: Ejecución de consultas SQL para segmentación de clientes.
Jupyter Notebook: Entorno de desarrollo y documentación del análisis.

📈 Etapas del Análisis
* **1. Generación y Limpieza de Datos**
Se creó un dataset de 1,000 transacciones incluyendo variables como customer_id, product_category, total_revenue y date. Se aplicaron técnicas de Data Wrangling para manejar valores nulos y estandarizar formatos de tiempo.
* **2. Análisis Exploratorio (EDA)**
Rentabilidad por Categoría: Identificación de las categorías "Home" y "Electronics" como los principales motores de ingresos.
Análisis Temporal: Visualización de la estacionalidad de ventas, detectando picos críticos en el último trimestre del año.
* **3. Segmentación SQL (Business Intelligence)**
Utilizando lógica de Business Solutions, se clasificó la base de clientes en tres niveles:
VIP: Clientes con un gasto acumulado > $10,000 USD.
Frecuentes: Clientes con gasto entre $5,000 y $10,000 USD.
Ocasionales: Clientes con gasto menor a $5,000 USD.

💡 Conclusiones de Negocio
Retención Prioritaria: El 10% de los clientes (Top 10) genera una parte desproporcionadamente alta de los ingresos, lo que justifica la creación de un programa de lealtad exclusivo.
Oportunidad de Upselling: Se identificó un segmento de clientes "Frecuentes" con alto potencial de conversión a VIP mediante campañas de marketing dirigidas.
