# TelecomX_LATAM_P1
challenge 2

README

Este proyecto tiene como objetivo analizar el problema de cancelación de clientes (churn) en la empresa TelecomX a partir de datos históricos obtenidos mediante una API. En esta primera etapa del análisis se realizó principalmente la extracción, limpieza y preparación de los datos, así como un análisis exploratorio que permitió identificar patrones relacionados con la cancelación de clientes. El propósito del análisis fue comprender qué características de los usuarios, tipos de contrato, servicios contratados y gastos asociados al servicio influyen en la probabilidad de que un cliente abandone la empresa.

El proyecto está organizado dentro de un notebook donde se desarrolla todo el proceso de trabajo. En él se incluyen las etapas de extracción de los datos desde la API en formato JSON, transformación de la información a un DataFrame, separación de columnas anidadas relacionadas con información del cliente, servicios telefónicos, internet y cuenta, así como el proceso de limpieza y estandarización de los datos. Durante este proceso también se convirtieron variables a formatos adecuados, se eliminaron registros con datos faltantes y se creó una variable adicional de gasto diario promedio. Como resultado final se generó un conjunto de datos limpio que se guardó como df_final.csv para su uso en el análisis.

Durante el análisis exploratorio se generaron diferentes visualizaciones para comprender el comportamiento del churn. Se realizaron gráficos de barras y gráficos de pastel para observar la proporción de clientes que cancelan y los que permanecen activos. También se elaboraron gráficos de barras para analizar la relación entre churn y variables categóricas como género, tipo de servicio de internet, método de pago y tipo de contrato. Además, se utilizaron histogramas para analizar la distribución de variables numéricas como tenure, Charges_Monthly, Charges_Total y cuentas_diarias, así como una matriz de correlación entre estas variables para identificar posibles relaciones.

Para ejecutar el proyecto únicamente es necesario abrir el notebook y ejecutar las celdas en el orden en que aparecen, ya que todo el proceso de extracción de datos, limpieza, análisis exploratorio y generación del dataset final se encuentra documentado dentro del mismo.
