# Análisis de KPIs de marketing y rendimiento de campañas

Este proyecto realiza un **análisis integral de desempeño de campañas de marketing digital**, calculando y evaluando los principales **KPIs de adquisición, conversión y rentabilidad** a partir de datos históricos de campañas.

El objetivo es **medir la eficiencia del gasto en marketing**, identificar campañas rentables y detectar oportunidades de optimización basadas en datos.

---

## 📈 Contexto del negocio

Las empresas invierten grandes presupuestos en múltiples canales digitales (Google, Facebook, Instagram, YouTube, partners).  
Sin un análisis sistemático de KPIs, es difícil responder preguntas clave como:

- ¿Qué campañas generan mayor retorno?
- ¿Dónde se está desperdiciando presupuesto?
- ¿Qué canal convierte mejor?
- ¿Cómo varía el rendimiento a lo largo del tiempo?

Este proyecto aborda estas preguntas desde una perspectiva **data-driven**.

---

## 🎯 Objetivo del análisis

- Evaluar el rendimiento de campañas de marketing
- Calcular métricas clave de adquisición, conversión y rentabilidad
- Analizar la evolución temporal de ingresos y engagement
- Identificar campañas con pérdidas y bajo desempeño
- Simular consultas analíticas usando lógica SQL

---

## 📊 Dataset

El dataset contiene información diaria de campañas de marketing digital:

### Variables principales
- `campaign_name`, `campaign_id`
- `c_date` (fecha)
- `impressions`
- `clicks`
- `leads`
- `orders`
- `revenue`
- `mark_spent` (gasto en marketing)

El dataset se encuentra **limpio**, sin valores nulos ni duplicados.

---

## 📐 KPIs calculados

Se calcularon y analizaron los siguientes indicadores clave:

- **CTR (Click Through Rate)**  
- **Conversion Rate 1** (clics → leads)
- **Conversion Rate 2** (leads → órdenes)
- **CPC (Cost Per Click)**
- **CPM (Cost Per Mille)**
- **CPA / CAC (Coste por adquisición)**
- **AOV (Average Order Value)**
- **RPC (Revenue Per Click)**
- **ROI / ROMI (Return on Marketing Investment)**

---

## 🧪 Metodología

### 1. Exploración inicial (EDA)
- Revisión de estructura y calidad del dataset
- Validación de integridad de datos
- Estadísticas descriptivas

### 2. Análisis de campañas
- Comparación de ROI, CPA, CTR y tasas de conversión por campaña
- Identificación de campañas de alto y bajo rendimiento
- Ranking de campañas por rentabilidad

### 3. Análisis temporal
- Evolución diaria de:
  - ingresos
  - impresiones
  - CTR promedio
  - tasas de conversión
- Detección de picos y caídas de rendimiento

### 4. Análisis de costos y eficiencia
- Evaluación de CPC y CPM por canal
- Relación entre costos, ingresos y valor promedio de pedido
- Identificación de campañas costosas con bajo retorno

### 5. Análisis tipo SQL
- Resolución de preguntas de negocio mediante lógica SQL
- Replicación de métricas con consultas `SELECT`, `WHERE`, `GROUP BY`
- Comparación entre enfoques Python y SQL

---

## 📌 Principales insights

- **YouTube Blogger** presenta el mayor ROI y los mejores ingresos por clic
- **Facebook LAL** muestra consistentemente bajo rendimiento y pérdidas
- **Instagram Tier 2** es el canal más rentable en términos de costos (CPC y CPM)
- El pico de ingresos ocurre alrededor del **20 de febrero**, seguido por una caída
- El CTR alto no siempre se traduce en mayores ingresos
- Las campañas de Facebook con ROMI negativo concentraron una pérdida significativa

---

## 🛠️ Tecnologías utilizadas

- **Python**
- **pandas**
- **matplotlib, `seaborn**`
- **SQL (lógica analítica)**
- **Jupyter / scripts en Python**

---

## 📂 Estructura del repositorio

├── Marketing.csv
├── KPI_marketing.py
├── README.md


---

## 🚀 Próximos pasos

- Construcción de un dashboard interactivo (Power BI / Tableau)
- Automatización del cálculo de KPIs
- Segmentación por canal, audiencia o dispositivo
- Integración con datos de atribución multi-touch
- Alertas automáticas para campañas con ROMI negativo

---

## 👤 Autor

**Flavia Hepp**  
Data Analyst / Analytics en formación  
