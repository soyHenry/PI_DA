<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Accidentes aéreos`**</h1>

<p align="center">
<img src="https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fcdn.pixabay.com%2Fphoto%2F2016%2F09%2F15%2F16%2F13%2Fairplane-1671967_1280.jpg"  height=300>
</p>

¡Bienvenidos al último proyecto individual de la etapa de labs! En esta ocasión, deberán hacer un trabajo situándose en el rol de un ***Data Analyst***.


## **Contexto**

Los accidentes aéreos son eventos inesperados e indeseados que involucran aeronaves y se producen daños físicos a personas o a la propia aeronave. Un accidente aéreo puede involucrar cualquier tipo de aeronave, incluyendo aviones comerciales, aviones privados, helicópteros, planeadores y globos aerostáticos.

Los accidentes aéreos pueden ser causados por diversos factores, como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Y en cuanto a sus consecuencias, pueden ser tanto en términos de pérdidas humanas como económicas. 

Es por eso que la industria de la aviación, las autoridades reguladoras y los investigadores trabajan incansablemente para mejorar la seguridad de la aviación y prevenir futuros accidentes.

Por esto, el análisis de datos históricos de accidentes aéreos es fundamental para mejorar la seguridad de la aviación. La recopilación y el análisis sistemático de los datos de accidentes pueden ayudar a los investigadores a identificar patrones, tendencias y factores contribuyentes que podrían llevar a mejoras en la seguridad, desde ayudar a mejorar la capacitación de los pilotos y el personal de mantenimiento, así como a mejorar el diseño y la fabricación de aviones y equipos de aviación.


## **Rol a desarrollar**

La **Organización de Aviación Civil Internacional (OACI)** es una organización intergubernamental que se dedica a promover la seguridad y eficiencia de la aviación civil internacional. Como parte de su misión, la OACI ha decidido llevar a cabo un proyecto de data analytics para analizar los accidentes aéreos de aviones en todo el mundo.

El objetivo del proyecto es recopilar, analizar y visualizar datos relevantes sobre accidentes aéreos para identificar patrones y tendencias en la seguridad de la aviación civil. El proyecto se llevará a cabo mediante la utilización de técnicas de data analytics que usted ya conoce, para procesar y analizar datos de accidentes aéreos.

Para llevar a cabo el proyecto, la OACI le proporciona los datos de accidentes de aviones, pero lo insta a usted, como parte del equipo de especialistas en data analytics, a que incluya otras fuentes de datos, como bases de datos gubernamentales, informes de la industria, informes de los medios de comunicación y otros recursos disponibles públicamente.

El resultado final del proyecto será un dashboard interactivo que permita a los usuarios explorar los datos y obtener información sobre accidentes específicos, el cual deberá utilizar para presentar los hallazgos obtenidos de la información analizada.

Dentro de este trabajo, con el fin de entender los datos y alinearlos con los objetivos de la organización, se le pide **visualizar** en su dashboard el siguientes KPI, junto a otros 3 adicionales que usted debe generar. 

+ Reducir en 5% la tasa de mortalidad a nivel anual, siendo el número de fallecidos en los accidentes aéreos respecto al total de personas en los vuelos involucrados.

*Nota: En la sección de material de apoyo se puede encontrar más información sobre los KPIs.*

Se espera que el reporte y el dashboard proporcionen información valiosa a la industria de la aviación civil, los reguladores gubernamentales y otros interesados en la seguridad de la aviación. Con esta información, se podrán desarrollar medidas preventivas para reducir la incidencia de accidentes aéreos y mejorar la seguridad en la aviación civil a nivel mundial.

## **Propuesta de trabajo**
 
 **Requerimientos de aprobación**

#### `Análisis Exploratorio de los datos` (_Exploratory Data Analysis = EDA_)

El reporte debe incluir un resumen de estadísticas descriptivas de los datasets, análisis univariados (por ejemplo, distribución de variables numéricas), análisis bivariados (correlación entre variables numéricas y/o categóricas) y **cualquier análisis que le ayude al mejor entendimiento de los datos** (encontrar patrones, outliers y/o anomalías, entre otros). El reporte debe presentarse en un notebook (_.ipynb_) con adecuado uso de markdowns y comentarios.
  
_En caso de hacer uso de librerias como pandas_profiling, es indispensable acompañar los graficos con análisis propios._

#### `Dashboard`

Debe ser funcional y coherente con el análisis y la historia que vayan a relatar. **El archivo debe estar en su repositorio** (.pbix, .py o el que aplique).

#### `KPIs`

Se deben sugerir 3 KPIs y deben aparecer en el dashboard. Tenga en cuenta que deben tener relación con la historia que está contando. Asimismo, se espera que en la presentación explique el análisis y la funcionalidad de los KPIs sugeridos.

#### :warning: `Análisis` :warning:

No se calificará solamente la producción de gráficos con datos (dashboard), sino también los **análisis y conclusiones** que encuentren en ellos.
  
#### `Repositorio de GitHub`

El repositorio debe contener un README principal donde se presente de forma general **su proyecto**. Presentar como propio el readme proporcionado por Henry será considerado como **insuficiente** para cumplir con este requerimiento.

### _**Desafíate y no te quedes siendo Junior, sé Junior Advanced**_

Pensando en alcanzar tu Boom, te recomendamos incorporar los siguientes desafíos para tener un portfolio mucho más completo y competitivo:

- Crear una base de datos en un motor SQL, ingestar el csv procesado y utilizarla como fuente de datos de su dashboard en Power BI (o la herramienta de visualización que utilice).
- Redactar un reporte de análisis con base en sus dashboards e incluirlo en el readme de sus repositorios. También debe incluir el análisis y la funcionalidad de los KPIs sugeridos.
- Ejecutar scripts de python en la herramienta de visualización de datos escogida.
- Cruce de datos con datasets complementarios.

<sub> Nota: la realización de uno o más de estos ítems no es intercambiable con los requerimientos mínimos establecidos en la sección anterior "Propuesta de trabajo". Empiece con esta sección una vez haya cumplido con los requerimientos mínimos, a modo de desafiarse a usted mismo y destacar frente al resto.</sub>

## Fuente de datos:
**Obligatorio:**

- Dataset principal, incluido en el repositorio del proyecto.

**Complementario:**
- [National Transportation Safety Board](https://www.ntsb.gov/safety/data/Pages/Data_Stats.aspx)
- [Aviation Safety Network](https://aviation-safety.net/database/)
- [Federal Aviation Administration](https://www.faa.gov/data_research/accident_incident)
- Cualquier dataset de búsqueda propia que complemente y mejore el análisis.



<h1>Lo que tendremos en cuenta a la hora de evaluar:</h1>

Serás evaluado en dos grandes áreas, ambas con igual peso entre si: `Tech` y `Soft`!

**Las habilidades técnicas (Tech)** para este proyecto de analytics incluyen el tipo de herramientas utilizadas para la realización de dashboard (herramientas de **Business Intelligence** y/o DataViz), elección de **gráficas pertinentes** para la representación del dato y un dashboard **efectivo** (organización, uso de filtros y criterios estéticos y de diagramación dónde se ubican los filtros y visualizaciones, títulos adecuados, estandarización de idiomas, entre otros).

**Las habilidades blandas (Soft)** para este proyecto tendrán en cuenta la **puntualidad y preparación para la demo**, su **comunicación oral y storytelling**, la forma en que cuentas tu historia (¿los datos duros que presentas son **útiles** para tu audiencia?) y finalmente (esto es MUY importante) :warning:**EL ANÁLISIS**:warning: (¿brindas un contexto?, ¿haces comparaciones con otros datos?, ¿tienes conclusiones interesantes y realizas análisis no triviales?).

<sub>**Spoiler**: Te vamos a dar feedback y también vamos a evaluar tu capacidad de recepción a este :stuck_out_tongue: </sub>


## Material de apoyo
- ¡Todos los Workshops de esta etapa serán de gran utilidad para tener un proyecto exitoso!
- [Como hacer un EDA](https://medium.com/nerd-for-tech/how-to-do-some-basic-eda-a-guide-for-dummies-d76d9a82242c)
- [Define your KPIs](https://medium.com/swlh/define-your-kpis-1a2072f1435)
- [Como ejecutar scripts en power BI](https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-python-scripts)



## ***Recomendaciones finales***

¡No debes mostrar nada de código en la exposición! Te recomendamos el workshop *From Data to Viz* para que te quede más claro la dinámica y lo que se espera de tu demo.

Recordamos que seas puntuales y pruebes el correcto funcionamiento de las herramientas empleadas antes de ingresar a la meet.

La **DEMO**, donde defenderás tu proyecto, se realizará el día jueves o viernes. Debes estar atent@ a tu *calendar* para ver qué día y horario te corresponde. 

Tendrá una duración total máxima de 30 minutos, de los cuales **sólo 10 minutos serán para su presentación**.  Es importante que sepas **gestionar bien tu tiempo** y tengas un speech ya preparado de 10 minutos, ya que el tiempo restante será dedicado a la corrección, revisión de repositorio y feedback por parte del Henry Mentor.


## Disclaimer
De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulan un entorno laboral, en el cual se trabajan diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).
  
<p align='center'>
<img src ="https://media.giphy.com/media/BpGWitbFZflfSUYuZ9/giphy.gif" height=250>
<p>
