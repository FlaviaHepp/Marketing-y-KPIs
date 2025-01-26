# Marketing-y-KPIs
Análisis y visualización de una base de datos de Marketing. Hecho con SQL y Python.

Analizar el gasto de marketing.

1- ROMI general
2- ROMI por campañas
3- Rendimiento de la campaña según la fecha: ¿en qué fecha gastamos más dinero en publicidad, cuándo obtuvimos los mayores ingresos, cuándo las 
tasas de conversión fueron altas y bajas? ¿Cuáles fueron los valores de pedido promedio?
4- ¿Cuándo los compradores son más activos? ¿Cuál es el ingreso promedio los días de semana y los fines de semana?
5- ¿Qué tipos de campañas funcionan mejor: redes sociales, banners, influencers o una búsqueda?
6- ¿Qué ubicaciones geográficas son mejores para la segmentación: ciudades de nivel 1 o nivel 2?

Columna. Descripción
Fecha Fecha de gasto del presupuesto de marketing
Nombre de la campaña Descripción de la campaña
Categoría Tipo de fuente de marketing
Id. de campaña Identificador único
Impresiones Número de veces que se ha mostrado el anuncio
Marca. Presupuesto Dinero gastado en esta campaña en este día
Clics Cuántas personas hicieron clic en un banner (=sitio web visitado)
Clientes potenciales Cuántas personas se registraron y dejaron sus credenciales
Pedidos Cuántas personas pagaron por el producto
Ingresos Cuánto dinero ganamos

Los clics, los clientes potenciales, los pedidos y los ingresos se calculan para una campaña de marketing específica en una fecha específica. 
Por ejemplo, para la campaña de marketing "facebook_tier1" del 1 de febrero, gastamos 7307,37 INR y obtuvimos 148 263 impresiones que se 
convirtieron en 1210 clics que, a su vez, se convirtieron en 13 clientes potenciales y 1 pedido. Ganamos 4981 INR.

Estos datos reflejan algunos hechos sobre lo que sucedió: cuánto gastamos, cuánto ganamos, cómo se comportaron los clientes (quién hizo clic en 
el banner publicitario, quién se registró, quién pagó). Ahora necesitamos calcular métricas de marketing que nos ayuden a evaluar si hicimos un 
buen trabajo o no y también identificar algunos parámetros de la campaña que serían importantes para el análisis.
¿Cuáles son estas métricas?

Retorno de la inversión en marketing (ROMI)
Coste por clic (CPC)
Coste por cliente potencial (CPL)
Coste de adquisición de clientes (CAC)
Valor promedio del pedido (AOV)
Tasa de conversión 1
Tasa de conversión 2
Estas métricas son procesables y nos permiten no sólo analizar sino tomar decisiones y actuar para mejorar el resultado del negocio.

Vamos a profundizar más.

Retorno de la inversión en marketing (ROMI), qué tan efectiva es una campaña de marketing, una métrica que muestra la efectividad de cada rupia 
gastada.
Se calcula (Ganancias totales (ingresos) - Costo de marketing) / Costo de marketing)

Tasa de clics (CTR). Porcentaje de personas que hicieron clic en un banner (clics/impresiones)

Conversión 1 conversión de visitantes a clientes potenciales para esta campaña (clientes potenciales/clic)

Conversión 2 Tasa de conversión de clientes potenciales a ventas (pedidos/clientes potenciales)

Valor promedio del pedido (AOV) Valor promedio del pedido para esta campaña (Ingresos/Número de pedidos)

Coste por clic (CPC) cuanto nos cuesta atraer 1 clic (de media)
(Gasto en Marketing/Clics)

Coste por lead (CPL) ¿cuánto nos cuesta atraer 1 lead (de media)?
(Gasto en Marketing/Leads)

Costo de adquisición de clientes (CAC): ¿cuánto nos cuesta atraer 1 pedido (en promedio)
(gasto de marketing/pedidos)?
Ganancia bruta Ganancia o pérdida después de deducir el costo de marketing (Ingresos-Gasto de marketing)

