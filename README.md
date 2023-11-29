<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Siniestros viales`**</h1>

¡Bienvenidos al último proyecto individual de la etapa de labs! En esta ocasión, deberán hacer un trabajo situándose en el rol de un ***Data Analyst***.
<p align='center'>
<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 500>
<p>

## **Descripción del problema -contexto y rol a desarrollar-**

Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

En el contexto de una ciudad como Buenos Aires, los siniestros viales pueden ser una preocupación importante debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.

Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Estas tasas se calculan, generalmente, como el número de muertes por cada cierto número de habitantes o por cada cierta cantidad de vehículos registrados. Reducir estas tasas es un objetivo clave para mejorar la seguridad vial y proteger la vida de las personas en la ciudad.

Es importante destacar que la prevención de siniestros viales involucra medidas como la educación vial, el cumplimiento de las normas de tráfico, la infraestructura segura de carreteras y calles, así como la promoción de vehículos más seguros. El seguimiento de las estadísticas y la implementación de políticas efectivas son esenciales para abordar este problema de manera adecuada.


### **Contexto**

En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país.
Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.

Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.

### **Rol a desarrollar**

El `Observatorio de Movilidad y Seguridad Vial` (OMSV), centro de estudios que se encuentra bajo la órbita de la ***Secretaría de Transporte*** del Gobierno de la Ciudad Autónoma de Buenos Aires, nos solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.
Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato *xlsx* y contiene dos hojas llamadas: **hechos** y **víctimas**. Asimismo, observarán que incluye otras dos hojas adicionales de diccionarios de datos, que les podrá servir de guía para un mayor entendimiento de la data compartida.

Por su parte, en la sección **Material de apoyo** podrán encontrar más información de interés relativa a los datos disponibilizados y al Observatorio que nos encomienda el trabajo.


## **Propuesta de trabajo -mínimos entregables-**
*Es importante que a la hora de empezar a desarrollar cada item, y tu demo, te ayudes tambien de la [rúbrica de evaluación](https://github.com/soyHenry/DS_LABS/tree/main/Proyectos/Proyectos%20Individuales/PI03/Data14_Homicidios#lo-que-tendremos-en-cuenta-a-la-hora-de-evaluar).* 😄

`EDA` (Exploratory Data Analysis)

Debes realizar un análisis exploratorio de los datos en un notebook. Tienen que estar tus pasos documentados con claridad, con las conclusiones correspondientes en cada gráfico empleado y análisis de lo que vas observando, utilizando celdas Markdown para tal fin. La prolijidad del notebook será un aspecto a evaluar. Es importante que tengas en cuenta que, en muchas oportunidades y trabajos, un EDA constituye un entregable en sí mismo.

En esta línea, hay varios aspectos indispensables que **deben** ser abordados en cualquier Análisis Exploratorio de Datos y tomaremos como punto de partida para evaluar tu performance en este apartado. Entre estos aspectos destacados se encuentran: *búsqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados*. Asimismo, la utilización de gráficos coherentes según la tipología de variable que corresponda resulta esencial.

***En caso de hacer uso de librerías como pandas_profiling, es indispensable acompañar los gráficos con análisis propios.***

`Dashboard`

Debe ser funcional y coherente con el storytelling. El dasbhoard tiene que incluir **filtros**, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos. Es decir, es indispensable que sea **interactivo**. También, se espera que el diseño que implementen facilite la interpretación de la información y su análisis, siendo importante, para ello, la claridad en la presentación de los datos, aspectos inherentes a la esteticidad, elección coherente de los gráficos según las variables a visualizar, entre otros ítems. 

`Análisis` :warning:

No se considerará solamente la producción de gráficos con datos -dashboard-, sino también los análisis y conclusiones que puedan extraer a partir de ellos.

`KPIs`

Debes graficar y medir los 2 KPIs propuestos a continuación, representándolos adecuadamente en el dashboard. A su vez, tambíen tienes que proponer, medir y graficar un tercer KPI que consideres relevante para la temática. 
Los dos KPIs propuestos son:
- *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*.
  
  Definimos a la **tasa de homicidios en siniestros viales** como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.
  Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000
  
- *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*.
  
  Definimos a la **cantidad de accidentes mortales de motociclistas en siniestros viales** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal.
  Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100


  

`MUY IMPORTANTE` repasar qué es un KPI y cómo se diferencia de una métrica convencional. En el material de apoyo tienen lectura que puede ser de ayuda.</small>

`Repositorio de GitHub`

El repositorio debe contener un **Readme** principal donde presenten, en una primera instancia, de forma general **su proyecto** y detallen qué hay en cada archivo/carpeta del propio repositorio. Este Readme no puede ser el mismo de la consigna que nosotros les entregamos.
A su vez, el Readme debe incluir un **reporte de análisis con base en sus dashboards**, así como el análisis y la funcionalidad de los KPIs sugeridos.

### _**Desafíate y no te quedes siendo Junior, sé Junior Advanced**_

Pensando en alcanzar tu Boom 🚀, te recomendamos incorporar los siguientes desafíos para tener un portfolio mucho más completo y competitivo:

- Crear una base de datos en un motor SQL, ingestar el dataset procesado y utilizarla como fuente de datos de su dashboard en Power BI (o la herramienta de visualización que utilice).
- Ejecutar scripts de Python en la herramienta de visualización de datos escogida.
- Cruce de datos con datasets complementarios, ya sea para obtener información nueva o poder comparar la información disponible para todas las plataformas. 

<sub> Nota: la realización de uno o más de estos ítems no es intercambiable con los requerimientos mínimos establecidos en la sección anterior "Propuesta de trabajo". Empiece con esta sección una vez haya cumplido con los requerimientos mínimos, a modo de desafiarse a usted mismo y destacar frente al resto.</sub>

## Fuente de datos
**Obligatorio:**

- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): deberán utilizar el dataset denominado `Homicidios`

**Complementarios:**
- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): pueden usar el dataset de `Lesiones`
- Cualquier dataset de búsqueda propia que complemente y mejore el análisis. Recuerde el uso de [APIs y WebScrapping](https://www.students.soyhenry.com/classes/95?cohortId=124&videoOrdinal=2)

<h1>Lo que tendremos en cuenta a la hora de evaluar</h1>

Serás evaluado en dos grandes áreas  `Tech` y `Soft`!

Ambas con igual peso entre si y ambas deben ser aprobatorias para tener la calidad de aprobado en este PIDA. Ten presente que una nota minima para aprobar significa tener TODOS los items como "Bueno" 👌
A continuacion te facilitamos nuevamente la [rúbrica de evaluación](https://docs.google.com/spreadsheets/d/e/2PACX-1vTV3zL1aeGRlbXkiy5012GWbDBMseA4iziMXs597TZfgaYgazjxZDx_-q6L4s9io3JW4UPHcZs_XNyz/pubhtml) con la que seras evaluado por tu corrector@. Recuerda que el feedback de tu corrector@ no es en ningun momento un indicativo de tu nota. Si tienes alguna duda durante tu DEMO, pidele a tu corrector@ que te aclare claramente cuales son los objetivos de aprendizaje no cumplidos.

Esperamos que te sirva de guia de aprendizaje, y recuerda que no se trata solo de cumplir requisitos, sino de destacar en cada nivel 🚀 💛


## Material de apoyo
- [Notas para el uso del dataset de homicidios de siniestros viales de la CABA](https://cdn.buenosaires.gob.ar/datosabiertos/datasets/transporte-y-obras-publicas/victimas-siniestros-viales/NOTAS_HOMICIDIOS_SINIESTRO_VIAL.pdf)
- [Observatorio de Movilidad y Seguridad Vial de la Ciudad Autónoma de Buenos Aires](https://buenosaires.gob.ar/observatorio-de-movilidad-y-seguridad-vial)


#### Tech
- [Repaso de clase sobre EDA](https://www.students.soyhenry.com/classes/100?cohortId=106&videoOrdinal=1)
- [Code Review: **Interactividad** Dashboard, Patron Z, **Tooltips**](https://www.students.soyhenry.com/classes/93?cohortId=124&videoOrdinal=2)
- [KPI's 4 students](https://docs.google.com/document/d/1DI0ZVgHfOfjgnXGhi8jEKzwCIjtUdgRUDe-qiiGGq8E/edit)
- [Code Review: DAX y **medidas calculadas**](https://www.students.soyhenry.com/classes/96?cohortId=124&videoOrdinal=2)

#### Soft
- ¡Todos los Workshops de esta etapa serán de gran utilidad para tener un proyecto exitoso!




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

