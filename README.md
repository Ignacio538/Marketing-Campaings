# **Impulso Estratégico**



### 📌 Sobre el Proyecto

Bienvenido a **Impulso Estratégico**, un análisis de datos de campañas de marketing centrado en el rendimiento. En este proyecto, hemos aplicado técnicas de limpieza, transformación y análisis de datos para obtener información clave sobre la efectividad de distintas estrategias de marketing.

## 📂 Contenido

### 🔍 Contexto

### 📊 Base de Datos

### 🛠️ Procesamiento de Datos

### 📈 Análisis y Resultados

### 📄 Informe Final


## [🔍 Contexto](#contexto)

El objetivo de este proyecto es analizar el rendimiento de campañas de marketing en función de diversas métricas clave: ROI, Tasa de conversión e Ingresos. Además, estudiamos el impacto de la duración de las campañas y patrones estacionales en los resultados.


## [📊 Base de Datos](#base-de-datos)

Trabajamos con un ["dataset"](https://github.com/Ignacio538/Marketing-Campaings/blob/main/data/marketingcampaigns.csv) de campañas de marketing con las siguientes variables principales:

- start_date y end_date: Fechas de inicio y fin.

- budget: Presupuesto de la campaña.

- roi: Retorno de inversión.

- type: El tipo de campaña.

- target_audience: A quién iba dirigida la campaña.

- channel: El canal por lo que se ha hecho la campaña.

- conversion_rate: Tasa de conversión.

- revenue: Ingresos generados.


## [🛠️ Procesamiento de Datos](#procesamiento-de-datos)

- Primero realizamos una limpieza del archivo original, incluyendo:

· Eliminación de filas duplicadas.

· Eliminación y/o corrección de outliers y valores nulos y/o erróneos.

· Corrección de formatos.

En total hemos eliminado **35 líneas**.

- A continuación hemos creado una serie de indicadores que nos ayudarán a responder a las preguntas que queremos responder en este análisis, así como futuras preguntas que puedan surgir:

· Creación de una columna net_profit (beneficio neto).

· Cálculo de valores estacionales como los meses o los trimestres.

· Cálculo de los días que han durado las campañas.

· Agrupación de campañas por duración en intervalos de 60 días para analizar su impacto.


Los datos limpiados junto con las nuevas variables creadas han sido almacenados en ["marketing_campaigns_clean.csv"](https://github.com/Ignacio538/Marketing-Campaings/blob/main/data/marketing_campaigns_clean.csv).

Todo este análisis está en en el notebook llamado ["Analysis"](https://github.com/Ignacio538/Marketing-Campaings/blob/main/notebooks/Analysis.ipynb).



## [📈 Análisis y Resultados](#-análisis-y-resultados)

Se respondieron siete preguntas clave sobre el rendimiento de las campañas mediante visualizaciones y métricas.

Entre los hallazgos más relevantes:

- La escasa correlación del ROI con los ingresos o la tasa de conversión.

- La fuerte diferencia que hay en la tasa de conversión para el público B2C cuando el canal es "Paid" o cuando es "Organic".

- En cuanto a las campañas más exitosas, el canal está muy diferenciado.

- La prácticamente inexistente correlación entre el presupuesto y los ingresos.

- Las ventas están cayendo mientras que el ROI sube.


Los análisis se encuentran en el notebook llamado ["Tasks"](https://github.com/Ignacio538/Marketing-Campaings/blob/main/notebooks/Tasks.ipynb).


## [📄 Informe Final](#-informe-final)

El [informe](https://github.com/Ignacio538/Marketing-Campaings/blob/main/docs/Informe_Final.md) incluye:

Resumen de respuestas a las preguntas clave.

Gráficos para visualizar tendencias.

**📌 Este proyecto fue desarrollado por Ignacio Rivas Andrades.**

![Logo de Upgrade Hub](Upgrade_logo.png)