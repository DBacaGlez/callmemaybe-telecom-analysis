# CallMeMaybe Telecom Analysis

Este proyecto analiza el desempeño operativo de los operadores de la plataforma de telefonía virtual **CallMeMaybe**. El objetivo es identificar operadores ineficaces mediante un análisis detallado de métricas clave como tiempos de espera, llamadas perdidas y actividad de llamadas salientes. Además, se realizan pruebas estadísticas para validar diferencias significativas entre diferentes grupos operativos.

## 📌 Objetivo
- Evaluar la eficiencia de los operadores.
- Identificar tiempos de espera excesivos, tasas altas de llamadas perdidas y baja actividad.
- Construir criterios cuantitativos que determinen qué operadores son ineficaces.
- Visualizar patrones en el comportamiento operativo.
- Realizar pruebas de hipótesis para validar diferencias entre grupos.

## 🧹 Preparación y Limpieza de Datos
- Conversión de fechas y normalización de columnas.
- Revisión de valores extremos: operadores con tiempos de espera >1 hora.
- Identificación de operadores con registros anómalos o incompletos.
- Cálculo de métricas derivadas:  
  - Tiempo promedio de espera  
  - Porcentaje de llamadas perdidas  
  - Número de llamadas salientes  
  - Ratio de actividad  

## 📊 Análisis Exploratorio de Datos (EDA)
- Distribuciones de tiempos de espera por operador.
- Cálculo del porcentaje de llamadas perdidas.
- Identificación de casos extremos (outliers).
- Mapas de calor y gráficos comparativos.
- Clasificación de operadores en categorías de desempeño.

## 🧮 Identificación de Operadores Ineficaces
Para categorizar a un operador como ineficaz, se evaluaron simultáneamente criterios como:

- **Tiempos de espera excesivos**  
- **Alta tasa de llamadas perdidas**  
- **Baja cantidad de llamadas de salida**  

Se construyó una matriz de decisión para determinar cuántos operadores cumplen con uno, dos o los tres criterios de ineficiencia.

## 📈 Pruebas Estadísticas
Se aplicaron pruebas estadísticas para evaluar:

- Diferencias en tiempos de espera entre grupos.
- Diferencias en tasas de llamadas perdidas.
- Significancia estadística entre operadores del grupo "ineficiente" vs. "eficiente".

Estas pruebas respaldan con evidencia si un grupo presenta desempeños significativamente distintos.

## 🔎 Resultados Principales
- Se identificaron operadores con combinaciones de alto tiempo de espera y alta tasa de llamadas perdidas.
- Muchos operadores mantienen niveles normales de operación, pero algunos destacan por baja actividad.
- Los gráficos de dispersión permitieron visualizar claramente los cuadrantes de ineficiencia.
- Las pruebas estadísticas confirmaron qué métricas mostraban diferencias significativas.

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **SciPy / Statsmodels**
- **Jupyter Notebook**

## 📁 Archivos del Proyecto
- `callmemaybe-telecom-analysis.ipynb` — Notebook principal.
- Datasets de llamadas, operadores y actividad.
