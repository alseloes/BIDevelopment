# GUÍA DE BI DEVELOPMENT

## POWER BI DOCUMENTACIÓN

* [Documentación de introducción a Power BI](https://learn.microsoft.com/es-es/power-bi/fundamentals/)
* [Documentación de Power BI](https://learn.microsoft.com/es-es/power-bi/)
* [La interfaz de usuario de Power Query](https://learn.microsoft.com/es-es/power-query/power-query-ui#the-query-ribbon)
* [Guía sobre la fecha y hora automáticas en Power BI Desktop](https://learn.microsoft.com/es-es/power-bi/guidance/auto-date-time)
* [Tipos de datos en Power BI Desktop](https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-data-types)
* [Dar forma y combinar datos en Power BI Desktop](https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-shape-and-combine-data)
* [Power BI Premium Per User](https://learn.microsoft.com/en-us/fabric/enterprise/powerbi/service-premium-per-user-faq)
* [Power BI licensing guide for organizations](https://learn.microsoft.com/en-us/fabric/enterprise/powerbi/service-admin-power-bi-licensing)
* [Power BI Service](https://app.powerbi.com/home?experience=power-bi)

## OTRO MATERIAL SOBRE POWER BI

* Youtube (por ver): [Curso de Power BI desde CERO (Actualizado 2025)](https://www.youtube.com/watch?v=vcU4V6wE8Js&t=624s)
* Youtube (por ver): [Power BI Opportunities Dashboard Tutorial (2025) | Visuals, KPI Cards, Filters & AI Q&A Explained](https://www.youtube.com/watch?v=Kiz4EyAihEk)
* Youtube (por ver): [Power BI KPI Cards for Beginners | Step-by-Step Tutorial (2025)](https://www.youtube.com/watch?v=rbWZllXMGYU)
* Medium: [Next level KPI in Power BI](https://medium.com/microsoft-power-bi/next-level-kpi-in-power-bi-6d9dc7825ee4)
* Zebra BI: [How to create a KPI dashboard in Power BI to make smarter decisions faster](https://zebrabi.com/create-the-best-kpi-dashboard/)
* Zoomcharts: [How to enhance KPI cards in Power BI](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/blog/kpi-cards-in-power-bi)
* Udemy: [Power BI TOTAL en 14 Días - Analista de Datos Avanzado](https://www.udemy.com/course/power-bi-total/?couponCode=KEEPLEARNING)
* OJO!! Coursera: [Unlock the Power of Data with Power BI](https://www.coursera.org/learn/unlock-the-power-of-data-with-power-bi/paidmedia?utm_medium=sem&utm_source=gg&utm_campaign=b2c_latam_microsoft-power-bi-and-power-platform-productivity_microsoft_ftcof_specializations_px_dr_bau_gg_sem_pr-bd_s1-v2_en_m_hyb_25-02_x&campaignid=22192535916&adgroupid=178366273630&device=c&keyword=&matchtype=&network=g&devicemodel=&creativeid=731819527162&assetgroupid=&targetid=dsa-2398364493316&extensionid=&placement=&gad_source=1&gad_campaignid=22192535916&gbraid=0AAAAADdKX6Yyom4bZ4VtoFCmQPgG6pMSk&gclid=Cj0KCQiAgbnKBhDgARIsAGCDdldgqChg5Sjvohk4k4m7ODN-vkx4ZrFQjOjULVp2E6SOHcChfq17YSIaArgVEALw_wcB)
* OJO!! Coursera: [Certificado profesional de Analista de datos de Microsoft Power BI](https://www.coursera.org/professional-certificates/microsoft-power-bi-data-analyst)
* Coursera: [Programa especializado: BI Essentials for Finance Analysts (Power BI Edition)](https://www.coursera.org/specializations/bi-essentials-for-finance-professionals-powerbi)
* Datacamp: [https://www.datacamp.com/es/pricing?period=yearly](https://www.datacamp.com/es/pricing?period=yearly)

## CURSILLOS DE POWER BI

* Todos los cursos, rutas de aprendizaje y módulos [Power BI](https://learn.microsoft.com/es-es/training/browse/?products=power-bi)
* [Introducción a la compilación con Power BI](https://learn.microsoft.com/es-es/training/modules/get-started-with-power-bi/)
* RUTA (por completar): [Introducción al análisis de datos de Microsoft](https://learn.microsoft.com/es-es/training/paths/data-analytics-microsoft/)
* RUTA (por completar): [Preparar y visualizar datos con Microsoft Power BI](https://learn.microsoft.com/es-es/training/paths/prepare-visualize-data-power-bi/)
* RUTA (por completar): [Preparación de datos para el análisis con Power BI](https://learn.microsoft.com/es-es/training/paths/prepare-data-power-bi/)

## NOTAS

* Los informes en Power BI se crean en Power BI desktop, pero se pueden publicar en Servicio Power BI (plataforma en línea) y visualizar en Power BI Mobile (aplicación móvil multiplataforma)
* El flujo de Power BI es el siguiente:

    1) Conectarse a los datos con Power BI Desktop.
    2) Transformar los datos con el editor de Power Query (incluido en Power BI Desktop).
    3) Modelar los datos con Power BI Desktop.
    4) Crear visualizaciones e informes con Power BI Desktop.
    5) Publicar el informe en el servicio Power BI.
    6) Distribuir y administrar informes en el servicio Power BI.

    El servicio Power BI también le permite crear paneles globales que exploran en profundidad los informes, así como aplicaciones para agrupar fácilmente informes relacionados para que los usuarios los vean en un formato sencillo.

* Ejemplos y explicación de Power BI Service [acá](https://learn.microsoft.com/es-es/training/modules/get-started-with-power-bi/4-exercise-touring-and-using-power-bi)

### POWER QUERY

* El editor de Power Query en Power BI Desktop permite dar forma (transformar) a los datos importados.
* En el panel de PQ, en el lado izquierdo aparece el panel de **Consultas**
* En el lado derecho los pasos **Configuración de la consulta**

## PASOS PARA CREAR UN DASHBOARD

### Limpiar, transformar y cargar datos en Power BI

1) Identificar encabezados y nombres de columnas. Podría ser necesario ([Rev](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/2-shape-data)):
    * Promocionar encabezados.
    * Cambiar el nombre de las columnas.
    * Quitar filas superiores.
    * Anular dinamización de columnas.
    * Dinamizar columnas.
2) Simplificación de la estructura de datos ([Rev](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/3-data-structure)):
    * Cambiar el nombre de las consultas.
    * Reemplazar valores.
    * Reemplazar los valores `null`: algunas veces es necesario reemlazar los valores `null` por  cero para evitar errores en operaciones.
    * Quitar los duplicados: es posible que sea necesario eliminar duplicados para crear una tabla con "categorías" únicas para usarlas en el modelo semántico. En este caso, se recomienda copiar la tabla antes de quitar los duplicados. La opción Copiar se encuentra en la parte superior del menú contextual. Copiar la tabla antes de quitar los duplicados proporcionará una comparación de las tablas y permitirá usar ambas si es necesario.
    * Procedimientos recomendados para asignar nombres a tablas, columnas y valores: es recomendable usar el lenguaje y las abreviaturas que se usen habitualmente en la organización, algo con lo que todos los usuarios estén de acuerdo y vean como terminología común. Al reemplazar valores, intente imaginar cómo aparecerán esos valores en el informe. Los valores demasiado largos podrían ser difíciles de leer y no caber en un objeto visual. Los valores demasiado cortos podrían ser difíciles de interpretar. Evitar los acrónimos en los valores, siempre que el texto quepa en el objeto visual.
3) Evaluación y cambio de tipos de datos de columna ([Rev](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/4-column-data-types)):

    **Implicaciones relacionadas con la determinación incorrecta del tipo de datos**: Los tipos de datos incorrectos impedirán la creación de determinados cálculos, la derivación de jerarquías o la creación de relaciones adecuadas con otras tablas. En un campo de fecha es la incapacidad de crear una jerarquía de fechas, que permite analizar los datos de manera anual, mensual o semanal.
    * Cambiar el tipo de datos de las columnas: este procedimiento se realiza en el editor de Power Query, puede hacerse mediante la cinta de opciones/Transform o mediante "click derecho" sobre símbolo izquierdo en encabezado de columna. Estos pasos quedarán guardados como paso programado en la **Configuración de la consulta** como "Tipo cambiado".
4) Combinación de varias tablas en una sola [Rev](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/5-combine-tables):

    La capacidad de combinar consultas es muy eficaz, ya que permite anexar o combinar diferentes tablas o consultas. Podrá combinar varias tablas en una sola en las siguientes circunstancias:

    * Existen demasiadas tablas, lo que dificulta navegar por un modelo semántico demasiado complicado.
    * Hay varias tablas con un rol parecido.
    * Hay una tabla que solo tiene una o dos columnas y estas se podrían incluir en otras tablas.
    * Le gustaría usar varias columnas de tablas diferentes en una columna personalizada.

    Las tablas se pueden combinar de dos maneras distintas: la combinación y la anexión:

    * Anexar consultas:
        * Se debe tener una columna que sirva de Key entre las consultas.
        * Las columnas que se necesiten en la tabla combinada deben tener el mismo nombre en las tablas de datos originales, a fin de ver una vista agrupada.
        * Elimine las columnas sobrantes de las consultas.

        El proceso se hace por inicio/Anexar consultas (como nuevas o en una tabla existente).
    * Combinación de consultas: consiste en combinar los datos de varias tablas en una sola, basándose en una columna que sea común entre las tablas (similar a `JOIN` en SQL).

5) Generación de perfiles de datos [Rev](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/6-profile-data):

    Consiste en analizar los matices de los datos: la determinación de anomalías, el examen y el desarrollo de las estructuras de datos subyacentes y la consulta de estadísticas de datos, como recuentos de filas, distribuciones de valores, valores mínimos y máximos, promedios, etc. Este concepto es importante porque permite dar forma a los datos y organizarlos para que la interacción con los datos y la identificación de su distribución no sea complicada, lo que facilita el trabajo con los datos en el frontend para el desarrollo de elementos de informes.

    * Examen de las estructuras de datos: Modelo
    * Búsqueda de anomalías y estadísticas de datos: Vista/Distribución de columnas, Calidad de columnas y Perfil de columnas

6) Uso del Editor avanzado para modificar el código M:

    Cada vez que da forma a los datos en Power Query, está creando un paso en el proceso de Power Query, los cuales se pueden reordenar, eliminar y modificar donde tenga sentido

**Recurso adicional:** [Laboratorio - Cargar datos en Power BI Desktop](https://learn.microsoft.com/es-es/training/modules/clean-data-power-bi/8-lab)
