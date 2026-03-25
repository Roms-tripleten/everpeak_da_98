# Análisis Estadístico de EverPeak Holdings

Este repositorio contiene el análisis estadístico realizado para EverPeak Holdings, una empresa recién incorporada al portafolio de SilverBasket Retail Group. El objetivo principal es evaluar la calidad y estructura de los datos transaccionales, identificar patrones clave y detectar posibles segmentos de clientes de alto valor.

## Contexto del Negocio

A finales del 2024, SilverBasket Retail Group firmó un acuerdo para incorporar a EverPeak Holdings. Antes de concretar la adquisición, el equipo de Estrategia e Integración de SilverBasket ha iniciado una revisión de los datos transaccionales de EverPeak para garantizar la confiabilidad de futuros análisis de clientes, ventas y márgenes. Este informe detalla el proceso de análisis y los hallazgos clave.

## Objetivo del Análisis

El análisis busca responder tres preguntas centrales:

1.  **Completitud y Consistencia de los Datos:** Evaluar la calidad y estructura de los datos transaccionales de EverPeak.
2.  **Patrones de Comportamiento:** Identificar patrones iniciales que revelen el comportamiento, distribución y valor de los clientes.
3.  **Segmentos de Alto Valor:** Detectar segmentos de clientes con alto potencial que representen una oportunidad estratégica para el negocio.

## Contenido del Notebook

El notebook `analisis_estadistico_everpeak.ipynb` (o el nombre que le hayas dado) aborda los siguientes puntos:

*   **Visión General de los Datos:** Exploración inicial del dataset, incluyendo su estructura, volumen y calidad. Se realiza un diagnóstico del formato de datos y se identifican valores faltantes.
*   **Limpieza de Datos:** Implementación de un pipeline modular y reproducible para la limpieza de datos, incluyendo la estandarización de columnas de texto, el tratamiento de valores numéricos y la conversión de tipos de datos. Se documenta la estrategia para manejar valores atípicos, específicamente en las variables `order_value` y `customer_age`.
*   **Análisis Estadístico y Manejo de Atípicos:** Análisis detallado de las variables `order_value` y `customer_age` mediante estadísticas descriptivas y visualizaciones (histogramas y boxplots). Se aplica el criterio del rango intercuartílico (IQR) para identificar y tratar valores atípicos, asegurando la robustez de la segmentación posterior.
*   **Segmentación de Clientes:** Aplicación de una metodología de segmentación basada en `order_value` y `customer_age` para categorizar a los clientes en grupos estratégicos como 'Senior VIP', 'Junior VIP', 'Jr. Medium Value' y 'Low Value'. Se discuten las implicaciones de cada segmento para futuras estrategias de negocio.

### Tecnologías Utilizadas

*   Python
*   Pandas (para manipulación de datos)
*   Matplotlib y Seaborn (para visualización de datos)
*   Jupyter Notebook / Google Colab

Este análisis proporciona una base sólida para la toma de decisiones estratégicas en la integración de EverPeak Holdings a SilverBasket Retail Group.
