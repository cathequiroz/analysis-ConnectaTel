## analysis-ConnectaTel

Descripción del proyecto:
Este repositorio contiene el análisis de datos realizado para ConnectaTel, una empresa de telecomunicaciones que opera en Latinoamérica.

Como analista de datos, el objetivo es evaluar el comportamiento de los clientes y comprender cómo utilizan los servicios de llamadas y mensajes, identificar patrones de consumo y detectar oportunidades de mejora en los planes ofrecidos por la empresa.
El análisis utiliza información registrada hasta el año 2024 y aplica técnicas de limpieza, exploración, análisis estadístico y segmentación de clientes para generar insights que apoyen la toma de decisiones estratégicas.

## 📂 Contenido del repositorio

Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/Análisis ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde el enlace público.

## Conclusiones e Insights Clave

1. 📊 La calidad de los datos es fundamental para obtener conclusiones confiables

El análisis identificó problemas importantes de calidad, especialmente en las variables duration y length, con un 55,19 % y un 44,74 % de valores faltantes, respectivamente. También se detectaron 469 usuarios sin información de ciudad (11,73 %) y un valor centinela inválido (-999) en la variable age. Estos hallazgos evidencian la importancia de aplicar procesos de limpieza y validación antes de realizar análisis estadísticos. Además, los valores faltantes de churn_date deben interpretarse según su significado, ya que pueden indicar usuarios que no han cancelado el servicio.

2. 🎯 La segmentación del consumo abre oportunidades para personalizar los planes

El análisis mostró que el consumo típico por usuario se sitúa alrededor de 5 mensajes y 4 llamadas, aunque existen clientes con niveles de uso considerablemente superiores. Esta variabilidad permite distinguir entre usuarios de bajo, medio y alto consumo, cada uno con necesidades potencialmente diferentes. ConnectaTel podría evaluar planes más económicos para clientes de bajo uso y alternativas con mayor capacidad para usuarios de consumo elevado, utilizando datos reales de demanda para validar estas oportunidades.

💡 Conclusión general

El análisis exploratorio de ConnectaTel permitió identificar problemas de calidad de datos, caracterizar los patrones de consumo y establecer segmentos con necesidades potencialmente distintas. Estos resultados proporcionan una base para optimizar la oferta de planes y orientar futuras estrategias comerciales. Como siguiente paso, sería necesario validar la rentabilidad de cada segmento y analizar las tasas de cancelación para convertir estos hallazgos en decisiones de negocio basadas en evidencia.
