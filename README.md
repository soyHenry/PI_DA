<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`MOOCs`**</h1>

¡Bienvenidos al último proyecto individual de la etapa de labs! En esta ocasión, deberán hacer un trabajo situándose en el rol de un ***Data Analyst***.
<p align='center'>
<img src = 'https://thumbs.dreamstime.com/b/mooc-massive-open-online-course-learning-vector-219370657.jpg' height = 200>
<p>


## **Descripción del problema (Contexto y rol a desarrollar)**

### **Contexto**

Los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, cuando el profesor Sebastian Thrun comenzó con la transmisión online de su curso introductorio a la Inteligencia Artificial. Poco tiempo después, Thrun fundó Udacity y con el pasar de los años se han ido sumando otras plataformas como edX y Coursera, brindando servicios similares: acceso a contenido específico, de calidad y de manera práctica, desde la comodidad del hogar. Muchas de estas plataformas tienen contenido gratuito, mientras que el modelo de negocio en general se basa en el pago de suscripciones recurrentes para acceso general o únicas, para acceder a certificaciones o a cursos premium.
Con el aumento de la popularidad de los MOOCs, no solo han aparecido nuevas plataformas privadas como las mencionadas anteriormente, sino que también muchas universidades y organizaciones sin fines de lucro han sumado a la oferta haciendo el mercado mucho más competitivo. En este contexto, resulta imperante para cada plataforma ajustar sus modelos de negocio, los cursos y el contenido que se ofrece en ellos para lograr captar y retener a la mayor cantidad de clientes.

### Rol a desarrollar

Nuestra PM se dirigió a nosotros con un nuevo ticket de trabajo. Una startup de tecnología está interesada en sumarse al mercado de cursos online, pero de una manera eficiente, por lo que compró datasets de posibles competidores para analizar y sacar conclusiones de los datos recolectados.

Ellos solicitan segmentar el nivel de ventas según precio, idioma, nivel y rating de cada curso, con el objetivo analizar qué tanto influyen dichas variables en la demanda del producto vendido.

Por otra parte, se nos solicita un Word Cloud de las palabras clave que más se repiten dentro del título -se pueden añadir otras variables de nuestro interés-. 
 
Con el fin de monitorear la eficacia de los objetivos de la empresa, se le pide visualizar el siguiente KPI y **establecer otros tres KPIs** producto de su análisis y que se puedan **visualizar** en el dashboard. 
+ Tasa de conversión de inscriptos gratuitos a inscriptos pagados -calculado como el número de inscriptos en cursos pagados / número de inscriptos en cursos gratuitos * 100-. El objetivo a futuro propuesto por la empresa es evaluar si en la tendencia se logra incrementar esta tasa en un 15% en comparación con el año anterior. Actualmente, para este cálculo, usted posee la información de Udemy, pero como desafío extra, se le pide buscar datasets complementarios y evaluar este KPI en las distintas plataformas. 

Por último, se nos pide una demo en un rango de tiempo de no más de 10 min donde presentemos nuestro dashboard junto con los análisis y conclusiones pertinentes.

## **Propuesta de trabajo (indicaciones)**

`EDA` (Exploratory Data Analysis)

Deben realizar un análisis exploratorio de los datos en un notebook. Tienen que estar sus pasos documentados con claridad, con las conclusiones correspondientes en cada gráfico empleado y análisis de lo que van observando, utilizando celdas Markdown para tal fin. La prolijidad del notebook será un aspecto a evaluar. Es importante que tengan en cuenta que, en muchas oportunidades y trabajos, un EDA constituye un entregable en sí mismo.

***En caso de hacer uso de librerías como pandas_profiling, es indispensable acompañar los gráficos con análisis propios.***

`Dashboard`

Debe ser funcional y coherente con el storytelling. El dasbhoard tiene que incluir filtros, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos. Es decir, es indispensable que sea interactivo. También, se espera que el diseño que implementen facilite la interpretación de la información y su análisis, siendo importante, para ello, la claridad en la presentación de los datos, aspectos inherentes a la esteticidad, elección coherente de los gráficos según las variables a visualizar, entre otros ítems. 

`Análisis` :warning:

No se considerará solamente la producción de gráficos con datos -dashboard-, sino también los análisis y conclusiones que puedan extraer a partir de ellos.

`KPIs`

Se deben sugerir 3 KPIs y mostrarse en el dashboard. Téngase presente que deben tener relación con la historia que usted está contando. Asimismo, se espera que en la presentación explique el análisis y la funcionalidad de los KPIs sugeridos.

`MUY IMPORTANTE` repasar qué es un KPI y cómo se diferencia de una métrica convencional. En el material de apoyo tienen lectura que puede ser de ayuda.</small>

`Repositorio de GitHub`

