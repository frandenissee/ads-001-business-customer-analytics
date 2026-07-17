# ADS-001 | Customer Analytics para la Toma de Decisiones en E-commerce

## Applied Data Science Lab

Este proyecto forma parte del **Applied Data Science Lab**, una colección de casos de estudio de Ciencia de Datos Aplicada orientados a resolver problemas reales mediante el análisis de datos y el desarrollo de soluciones basadas en evidencia.

**ADS-001** aborda un problema de **Customer Analytics** en un marketplace de comercio electrónico utilizando un conjunto de datos públicos del sector. El objetivo es comprender el comportamiento de los clientes mediante análisis exploratorio, segmentación y modelos predictivos para generar recomendaciones que apoyen la toma de decisiones estratégicas del negocio.

---

# Tabla de Contenidos

* [Objetivo del Proyecto](#objetivo-del-proyecto)
* [Problema de Negocio](#problema-de-negocio)
* [Valor para el Negocio](#valor-para-el-negocio)
* [Objetivos Específicos](#objetivos-específicos)
* [Dataset](#dataset)
* [Metodología](#metodología)
* [Flujo Analítico](#flujo-analítico)
* [Indicadores Clave (KPIs)](#indicadores-clave-kpis)
* [Roadmap del Proyecto](#roadmap-del-proyecto)
* [Estructura del Repositorio](#estructura-del-repositorio)
* [Documentación](#documentación)
* [Tecnologías](#tecnologías)
* [Estado del Proyecto](#estado-del-proyecto)
* [Resultados Esperados](#resultados-esperados)
* [Autor](#autor)
* [Licencia](#licencia)

---

# Objetivo del Proyecto

Desarrollar un caso de estudio de Ciencia de Datos Aplicada que permita comprender el comportamiento de los clientes de un marketplace de comercio electrónico mediante el análisis de datos, la segmentación de clientes y el desarrollo de modelos predictivos.

El propósito final es transformar datos en información útil que permita apoyar decisiones de negocio relacionadas con la retención de clientes, la experiencia de compra y el crecimiento del negocio.

---

# Problema de Negocio

Las empresas de comercio electrónico generan grandes volúmenes de datos sobre clientes, pedidos, pagos, productos y entregas. Sin embargo, disponer de datos no garantiza una mejor toma de decisiones.

La empresa objeto de este caso de estudio busca responder preguntas como:

* ¿Quiénes son nuestros clientes?
* ¿Qué patrones de compra presentan?
* ¿Existen segmentos claramente diferenciados?
* ¿Qué factores influyen en la satisfacción del cliente?
* ¿Qué clientes tienen mayor valor potencial?
* ¿Qué acciones podrían mejorar la retención y la experiencia del cliente?

Este proyecto utiliza técnicas de Ciencia de Datos para responder estas preguntas mediante un enfoque estructurado y reproducible.

---

# Valor para el Negocio

Los resultados de este proyecto buscan apoyar la toma de decisiones en distintas áreas del negocio, permitiendo:

* Comprender el comportamiento de compra de los clientes.
* Identificar segmentos de clientes con características similares.
* Detectar oportunidades para mejorar la retención de clientes.
* Evaluar el impacto de la logística en la satisfacción.
* Identificar categorías y productos de mayor valor.
* Apoyar estrategias comerciales y de marketing basadas en datos.

---

# Objetivos Específicos

* Comprender el contexto del negocio y definir las preguntas analíticas.
* Analizar la calidad y estructura de los datos.
* Integrar y preparar múltiples fuentes de información.
* Realizar un análisis exploratorio orientado al negocio.
* Identificar segmentos de clientes mediante técnicas de clustering.
* Desarrollar un modelo predictivo que aporte valor al negocio.
* Generar recomendaciones basadas en evidencia para apoyar la toma de decisiones.

---

# Dataset

Este proyecto utiliza el **Brazilian E-Commerce Public Dataset by Olist**, un conjunto de datos públicos que contiene información sobre pedidos realizados en un marketplace brasileño entre 2016 y 2018.

El dataset incluye información relacionada con:

* Clientes
* Pedidos
* Productos
* Pagos
* Vendedores
* Reseñas
* Geolocalización
* Categorías de productos

Al tratarse de un conjunto de datos relacional, permite simular un entorno cercano al de una empresa real y desarrollar un flujo completo de análisis de datos.

---

# Metodología

El proyecto sigue la metodología **CRISP-DM (Cross-Industry Standard Process for Data Mining)**.

Las etapas consideradas son:

1. Comprensión del negocio.
2. Comprensión de los datos.
3. Preparación de los datos.
4. Modelado.
5. Evaluación.
6. Despliegue.

Cada una de estas etapas se adapta al contexto académico del proyecto y se desarrolla mediante sprints incrementales.

---

# Flujo Analítico

El desarrollo del proyecto seguirá el siguiente flujo de trabajo:

1. Comprensión del negocio.
2. Comprensión de los datos.
3. Preparación de datos.
4. Análisis exploratorio.
5. Ingeniería de variables.
6. Segmentación de clientes.
7. Modelado predictivo.
8. Recomendaciones para el negocio.

---

# Indicadores Clave (KPIs)

Durante el proyecto se analizarán, entre otros, los siguientes indicadores:

* Ingresos totales.
* Valor promedio por pedido.
* Número de clientes únicos.
* Tasa de recompra.
* Tiempo promedio de entrega.
* Calificación promedio de los clientes.
* Ventas por categoría.
* Ventas por estado.

---

# Roadmap del Proyecto

## Sprint 0 — Project Setup

* Configuración del repositorio.
* Estructura del proyecto.
* Entorno virtual.
* Documentación inicial.

## Sprint 1 — Business Understanding

* Definición del problema de negocio.
* Objetivos del proyecto.
* Stakeholders.
* Preguntas de negocio.
* Project Canvas.
* Diccionario de datos.
* Modelo entidad-relación (ERD).

## Sprint 2 — Data Understanding

* Exploración inicial de las tablas.
* Calidad de los datos.
* Valores faltantes.
* Tipos de datos.
* Estadísticas descriptivas.

## Sprint 3 — Data Preparation

* Limpieza de datos.
* Integración de tablas.
* Transformaciones.
* Ingeniería de variables.
* Construcción del dataset analítico.

## Sprint 4 — Exploratory Data Analysis

* KPIs.
* Patrones de compra.
* Distribuciones.
* Análisis geográfico.
* Análisis temporal.
* Insights de negocio.

## Sprint 5 — Customer Segmentation

* Construcción de variables.
* Clustering.
* Perfilado de segmentos.
* Interpretación de resultados.

## Sprint 6 — Predictive Analytics

* Definición del problema predictivo.
* Entrenamiento de modelos.
* Evaluación.
* Interpretación de resultados.

## Sprint 7 — Reporting & Business Recommendations

* Dashboard de resultados.
* Recomendaciones para el negocio.
* Limitaciones.
* Trabajo futuro.
* Informe final.

---

# Estructura del Repositorio

```text
ads-001-business-customer-analytics/

├── data/
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── business_understanding.md
│   ├── project_canvas.md
│   ├── data_dictionary.md
│   └── entity_relationship.md
│
├── figures/
├── notebooks/
├── reports/
├── src/
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

---

# Documentación

La documentación del proyecto se encuentra en la carpeta `docs/` e incluye:

* Business Understanding
* Project Canvas
* Data Dictionary
* Entity Relationship Diagram (ERD)

Cada documento describe una parte del proceso de comprensión del negocio y de los datos antes de iniciar el análisis exploratorio.

---

# Tecnologías

Las principales herramientas utilizadas en este proyecto son:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn *(etapas posteriores)*
* Git
* GitHub

A medida que el proyecto avance podrán incorporarse nuevas herramientas de análisis y visualización.

---

# Estado del Proyecto

**Estado actual:** 🟡 En desarrollo

## Progreso

* [x] Configuración del repositorio
* [x] Configuración del entorno virtual
* [x] Estructura del proyecto
* [x] Licencia MIT
* [x] Comprensión del negocio
* [x] Comprensión de los datos
* [ ] Preparación de los datos
* [ ] Análisis exploratorio
* [ ] Segmentación de clientes
* [ ] Modelado predictivo
* [ ] Recomendaciones de negocio

---

# Resultados Esperados

Al finalizar el proyecto se espera contar con:

* Un análisis exploratorio reproducible.
* Un dataset analítico preparado.
* Segmentos de clientes claramente definidos.
* Un modelo predictivo alineado con un problema de negocio.
* Recomendaciones accionables basadas en evidencia.
* Un dashboard con indicadores relevantes.
* Documentación técnica completa y reproducible.

---

# Autor

**Francisca Morales Romo**

Proyecto desarrollado como parte del **Applied Data Science Lab**.

---

# Licencia

Este proyecto se distribuye bajo la licencia **MIT**.

El código fuente está disponible para fines educativos y de aprendizaje conforme a los términos de dicha licencia.

El dataset utilizado pertenece a sus respectivos autores y está sujeto a las condiciones de uso establecidas por su licencia.