# Arquitectura Big Data en GCP para el Sector Retail

## Resumen del Proyecto
Este proyecto académico consistió en el diseño e implementación de una arquitectura de datos escalable basada en el **Modelo Lambda** utilizando Google Cloud Platform (GCP). El objetivo principal fue optimizar la toma de decisiones en el sector retail mediante el procesamiento de grandes volúmenes de datos de ventas e inventarios para la posterior visualización de KPIs estratégicos.

## Mi Rol en el Proyecto
Como parte de un equipo de 4 personas, **lideré el diseño y la implementación de la arquitectura de la base de datos**. Me encargué de estructurar el flujo de datos desde la ingesta hasta el almacenamiento analítico, garantizando que la información estuviera optimizada para su consumo en herramientas de Business Intelligence.

## Stack Tecnológico (Google Cloud Platform)
La solución fue estructurada en las siguientes capas:
* **Ingesta (Streaming):** `Cloud Pub/Sub` para capturar eventos de ventas en tiempo real desde sistemas transaccionales.
* **Almacenamiento (Data Lake):** `Cloud Storage` para conservar la información histórica en estado crudo (raw).
* **Procesamiento:** `Cloud Dataflow` para ejecutar pipelines de limpieza y transformación de datos.
* **Almacenamiento Analítico (Data Warehouse):** `BigQuery` para almacenar datos estructurados y soportar consultas analíticas de alta eficiencia.

## Arquitectura del Sistema
![Arquitectura General] [ImagenArquitectura.png]

## Estructura de este Repositorio
* Diagramas conceptuales de las capas de datos.
* Capturas de la implementación en la consola de Google Cloud.
* Informe técnico detallado del proyecto.