El repositorio debe contener un **Readme** principal donde presenten, en una primera instancia, de forma general **su proyecto** y detallen qué hay en cada archivo/carpeta del propio repositorio. Este Readme no puede ser el mismo de la consigna que nosotros les entregamos.
A su vez, el Readme debe incluir un reporte de análisis con base en sus dashboards, así como el análisis y la funcionalidad de los KPIs sugeridos.

### _**Desafíate y no te quedes siendo Junior, sé Junior Advanced**_

Pensando en alcanzar tu Boom, te recomendamos incorporar los siguientes desafíos para tener un portfolio mucho más completo y competitivo:

- Crear una base de datos en un motor SQL, ingestar el csv procesado y utilizarla como fuente de datos de su dashboard en Power BI (o la herramienta de visualización que utilice).
- Ejecutar scripts de Python en la herramienta de visualización de datos escogida.
- Cruce de datos con datasets complementarios, ya sea para obtener información nueva o poder comparar la información disponible para todas las plataformas. 

<sub> Nota: la realización de uno o más de estos ítems no es intercambiable con los requerimientos mínimos establecidos en la sección anterior "Propuesta de trabajo". Empiece con esta sección una vez haya cumplido con los requerimientos mínimos, a modo de desafiarse a usted mismo y destacar frente al resto.</sub>

## Fuente de datos:
- [Datasets proporcionados ](https://drive.google.com/drive/folders/1TS76ok6giW7D_l5vc-zu5-cBU_dH3P5H?usp=sharing)
- Otros datasets de búsqueda propia.

<br>

<h1>Lo que tendremos en cuenta a la hora de evaluar:</h1>

Serás evaluado en dos grandes áreas, ambas con igual peso entre si: `Tech` y `Soft`!

**Las habilidades técnicas -Tech-** para este proyecto de analytics incluyen el tipo de herramientas utilizadas para la realización del dashboard (herramientas de **Business Intelligence** y/o DataViz), elección de **gráficas pertinentes** para la representación del dato y un dashboard **efectivo** (organización, uso de filtros y criterios estéticos y de diagramación -dónde se ubican los filtros y visualizaciones, etc- :nail_care:)

**Las habilidades blandas -Soft-** para este proyecto tendrán en cuenta la **puntualidad y preparacion para la demo**, su **comunicación oral y storytelling**, la forma en que cuentas tu historia (¿los datos duros que presentas son **útiles** para tu audiencia?) y, finalmente -esto es MUY importante-, :warning:**EL ANÁLISIS**:warning: (¿brindas un contexto?, ¿haces comparaciones con otros datos?, ¿tienes conclusiones interesantes y realizas análisis no triviales?).

<sub>**Spoiler**: te vamos a dar feedback y también vamos a evaluar tu capacidad de recepción :stuck_out_tongue: </sub>


## Material de apoyo
- ¡Todos los Workshops de esta etapa serán de gran utilidad para tener un proyecto exitoso!
- [Como hacer un EDA](https://medium.com/nerd-for-tech/how-to-do-some-basic-eda-a-guide-for-dummies-d76d9a82242c)
- [Como ejecutar scripts en power BI](https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-python-scripts)
- [Pypy: WordCloud](https://pypi.org/project/wordcloud/)
- [KPI's 4 students](https://docs.google.com/document/d/1DI0ZVgHfOfjgnXGhi8jEKzwCIjtUdgRUDe-qiiGGq8E/edit) y [Define your KPIs](https://medium.com/swlh/define-your-kpis-1a2072f1435)
- [Repaso de clase sobre EDA](https://www.students.soyhenry.com/classes/100?cohortId=106&videoOrdinal=1)


## ***Recomendaciones finales***

¡No debes mostrar nada de código en la exposición! Te recomendamos el workshop *From Data to Viz* para que te quede más claro la dinámica y lo que se espera de tu demo.

Recordamos que sean puntuales y prueben el correcto funcionamiento de las herramientas empleadas ***antes*** de ingresar a la meet.

La **DEMO**, donde defenderás tu proyecto, se realizará el día jueves o viernes. Debes estar atent@ a tu *calendar* para ver qué día y horario te corresponde. 

Tendrá una duración total máxima de 30 minutos, de los cuales **sólo 10 minutos serán para su presentación**.  Es importante que sepa **gestionar bien tu tiempo** y tenga un speech ya preparado de 10 minutos, ya que el tiempo restante será dedicado a la corrección, revisión de repositorio y feedback por parte del Henry Mentor.



## Disclaimer
De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulen un entorno laboral, en el cual se trabajen diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).
  
  
<p align='center'>
<img src ="https://media.giphy.com/media/BpGWitbFZflfSUYuZ9/giphy.gif" height=250>
<p>

