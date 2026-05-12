# Arquitectura Big Data en GCP: Caso de Estudio Tottus

## Contexto y Resumen del Proyecto
Este proyecto académico consistió en el diseño e implementación de una arquitectura de datos escalable basada en el **Modelo Lambda** utilizando Google Cloud Platform (GCP). 

Para este desarrollo, tomamos como caso de estudio a la cadena de supermercados **Tottus**. Utilizando **datasets simulados**, construimos un flujo de datos capaz de resolver problemas operativos reales del sector retail peruano, permitiendo procesar grandes volúmenes de información transaccional para la posterior visualización y optimización de KPIs estratégicos de inventario y ventas.

## Mi Rol en el Proyecto
Como parte de un equipo ágil, **lideré el diseño y la implementación de la arquitectura de la base de datos**. Me encargué de estructurar el flujo de datos desde la ingesta hasta el almacenamiento analítico, garantizando que la información estuviera optimizada, limpia y lista para su consumo en herramientas de Business Intelligence.

## Stack Tecnológico y Arquitectura (Google Cloud Platform)
La solución fue estructurada en las siguientes capas lógicas:
* **Ingesta (Streaming/Eventos):** Implementación de `Cloud Pub/Sub` para capturar eventos de ventas en tiempo real desde los sistemas transaccionales, logrando una recolección continua y desacoplada.
* **Almacenamiento (Data Lake):** Configuración de `Cloud Storage` para conservar la información histórica en estado crudo, facilitando auditorías y análisis sin transformación previa.
* **Procesamiento:** Uso de `Cloud Dataflow` para ejecutar pipelines de limpieza, estructuración y transformación de los datos de ventas.
* **Almacenamiento Analítico (Data Warehouse):** Modelado en `BigQuery` para alojar los datos estructurados, permitiendo consultas analíticas de alta eficiencia.

## Arquitectura del Sistema
![Arquitectura General](arquitecturaRetail_GCP)
