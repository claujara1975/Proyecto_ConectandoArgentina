PROYECTO INDIVIDUAL Nº2: "CONECTANDO ARGENTINA: ANÁLISIS DEL ACCESO Y EXPANSIÓN A INTERNET"
📌 Introducción
Este proyecto aborda un análisis profundo del acceso y crecimiento de los servicios de telecomunicaciones en Argentina, con especial énfasis en el servicio de internet. Como analista de datos, he desarrollado un EDA que permite comprender las tendencias y el estado actual del sector, y además, he implementado KPIs clave para evaluar la performance del mercado y sugerir estrategias de mejora.

🌐 Contexto
El acceso a internet se ha convertido en un pilar esencial para el desarrollo de las sociedades modernas. En Argentina, las telecomunicaciones han crecido considerablemente, con un registro de 62,12 millones de conexiones en 2020. Sin embargo, comprender y mejorar el acceso en diferentes regiones sigue siendo un desafío, particularmente en la expansión y optimización de servicios.

🎯 Objetivo del Proyecto
El proyecto busca analizar datos relacionados con el acceso a internet y otros servicios de telecomunicaciones en Argentina, centrándose en el desarrollo y cumplimiento de indicadores clave de rendimiento (KPIs) que reflejen el crecimiento y las oportunidades de mejora.

📂 EDA (Análisis Exploratorio de Datos)
El análisis exploratorio se inició cargando los datos desde el archivo internet.xlsx, el cual contenía 15 hojas con información relevante. Estas hojas se transformaron en archivos CSV para una mejor manipulación y estandarización. El EDA incluyó:

Proceso de Análisis:
Revisión de los datos: Exploración y evaluación de la calidad de los datos.
Limpieza: Eliminación de valores nulos, duplicados y outliers.
Visualización: Uso de gráficos de barras, histogramas y boxplots para entender la distribución de los datos.
Análisis de correlación: Matriz de correlación para identificar relaciones significativas entre variables.
Ajuste por inflación: Se ajustaron los ingresos a la inflación de 2014 a 2023 para un análisis más realista.
Los archivos trabajados incluyeron:

Penetración-hogares.csv
Accesos Por Tecnología.csv
Penetración-poblacion.csv
Totales Acceso Por Tecnología.csv
Ingresos.csv
📊 KPIs Implementados
1. Aumento del Acceso a Internet
Objetivo: Incrementar el acceso a internet en un 2% por cada 100 hogares en cada provincia en el próximo trimestre.
Fórmula:
Tasa de Crecimiento de Acceso
=
(
Nuevo acceso
−
Acceso actual
Acceso actual
)
×
100
Tasa de Crecimiento de Acceso=( 
Acceso actual
Nuevo acceso−Acceso actual
​
 )×100
2. Crecimiento de Accesos por Tecnología de Conexión
Objetivo: Medir el crecimiento por tecnología con una meta del 5% en el próximo trimestre.
Fórmula:
Crecimiento por Tecnolog
ı
ˊ
a
=
(
Accesos nuevos
−
Accesos actuales
Accesos actuales
)
×
100
Crecimiento por Tecnolog 
ı
ˊ
 a=( 
Accesos actuales
Accesos nuevos−Accesos actuales
​
 )×100
3. Penetración del Servicio de Internet por Población
Objetivo: Incrementar en un 3% la penetración del servicio.
Fórmula:
I
ˊ
ndice de Penetraci
o
ˊ
n
=
(
Accesos por 100 hogares
Poblaci
o
ˊ
n total
)
×
100
I
ˊ
 ndice de Penetraci 
o
ˊ
 n=( 
Poblaci 
o
ˊ
 n total
Accesos por 100 hogares
​
 )×100
4. Variación de Ingresos por Servicios de Internet
Objetivo: Lograr un aumento del 4% en ingresos correlacionado con el aumento de accesos.
Fórmula:
Variaci
o
ˊ
n de Ingresos
=
(
Ingresos nuevos
−
Ingresos actuales
Ingresos actuales
)
×
100
Variaci 
o
ˊ
 n de Ingresos=( 
Ingresos actuales
Ingresos nuevos−Ingresos actuales
​
 )×100
🛠️ Herramientas Utilizadas
Visual Studio Code: Para el manejo de código y documentación.
Python: Para el análisis de datos.
Power BI: Para la creación de un dashboard interactivo que representa los KPIs.
📈 Dashboard en Power BI
El dashboard visualiza de forma interactiva los KPIs definidos y muestra las tendencias por provincia y trimestre, facilitando la toma de decisiones basada en datos.

📝 Conclusiones
El análisis demostró variaciones significativas en la penetración y acceso a internet, revelando áreas críticas para el desarrollo y mejoras. Las recomendaciones basadas en los KPIs ofrecen una guía estratégica para la expansión de los servicios.

🔗 Enlaces de Interés
Repositorio del Proyecto
