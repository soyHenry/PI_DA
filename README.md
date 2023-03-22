<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Mercado bursátil`**</h1>

¡Bienvenidos al último proyecto individual de la etapa de labs! En esta ocasión, deberán hacer un trabajo situándose en el rol de un ***Data Analyst***.
<p align='center'>
<img src = 'https://m.foolcdn.com/media/dubs/original_images/Intro_slide_-_digital_stock_chart_going_up_-_source_getty.jpg' height = 200>
<p>


## **Descripción del problema (Contexto y rol a desarrollar)**

### **Contexto**

Cuando surgió la pandemia causada por el COVID-19, el mercado financiero internacional llevaba años de relativa tranquilidad posterior al desplome de 2008 con la burbuja de la deuda inmobiliaria estadounidense. La pandemia, un evento considerado por muchos analistas como un “cisne negro”, (sucesos que no habría habido forma alguna de predecir y con consecuencias graves), tuvo implicaciones trascendentales no sólo en la salud de las personas. 
Las medidas adoptadas por los gobiernos para afrontarla afectaron otros ámbitos, por ejemplo, los confinamientos cortaron por períodos más o menos extendidos casi todas las líneas de suministros perjudicando la producción global de bienes y servicios; o la generación de nuevas tendencias “remote first” llevaron al crecimiento exponencial de empresas de consumo masivo online o de herramientas que permitieran tal filosofía de trabajo, como Zoom. 
  
Este cambio se tradujo en el mercado en un movimiento muy marcado de inversiones hacia empresas tecnológicas, mientras que las consideradas tradicionales se vieron más o menos desfavorecidas. Sin embargo, mucha gente dependiente de la presencialidad vio reducidos sus ingresos al punto de ver comprometida su subsistencia por lo que la mayoría de los gobiernos adoptó medidas de asistencia, recurriendo a la emisión monetaria para tales fines. 

Esto llevó a una hiper liquidez a nivel global, cuyos efectos vemos aún al día de hoy: la Reserva Federal realiza hace tiempo aumentos de las tasas de interés que paga por sus bonos, a un ritmo no visto desde hace décadas, en un intento por bajar la aún creciente inflación. Esto, la incertidumbre con respecto a la situación económica mundial y el impacto de otros eventos como la guerra Ucrania-Rusia y el estrés que la misma salpicó a las relaciones geopolíticas internacionales, despertaron una migración al dólar estadounidense, en busca de refugio.

La suba de tasas por parte de la FED y la migración al dólar causaron su fortalecimiento, generando que muchos países en vías de desarrollo vieran encarecidas sus deudas en dólares, y empezaran a notarse indicios de una recesión inminente. 

Los mercados financieros son el espacio en donde se encuentran la oferta y la demanda de activos financieros, como bonos y acciones. De esta forma, a través del mercado, los gobiernos y las empresas pueden obtener financiamiento mientras que las personas pueden invertir sus ahorros y obtener ganancias.

En líneas generales, en el corto/mediano plazo se observan muchas variaciones en los precios de los activos, pero a largo plazo se suelen observar tendencias alcistas (también llamadas bullish) o tendencias bajistas (bearish). Una herramienta utilizada para el correcto análisis y visualización de los precios, minimizando el “ruido” generado por la volatilidad inherente, son las medias móviles, que muestran el valor medio del precio de un mercado/activo durante un determinado período de tiempo y en función del cambio del precio, su valor medio va aumentando o disminuyendo.

Si por ejemplo tomamos una media móvil de periodo 200 (es decir, 200 sesiones) tenemos la media aritmética del precio durante las anteriores 200 sesiones y lo que se hace es que se suman los 200 precios de cierre y posteriormente los dividimos entre 200.

 
### Rol a desarrollar

Simularemos una situación en donde una empresa que busca invertir en el mercado bursátil le solicita analizarlo en detalle. Considerando que la empresa no conoce esta área financiera, le solicita una explicación de qué ha sucedido en este mercado en los últimos años (considerando impactos positivos y negativos a partir del año 2000), recomendaciones de inversión (ya sea enfocada en empresas o rubros de éstas) y otra información complementaria que, usted como experto en datos, está en capacidad de brindar. 

El foco del análisis es variado y amplio, siendo posible incorporar focos como la variación de precios en el tiempo, la comparación entre distintas acciones, cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otras), recomendaciones basadas en el retorno y riesgo de inversión e incluso la creación de KPIs útiles para la toma de decisiones de inversión. La empresa deja a su disposición el o los focos que desee analizar, el resto de las exigencias se indicarán más adelante.

Considerando la cantidad de empresas existentes en el mercado bursátil, se le pide limitar el análisis a las empresas pertenecientes al índice SP500 ([Standard & Poor's 500 Index](https://www.google.com/url?q=https://en.wikipedia.org/wiki/List_of_S%2526P_500_companies&sa=D&source=docs&ust=1676566032938438&usg=AOvVaw3J6gZYtEH8xJABTCf0pYqO)).

Considerando lo anterior, el principal objetivo es poder conocer la situación del mercado bursátil en los últimos 23 años según los focos mencionados anteriormente, permitiendo que usted, como Analista de Datos, sea capaz de dar un contexto de la situación y generar recomendaciones de inversión, como mínimo se espera que pueda recomendar en qué compañías invertir y qué día de la semana es recomendable hacerlo.


## **Propuesta de trabajo (requerimientos de aprobación)**

`Análisis Exploratorio de los datos`(_Exploratory Data Analysis = EDA_):

El reporte debe incluir un resumen de estadísticas descriptivas de los datasets, análisis univariados (por ejemplo, distribución de variables numéricas), análisis bivariados (correlación entre variables numéricas y/o categóricas); y **cualquier análisis que le ayude al mejor entendimiento de los datos** (encontrar patrones, outliers y/o anomalías, entre otros). El reporte debe presentarse en un notebook (_.ipynb_) con adecuado uso de markdowns y comentarios.
  
`Dashboard`:

Debe ser funcional y coherente con el análisis y la historia que vayan a relatar. **El archivo debe estar en su repositorio** (.pbix, .py o el que aplique).

`KPIs`:

Se deben sugerir 3 KPIs y deben aparecer en el dashboard. Tenga en cuenta que debe tener relación la historia que está contando, y debe explicar en la presentación el análisis y la funcionalidad de los KPIs sugeridos.

:warning:`Análisis`: :warning:

No se calificará solamente la producción de gráficos con datos (dashboard), sino también los **análisis y conclusiones** que encuentren de estos.
  
`Repositorio de GitHub`:

El repositorio debe contener un Readme principal donde se presente de forma general **su proyecto**. Presentar como propio el Readme proporcionado por Henry será considerado como **insuficiente** para cumplir con este requerimiento.
  
**PLUS**
<br>
<sub> Nota: la realización de los siguientes ítems no es intercambiable con los requerimientos mínimos establecidos en la sección anterior "Propuesta de trabajo". Empiece con esta sección una vez haya cumplido con los requerimientos mínimos, a modo de desafiarse a usted mismo.</sub>

- Redactar un reporte escrito de análisis realizado en base a sus dashboard e incluirlo en el readme de sus repositorios. También debe incluir el análisis y la funcionalidad de los KPIs sugeridos.
- Cruce de datos con datasets complementarios.
- Incorporar al análisis al menos una década de datos extra (datos previos al año 2000). 

  
## Fuente de datos:
**Obligatorios:**

- Para este trabajo se utilizará la API de yahoo finance, la cual posee su librería https://pypi.org/project/yfinance/ y pagina oficial https://finance.yahoo.com/

- [Lista índice SP500](https://www.google.com/url?q=https://en.wikipedia.org/wiki/List_of_S%2526P_500_companies&sa=D&source=docs&ust=1676566032938438&usg=AOvVaw3J6gZYtEH8xJABTCf0pYqO)

**Complementarios:**
- Cualquier dataset de búsqueda propia que complemente y mejore el análisis.


<h1>Lo que tendremos en cuenta a la hora de evaluar:</h1>

Serás evaluado en dos grandes áreas, ambas con igual peso entre si: `Tech` y `Soft`!

**Las habilidades técnicas (Tech)** para este proyecto de analytics incluyen el tipo de herramientas utilizadas para la realización de dashboard (herramientas de **Business Intelligence** y/o DataViz), elección de **gráficas pertinentes** para la representación del dato y un dashboard **efectivo** (organización, uso de filtros y criterios estéticos y de diagramación dónde se ubican los filtros y visualizaciones, títulos adecuados, estandarizacion de idiomas, entre otros)

**Las habilidades blandas (Soft)** para este proyecto tendrán en cuenta la **puntualidad y preparación para la demo**, su **comunicación oral y storytelling**, la forma en que cuentas tu historia (los datos duros que presentas son **útiles** para tu audiencia?) y finalmente (esto es mucho muy importante), :warning:**EL ANÁLISIS**:warning: (¿brindas un contexto?, ¿haces comparaciones con otros datos?, tienes conclusiones interesantes y realizas análisis no triviales?).

<sub>**Spoiler**: Te vamos a dar feedback y también vamos a evaluar tu capacidad de recepción a este :stuck_out_tongue: </sub>


## Material de apoyo
- Todos los Workshops de esta etapa serán de gran utilidad para tener un proyecto exitoso!
- [Como hacer un EDA](https://medium.com/nerd-for-tech/how-to-do-some-basic-eda-a-guide-for-dummies-d76d9a82242c)
- [Define your KPIs](https://medium.com/swlh/define-your-kpis-1a2072f1435)
- [Web Scrapping](https://www.softwaretestingmaterial.com/why-we-need-web-scraping/)

- [COVID-19 Economy’s Effects on Food, Housing, and Employment Hardships](https://www.cbpp.org/research/poverty-and-inequality/tracking-the-covid-19-economys-effects-on-food-housing-and)
- [The COVID-19 effect on global economic sentiment](https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/the-coronavirus-effect-on-global-economic-sentiment)
- [FED: Suba histórica de tasas](https://cnnespanol.cnn.com/2022/07/27/fed-tasas-interes-reserva-federal-aumento-trax/)
- [Monedas latinoamericanas y fortalecimiento del dólar](https://cnnespanol.cnn.com/2022/10/07/monedas-latinoamerica-mundo-afectadas-dolar-fuerte-orix/)



## ***Recomendaciones finales***

¡No deben mostrar nada de código en la exposición!

Recordamos que sean puntuales y prueben el correcto funcionamiento de las herramientas empleadas antes de ingresar a la meet.

La **DEMO**, donde defenderán el proyecto, se realizará el día jueves o viernes. Deben estar atentos a su *calendar* para ver qué día y horario les corresponde. 

Tendrá una duración total máxima de 30 minutos, de los cuales sólo 10 minutos serán para su presentación.  Es importante que sepan **gestionar bien su tiempo** y tengan un speech ya preparado de 10 minutos, ya que el tiempo restante será dedicado a la corrección y feedback por parte del Henry Mentor.


## Disclaimer
De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulan un entorno laboral, en el cual se trabajan diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).
  
<p align='center'>
<img src ="https://media.giphy.com/media/BpGWitbFZflfSUYuZ9/giphy.gif" height=250>
<p>