ROMI es la métrica más importante y se utiliza como la forma definitiva de evaluar si la campaña es buena o mala.

Puede utilizar este artículo para obtener más información sobre las métricas de marketing.
https://www.owox.com/blog/articles/digital-marketing-metrics-and-kpis/

#Conclusiones:

#Alto ROI en YouTube: la campaña YouTube blogger se destaca con el mayor retorno de la inversión (ROI), lo que sugiere que las asociaciones con 
# influencers impulsadas por contenido en YouTube son altamente efectivas para generar valor a partir del gasto en marketing.
#Desafíos con Facebook LAL: la campaña Facebook Lookalike Audience (LAL) se identifica repetidamente como la de menor rendimiento tanto en ROI 
# como en otras métricas, lo que indica que, si bien dirigirse a audiencias similares puede ser poderoso, esta ejecución en particular puede 
# necesitar una revisión u optimización. #Retargeting efectivo en Facebook: el éxito de la campaña de retargeting en Facebook en términos de 
# tasa de clics (CTR) subraya la eficacia de las estrategias de retargeting en esta plataforma, probablemente debido a la segmentación precisa 
# de la audiencia en función de la interacción previa.
#Relación costo-eficiencia con Instagram Tier 2: la campaña Tier 2 de Instagram muestra el costo por adquisición (CPA) más bajo para los 
# clientes potenciales, lo que sugiere que las estrategias de segmentación o creativas en este nivel son rentables y efectivas para generar 
# interés y acciones a un menor costo.
#Dinámica interesante de la tasa de conversión: las altas tasas de conversión para las campañas Tier 2 de Facebook y YouTube Blogger, junto con 
# Instagram Blogger y Banner Partner, revelan una visión matizada del rendimiento de la campaña. Este último, a pesar de un CTR bajo, aún 
# logra altas tasas de conversión, lo que sugiere que, si bien es posible que menos usuarios hagan clic, los que lo hacen están muy interesados 
# ​​o tienen la intención de tomar una acción. Esto apunta a la calidad de la interacción por sobre la mera cantidad. #Rendimiento deficiente 
# persistente de Facebook LAL: en varias métricas, Facebook LAL muestra constantemente un rendimiento deficiente. Este hallazgo repetido indica 
# un área crítica para la reevaluación y el ajuste en la segmentación, la estrategia creativa o la ejecución general de la campaña.
#Próximos pasos con el análisis de series temporales: avanzar con un análisis de series temporales proporcionará información más detallada 
# sobre cómo estas tendencias y rendimientos evolucionan con el tiempo, especialmente dentro del contexto específico de los cambios diarios y 
# semanales de febrero. Esto podría revelar información más granular sobre la efectividad de la campaña, los comportamientos de la audiencia y 
# las posibles influencias externas en los resultados de marketing.

#Conclusión final: en resumen, hubo una interacción bastante compleja entre todas las diferentes métricas. No se puede simplemente observar un 
# punto de datos para comprender qué impulsó realmente el rendimiento. El panorama completo requiere profundizar en conjuntos de datos más 
# grandes y profundos.

