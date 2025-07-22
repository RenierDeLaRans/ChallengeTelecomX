Propósito del Análisis
El objetivo de este proyecto es analizar el fenómeno de churn (evasión de clientes) en la empresa de telecomunicaciones TelecomX. La pérdida de clientes impacta directamente los ingresos, por lo que este análisis busca:
Identificar patrones de comportamiento que llevan a la cancelación del servicio.
Determinar qué variables influyen más en la retención.
Apoyar decisiones estratégicas con base en datos para reducir la tasa de evasión.

Estructura del Proyecto
TelecomX/
├── ChallegeTelecomX.ipynb     <- Notebook principal del análisis
├── TelecomX.json              <- Archivo original de datos (anidado)
├── README.md                  <- Este archivo

El notebook está organizado en las siguientes secciones:
Carga y limpieza de datos
Lectura del archivo JSON con estructuras anidadas.
Desanidación de columnas (customer, account, phone, internet).
Conversión de tipos de datos y creación de nuevas variables como Cuentas_Diarias.
Análisis Exploratorio (EDA)
Visualización de la distribución de churn.
Análisis de correlación entre variables categóricas y churn.
Exploración de variables numéricas como MonthlyCharges, TotalCharges y tenure.
Visualizaciones
Gráficos de pastel, barras apiladas y histogramas para comparar segmentos.

Ejemplos de Gráficos e Insights
Distribución de Churn: Un 26% de los clientes cancelaron el servicio.
Tipo de Contrato: Los contratos "Month-to-month" tienen la mayor tasa de evasión.
Método de Pago: El método Electronic check se asocia con una mayor probabilidad de churn.
Tenencia (tenure): Clientes nuevos (menos de 12 meses) tienden a cancelar más.
Segmentación por Género y Edad: No se observaron diferencias significativas por género, pero los Senior Citizens presentan una ligera mayor propensión a cancelar.

Instrucciones para Ejecutar el Notebook
Asegúrate de tener Python 3 y Jupyter Notebook instalados. Puedes usar Anaconda para facilitar esto.

Instala las dependencias necesarias:
pip install pandas matplotlib seaborn

Abre el notebook:
jupyter notebook ChallegeTelecomX.ipynb

Ejecuta cada celda secuencialmente (Shift + Enter) para reproducir el análisis y visualizar los gráficos.



