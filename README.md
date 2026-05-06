# Market Express: Estrategia de Expansión Global 🌍

**Market Express** es una plataforma ficticia de e-commerce, almacenamiento y distribución cuyo valor diferencial es la eficiencia logística, garantizando entregas en menos de 48 horas. 

Este proyecto tiene como objetivo definir la infraestructura necesaria para la expansión a nuevos mercados internacionales, determinando si la empresa debe optar por un **Centro de Distribución Único** o **Centros Múltiples**, basándose en un análisis multidimensional de datos.

---

## 🎯 Objetivos del Proyecto

* **Análisis Macro:** Evaluar variables clave a nivel mundial: Población, Superficie (km²), Densidad Poblacional, Idiomas oficiales y Condiciones de vida (Esperanza de Vida).
* **Análisis Económico:** Estudiar el GNP y GNP per Cápita para identificar la disposición de pago en potenciales mercados.
* **Modelado de Infraestructura:** Clasificar países según el tipo de centro a instalar basado en la distribución de la población y condiciones estructurales.
* **Identificación de Oportunidades:** Obtener el **Top 10 de países** con mayor GNP per cápita para priorizar la inversión.

---

## 🛠️ Stack Tecnológico

Para este análisis se integraron las siguientes herramientas:

* **SQL:** Utilizado para la importación de datos y la ejecución de consultas exploratorias iniciales.
* **Python (Pandas):** Empleado para la limpieza, transformación de datos y la creación de la lógica de clasificación.
* **Power BI:** Utilizado para la creación de dashboards interactivos y la visualización de los hallazgos estratégicos.

---

## 📂 Datos y Metodología

Se trabajó con la base de datos `world`, la cual incluye información estructurada en las tablas:
1.  `city`
2.  `country`
3.  `countrylanguage`

### Transformaciones Realizadas
Durante la fase de procesamiento en **Python**, se crearon métricas esenciales para la toma de decisiones:
- **Densidad Poblacional:** (Habitantes / km²) para determinar la concentración urbana.
- **Crecimiento Económico:** Para evaluar la estabilidad del mercado.
- **GNP per Cápita:** Variable fundamental para clasificar el nivel de riqueza y potencial de consumo.

---

## 🚀 Criterios de Clasificación

El modelo decide la infraestructura óptima bajo las siguientes premisas:
- **Centro Único:** Idealmente en la capital, para países con población centralizada o superficies pequeñas.
- **Centros Múltiples:** Para países de gran extensión territorial o con población repartida en múltiples centros urbanos, siempre que las condiciones estructurales lo permitan.

---