***Calculando Métricas***
-Pregunta 1.1: ¿Cuál es el CTR de la campaña google_wide del 1 de febrero de 2021?
-Pregunta 1.2: ¿Cuál es la Conversión 1 de la campaña instagram_tier2 del 5 de febrero de 2021?
-Pregunta 1.3: ¿Cuál es la Conversión 2 de la campaña facebook_tier1 del 9 de febrero de 2021?
-Pregunta 1.4: ¿Cuál es el AOV de la campaña facebook_lal del 13 de febrero de 2021?
-Pregunta 1.5: ¿Cuál es el CPC de la campaña facebook_retargeting del 23 de febrero de 2021?
-Pregunta 1.6: ¿Cuál es el CAC de la campaña youtube_blogger del 24 de febrero de 2021?
-Pregunta 1.7: ¿Cuál es el ROMI de la campaña banner_partner del 28 de febrero de 2021?
***Calcular el ROMI general***
***Calcular el ROMI para la campaña instagram_blogger entre el 15 y el 25 de febrero***
***Averiguar el ingreso promedio gastado el fin de semana (sábado y domingo)***
***Averiguar el ingreso promedio gastado en días laborables (de lunes a viernes) con NOT IN***
***¿Qué campaña mostró la mayor pérdida en un solo día? Por pérdida nos referimos a una ganancia bruta negativa (ingresos - gastos de # marketing). Ingrese el ID de la campaña.***
***¿Cuánto dinero total gastamos en Facebook en campañas con ROMI negativo?***

El archivo realiza un análisis exhaustivo de métricas de marketing y desempeño de campañas publicitarias. A continuación, se detalla qué se hizo y las conclusiones principales:
**1. Objetivo del análisis**
Evaluar el desempeño de diversas campañas de marketing utilizando métricas clave como ROI, CTR, costo por clic (CPC), y costo por adquisición (CAC).
Identificar tendencias y patrones en las campañas para optimizar estrategias futuras.
**2. Actividades realizadas**
*Preparación de los datos:*
Carga de un conjunto de datos limpio que incluye columnas como gastos de marketing, ingresos, clics, pedidos, etc.
Verificación de valores duplicados y faltantes (no se encontraron problemas).
*Cálculo de métricas clave:*
- ROI: Mide la efectividad del gasto en marketing.
- CTR (Click-Through Rate): Indica la proporción de clics en relación con las impresiones.
- CPL (Cost per Lead) y CAC (Cost of Customer Acquisition): Cuánto cuesta generar leads o clientes.
- AOV (Average Order Value): Valor promedio por pedido.
Conversión 1 y 2: De clics a leads y de leads a pedidos.
*Análisis por campaña:*
Identificación de las campañas con mejor y peor desempeño según métricas clave.
Comparación de métricas como CTR, CPC, ingresos por clic y ROI.
*Análisis temporal:*
-Evaluación de ingresos y tasas de clics por día.
-Identificación de días con altos ingresos y aquellos con bajas tasas de conversión.
-Identificación de oportunidades y áreas de mejora:
-Campañas con pérdidas significativas.
-Análisis de campañas con ROMI negativo y estrategias de mejora.
*Tareas adicionales:*
Cálculo de métricas específicas para campañas y fechas particulares.
Comparación de ingresos promedio entre fines de semana y días laborales.
**3. Conclusiones principales**
*Mejores campañas:*
- YouTube Blogger: Generó el mayor ROI y AOV, indicando alta efectividad de las colaboraciones con influencers.
- Facebook Retargeting: Sobresalió en CTR, mostrando el éxito de las estrategias de retargeting.
*Peores campañas:*
-Facebook Lookalike Audience (LAL): Consistentemente mostró un desempeño deficiente en ROI, CTR y otras métricas.
*Tendencias temporales:*
-Los ingresos alcanzaron su punto máximo el 20 de febrero, pero disminuyeron rápidamente después de esa fecha.
-El CTR fue más alto los días 24 y 25 de febrero, pero no se correlacionó directamente con mayores ingresos.
*Eficiencia de costos:*
-Instagram Tier 2: Mostró el menor costo por clic (CPC) y costo por mil impresiones (CPM), siendo muy rentable.
*Áreas de mejora:*
-Facebook LAL necesita reevaluarse para mejorar la segmentación y optimizar los recursos invertidos.
-La relación entre CTR alto y bajos ingresos sugiere que no siempre más clics significan mayor conversión o valor.
*Ingresos por día:*
Los ingresos promedio son ligeramente mayores entre semana (141,914 INR) en comparación con fines de semana (132,593 INR).
**4. Próximos pasos**
- Ajustar las campañas con bajo ROMI y alto costo, como Facebook LAL.
- Implementar análisis más profundos con datos adicionales para entender mejor las correlaciones entre métricas.
- Reforzar las estrategias exitosas como colaboraciones con influencers en YouTube y campañas rentables en Instagram.


***En resumen, el análisis proporciona insights valiosos para optimizar estrategias de marketing y maximizar el retorno de inversión en futuras campañas.***
