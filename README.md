# telecom-analysis
## Objetivo
Este proyecto analiza el comportamiento de uso de servicios móviles (llamadas y mensajes) de ConnectTel, una empres de telecomunicaciones con operaciones en México y Colombia.

## Datasets Utilizados
El análisis se basa en tres fuentes principales de datos:

* **plans.csv** : información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
* **users_latam.csv** : información de los clientes (edad, ciudad, fecha de registro, plan, churn).
* **usage.csv** : información de los clientes (edad, ciudad, fecha de registro, plan, churn).

## Preguntas de Negocio
- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes y optimizar la oferta?

## Tecnologías y Librerías Utilizadas

- **Python 3.8+**
- **Jupyter Notebook**

### Librerías principales:
- `pandas >= 1.3.0` - Manipulación y análisis de datos
- `numpy >= 1.21.0` - Operaciones numéricas y arrays
- `matplotlib >= 3.5.0` - Visualización básica de datos
- `seaborn >= 0.11.0` - Visualización estadística avanzada
- `scipy >= 1.7.0` - Análisis estadístico y detección de outliers

## Etapas del Análisis

* Exploración y Limpieza de Datos - Carga y exploración inicial de los datasets - Identificación y tratamiento de valores faltantes - Validación y estandarización de tipos de datos - Detección de inconsistencias.
* Integración de Datos - Unión de las tres fuentes de datos - Creación del dataset consolidado user_profile - Validación de la integridad de los datos integrados.
* Análisis Exploratorio de Datos (EDA) - Estadísticas descriptivas por segmentos - Análisis de distribuciones de uso - Identificación de patrones por país y edad.
* Detección de Valores Atípicos - Aplicación de métodos estadísticos (IQR, Z-score) - Visualización de outliers - Análisis de comportamientos anómalos.
* Segmentación de Clientes - Segmentación por uso: Bajo uso, Uso medio, Alto uso - Segmentación por edad: Joven (<30), Adulto (30-59), Adulto Mayor (≥60) - Análisis cruzado de segmentos.
* Visualización y Insights - Gráficos de distribución por segmentos - Análisis comparativo entre países - Identificación.
