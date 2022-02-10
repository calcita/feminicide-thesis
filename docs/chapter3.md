# Estrategia metodológica 




Para el propósito de esta investigación se ha seleccionado una estrategia mixta de
investigación. Por un lado, se emplean técnicas cuantitativas para el procesamiento y análisis de datos. Más concretamente, se realiza un cruzamiento y análisis de microdatos publicados por diferentes instituciones del Estado, así como por organizaciones de la sociedad civil con amplia trayectoria en el seguimiento, denuncia y combate a la VBG. Por otro lado, para analizar la política pública vigente en materia de VBG se realiza un análisis de documentos institucionales y la normativa nacional al respecto y, de forma complementaria, se realizan entrevistas semi-estructuradas a informantes clave que trabajan en el Sistema de Respuesta Integral (SRI) del MI e Inmujeres, con el objetivo de recabar información adicional no disponible en la documentación institucional analizada. Estas personas seleccionadas trabajan en la implementación de las políticas públicas.

La estrategia cuantitativa, consiste en primer lugar en analizar si los feminicidios ocurren aleatoriamente en el espacio o, por el contrario, se producen en determinadas zonas. En caso de encontrarse algún patrón espacial, se analizan las características de esas zonas. Posteriormente, a través de técnicas estadísticas se busca detectar una relación entre la tasa de feminicidios y el nivel socioeconómico promedio de las personas que habitan la zona en que ocurren los feminicidios. El nivel socioeconómico se usa como *proxy*^[En estadística, un proxy es una variable que no tiene tanto interés en si misma sino porque se relaciona con otras variables inobservables o que no se pueden medir.] de variables no observables que tienen que ver con la autonomía económica de las mujeres o la posesión de recursos materiales que facilitarían la salida de una situación de VBG. Otras características inmateriales como el capital cultural y social que podrían ayudar a las mujeres a superar estas situaciones no es posible operacionalizarlas con las fuentes de datos disponibles, por lo tanto, quedan por fuera del análisis.

En esta investigación, el nivel socioeconómico se operacionaliza, para Montevideo, a
través del indicador de incidencia de la pobreza en personas estimado a partir de la Encuesta Continua de Hogares (ECH) realizada anualmente por el INE. La evidencia muestra que conforme más pobre es un hogar, hay una mayor proporción de mujeres que no perciben ingresos propios y paralelamente, asumen una mayor carga de trabajo no remunerado al interior del hogar, esto como se mencionó anteriormente, vulnera su autonomía económica (INE, 2013). Por otro lado, para los departamentos del interior del país, no se considera el indicador de incidencia de la pobreza, sino que se utiliza el indicador de Necesidades Básicas Insatisfechas (NBI)^[La pobreza por ingresos es una medida coyuntural dado que los ingresos pueden sufrir una gran volatilidad en un corto tiempo, mientras que las NBI son una medida estructural de pobreza con poca variación en el corto plazo.]. Esta distinción se realiza por criterios estadísticos, dado que para Montevideo, la ECH permite calcular con una precisión aceptable la pobreza monetaria a diferentes niveles de desagregación territorial (municipio, CCZ, barrio) cuando se agregan encuestas, mientras que, para los restantes departamentos del país, se pierde precisión a la hora de estimar en unidades más pequeñas que la departamental. Por este motivo, para los 18 departamentos del interior se utiliza el Censo de Viviendas y Personas del año 2011. Dado que éste no releva ingresos, el indicador elegido para operacionalizar el nivel socioeconómico de las personas es la incidencia de las NBI en personas.

## Fuente de datos

Para estudiar un fenómeno de manera cuantitativa es necesario contar con datos confiables y comparables a lo largo del tiempo, así como datos secundarios que puedan aportar a la investigación (encuestas, censos, etc.). Las estadísticas oficiales de femicidios^[El Ministerio del Interior utiliza el término femicidio en lugar de feminicidio.] elaboradas para el total país, por el Observatorio Nacional sobre Violencia y Criminalidad del MI datan de 2013, año en que se puso en funcionamiento el Sistema de Gestión de Seguridad Pública (SGSP). Por otro lado, existe un registro no oficial de feminicidios a través del portal Feminicidios Uruguay^[El registro que llevan adelante activistas feministas está disponible en la página web Feminicidio Uruguay. Actualmente este proyecto está a cargo de la activista y comunicadora social Helena Suárez Val, con la colaboración de Yoselin Machin Castro. Esta iniciativa surgió a fines de 2014 en el marco de las movilizaciones contra los feminicidios organizados por la Coordinadora de Feminismos y del Primer Encuentro de Feminismos del Uruguay. Los datos del período marzo 2001 y junio 2014 fueron relevados por la ONG Caminos-Centro Interdisciplinario, y a partir de esa fecha, los casos fueron recopilados retrospectivamente a partir de la cobertura en los medios de comunicación.] (FU). Esta base recoge el registro que la ONG Caminos llevó desde marzo 2001 hasta 2014 y para los años posteriores las activistas de FU completaron la serie y agregaron las coordenadas del lugar del hecho. En esta investigación se optó por utilizar los datos de FU, ya que representan una serie de tiempo más larga e incorporan algunas variables más que los datos del MI, además, refieren a la definición feminicidio adoptada para realizar esta investigación. 


Dado los cometidos del presente trabajo, también se utilizan fuentes de datos secundarias
como las ECHs, el Censo de Población y la serie de Proyecciones de Población del INE; el
registro de Homicidios a Mujeres^[El MI denomina a estos datos como homicidios porque no todos estos casos están judicialmente caratulados como femicidios, aunque, en la práctica si los considera femicidios.] y las denuncias de VD del MI; y un conjunto de archivos con las geometrías que definen los límites de departamentos, segmentos censales, Centros
Comunales Zonales (CCZs) y barrios^[Los CCZs y barrios solo están definidos para Montevideo.]. En la Tabla 1 se listan las diferentes fuentes de datos utilizadas. Las fuentes secundarias son imprescindibles en esta investigación ya que, permiten estimar el nivel socioeconómico a diferentes nivel de desagregación espacial, calcular las tasas de feminicidio y realizar mapas a partir de estos indicadores.

<!-- tabla 1 -->
<table class="table" style="font-size: 12px; margin-left: auto; margin-right: auto;border-bottom: 0;">
<caption style="font-size: initial !important;">(\#tab:unnamed-chunk-2)Fuente de datos</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Datos </th>
   <th style="text-align:left;"> Fuente </th>
   <th style="text-align:left;"> Período </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Registro no oficial de feminicidios </td>
   <td style="text-align:left;width: 7cm; "> Feminicidios Uruguay </td>
   <td style="text-align:left;"> 2001-2019 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Homicidios domésticos a mujeres </td>
   <td style="text-align:left;width: 7cm; "> Ministerio del Interior </td>
   <td style="text-align:left;"> 2013-2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Denuncias de Violencia Doméstica </td>
   <td style="text-align:left;width: 7cm; "> Ministerio del Interior </td>
   <td style="text-align:left;"> 2013-2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Encuesta Continua de Hogares </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;"> 2006-2019 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Censo Poblacional </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;"> 2011 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Proyecciones de Población </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;"> 2001-2019 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Geometrías departamentos </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Geometrías segmentos censales </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Geometrías CCZ (Montevideo) </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Geometrías barrios (Montevideo) </td>
   <td style="text-align:left;width: 7cm; "> Instituto Nacional de Estadística </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Fuente:</span> <sup></sup> elaboración propia</td></tr></tfoot>
</table>


Respecto a la fuente principal de datos, el registro de FU, cabe resaltar que presenta datos faltantes y heterogeneidad en la forma de ingreso de la información. En particular, los datos de las coordenadas del lugar del feminicidio solo están exactas para Montevideo a partir de 2010. Para el interior del país las coordenadas no tienen un alto grado de precisión, ya que solo indican la localidad en que ocurrió el crimen. Con el propósito de homogeneizar la base de datos y mejorar la información que contiene, se realizó un procesamiento que constó en: validar las coordenadas, excluyendo los casos que no corresponden al territorio uruguayo^[Existen algunos casos que se incluyeron en la base de FU por tratarse de víctimas uruguayas asesinadas en otro país. Estos casos se descartan porque exceden el propósito de esta investigación.], y de algunos casos no georreferenciados se obtuvieron las coordenadas a partir de la base de Homicidios a Mujeres del MI. A partir de las coordenadas, se recalculó el departamento y localidad, también se agregaron variables a un nivel de desagregación menor: segmento censal (para Montevideo y el interior), municipio, CCZ y barrio (sólo para Montevideo). Asimismo se calcularon otras variables como, por ejemplo, el tamaño de la localidad. 


Dado que una variable relevante en este análisis es el espacio donde ocurrió el crimen y
no se releva directamente en los registros de FU, parte del proceso de limpieza y procesamiento de los datos implicó la revisión de noticias sobre los feminicidios y la variable que describe el hecho, de manera de completar la información faltante mediante un análisis de texto. Esta heterogeneidad que presenta la base de datos de FU se debe en parte a que los datos se obtienen en mayor medida por información de prensa y ésta no siempre reporta las mismas variables. Por lo tanto, no es estándar la descripción de los feminicidios sino que responde a la información que se tenga del caso, por ejemplo, a veces, se menciona la existencia de hijas/os pero en la mayoría de los casos no se dice nada al respecto. Como resultado de este procesamiento, para el período 2001-2019 se obtuvo una base de datos con un alto grado de completitud en las variables a utilizar (Ver Tabla 2). En el caso de Montevideo, para el período 2010-2019 se logró tener el 99% de los datos con las coordenadas exactas del lugar del feminicidio. 


<!-- tabla 2 -->
<table class="table" style="font-size: 12px; margin-left: auto; margin-right: auto;border-bottom: 0;">
<caption style="font-size: initial !important;">(\#tab:unnamed-chunk-3)Variables y completitud</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Variable </th>
   <th style="text-align:left;"> Descripción </th>
   <th style="text-align:left;"> Completitud </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> coordenadas </td>
   <td style="text-align:left;width: 7cm; "> Latitud, Longitud </td>
   <td style="text-align:left;"> 22% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> fecha </td>
   <td style="text-align:left;width: 7cm; "> fecha del crimen (yy-mm-dd) </td>
   <td style="text-align:left;"> 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> lugar </td>
   <td style="text-align:left;width: 7cm; "> Lugar del crimen (vivienda, espacio público, etc.) </td>
   <td style="text-align:left;"> 88% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> edad </td>
   <td style="text-align:left;width: 7cm; "> Edad de la mujer asesinada </td>
   <td style="text-align:left;"> 97% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> edad_feminicida </td>
   <td style="text-align:left;width: 7cm; "> Edad del feminicida </td>
   <td style="text-align:left;"> 52% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> vinculo </td>
   <td style="text-align:left;width: 7cm; "> Tipo de vínculo entre la víctima y el feminicida </td>
   <td style="text-align:left;"> 87% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> localidad </td>
   <td style="text-align:left;width: 7cm; "> Localidad donde ocurrió el feminicidio </td>
   <td style="text-align:left;"> 100% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> departamento </td>
   <td style="text-align:left;width: 7cm; "> Departamento donde ocurrió el feminicidio </td>
   <td style="text-align:left;"> 100% </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Fuente:</span> <sup></sup> elaboración propia</td></tr></tfoot>
</table>

Los datos se procesan utilizando el software libre y gratuito R Core Team (2020),
disponible en https://www.R-project.org/. Para obtener las capas geográficas, se utiliza el paquete “geouy” (Detomasi, 2020), para procesar las ECH se utiliza el paquete “ech” (Mathieu y Detomasi, 2020) y para realizar el análisis estadístico el paquete “spdep” (Bivand, Pebesma y Gomez-Rubio, 2013).

## Definiciones

El universo de estudio es la totalidad de los feminicidios ocurridos en el territorio
uruguayo entre 2001 y 2019. La selección de ese período se debe a que corresponde a la serie de datos más extensa que se tiene para este fenómeno. No existe un registro para los feminicidios ocurridos con anterioridad a 2001 y dado que la investigación se desarrolló durante 2020 no se cuentan con los datos completos para dicho año. El análisis se realiza para los departamentos del interior con los datos de todo el período, ya que la precisión en la georreferenciación es común para todos los años y es a nivel de la localidad. Sin embargo, para Montevideo, a partir de 2010 los casos se encuentran georreferenciados con una precisión exacta sobre el lugar de ocurrencia, y para los años anteriores los casos no están georreferenciados^[Los datos de Feminicidios Uruguay se nutren de los datos de ONG Caminos para el período 2002-2014 y éstos no fueron sistematizados con el objetivo de recabar las coordenadas del lugar del crimen. El trabajo de sistematizar el lugar del crimen a partir de las coordenadas lo realizó Feminicidios Uruguay ex-post de contar con la base de datos de ONG Caminos, por lo tanto, los casos más viejos no cuenta con el dato geográfico.]. Por lo tanto, para este departamento, el análisis espacial comprende sólo aquellos feminicidios ocurridos entre 2010 y 2019.

Se tienen en cuenta dos grandes categorías de feminicidios, aquellos que ocurrieron en la
vivienda de la mujer asesinada, y, por otro lado, los restantes feminicidios. Esta distinción es relevante, dado que si el feminicidio ocurrió en la vivienda de la víctima podremos de alguna manera asociar las características promedio de las personas de ese microterritorio a las de la mujer asesinada. Esto tiene sentido, al menos en Montevideo, ya que conforme el nivel de desagregación territorial es mayor, los territorios se vuelven más pequeños y homogéneos en su interior considerando el nivel socioeconómico, debido a una marcada segregación territorial que existe en términos de ingreso (Rodríguez, 2019).

### Unidad de análisis

En definitiva, esta investigación considera como unidad de análisis los feminicidios
ocurridos en Uruguay a partir de 2001 y hasta 2019, con énfasis en el análisis de los feminicidios georreferenciados en Montevideo en el período 2010-2019.

### Unidades espaciales

Tanto la ECH como el Censo consideran diferentes unidades territoriales sobre las cuales
reportan las variables relevadas. La unidad más abarcativa en extensión de territorio, es el “departamento censal” que se divide en “secciones censales”. Dentro de las “secciones censales”, los territorios menores se denominan “segmentos censales” (en áreas urbanas representa un conjunto de manzanas). La unidad más pequeña identificable es la “zona censal” (en áreas urbanas representa una manzana). Sin embargo, tanto la ECH como el Censo se divulgan con georreferencia mínima de “segmentos censales”, de manera de proteger el secreto estadístico y la confidencialidad de las personas encuestadas tal como lo dispone la Ley 16.616 que crea el Sistema Estadístico Nacional. Para Montevideo también se dispone de información del barrio y el CCZ, además, es posible identificar el municipio. Cada una de estas unidades espaciales representan un área o polígono, mientras que los lugares donde ocurrieron los feminicidios representan un punto en el espacio. Estas diferentes unidades espaciales mencionadas serán utilizadas en el análisis descriptivo y estadístico.

## Métodos e indicadores

A partir de los registros de FU, y las proyecciones de población del INE para los
diferentes años analizados se calcula la tasa de feminicidios anual para el total país y otras áreas de interés, así como también la tasa de feminicidios para todo el período.

Se utiliza la tasa de feminicidios como indicador para comparar entre diferentes regiones,
departamentos e incluso entre años. Si bien los valores absolutos dan cuenta de la magnitud del fenómeno, para comparar entre países o entre departamentos debido a las diferencias de tamaño de población, estas cifras pueden resultar engañosas y es necesario estandarizar estos valores.

La tasa anual de feminicidio (por cada 100.000 mujeres) se define como el cociente entre
el número de feminicidios durante cierto año, $F_i$, y la población de mujeres, $M_i$, multiplicado por 100.000. Tanto la cantidad de feminicidios como de mujeres deben estar referidos a un territorio delimitado, por ejemplo, departamento, localidad, etc.

<!-- formula 1  -->
$$TF_i = \frac{F_i}{\hat{M}_i}* 100.000$$

De acuerdo a la ecuación anterior, la tasa de feminicidios del año $i$, denominada $TF_i$, se calcula como el cociente entre la cantidad de feminicidios ocurridos en el año $i$, denotados como $F_i$, y la población de mujeres estimada al 30 de junio de dicho año, $\hat{M_i}$^[Las proyecciones de población del INE se realizan para junio de cada año a partir de la información del último censo disponible.], por cada 100.000 mujeres.

Para obtener una medida de todo el período se considera la tasa agregada de feminicidios
como la razón entre la cantidad de feminicidios ocurridos en un período de tiempo, y, el producto entre la cantidad de años del período y la población promedio de mujeres de ese territorio, multiplicado por 100.000. Por ejemplo, para calcular la tasa de feminicidios para el período 2010-2019 se realiza el cociente entre la cantidad de feminicidios del período, dividido por 10 (que es la cantidad de años entre 2010 y 2019) y la población promedio de mujeres en ese período. Este valor se multiplica por 100.000. La fórmula es:

<!-- formula 2 -->
$$TF_{2010-2019} = \frac{\sum_{2010}^{2019}{F_i}}{\hat{M_{2010-2019}}}* 100.000/10$$

A partir de los datos de las fuentes secundarias, se presenta la información según un nivel de desagregación espacial intermedio, con el fin de cuantificar el indicador de nivel socioeconómico en unidades territoriales pequeñas manteniendo niveles de precisión aceptable.


La estimación de la incidencia de la pobreza a nivel de personas en Montevideo se realiza
a partir de las ECHs desde 2010 hasta 2019 para distintas unidades espaciales (municipios, CCZs y barrios). Se estima el indicador de incidencia de la pobreza en personas como el cociente entre la suma de personas en situación de pobreza para un área de interés sobre la totalidad de las personas que residen en dicha área en un año determinado.

<!-- formula 3 -->
$$\hat{IPP} = \sum_{j=1}^{n}(pobres_j)/total$$

Para estimar la incidencia de las NBI en personas para cada localidad del interior del país, se utilizan los datos del Censo Poblacional de 2011. Se calculan una serie de indicadores que agregados resumen la cantidad de NBI que tiene un hogar y por ende, todas las personas que lo integran. En la Tabla 3 se listan los indicadores considerados y el umbral que determina la carencia. Como resultado se obtiene la proporción de personas en dicha localidad con 0, 1, 2 y hasta 6 NBI.

<!-- tabla 3 -->
<table class="table" style="font-size: 12px; margin-left: auto; margin-right: auto;border-bottom: 0;">
<caption style="font-size: initial !important;">(\#tab:unnamed-chunk-4)NBI: dimensiones, indicadores y umbrales</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Dimensión </th>
   <th style="text-align:left;"> Indicador </th>
   <th style="text-align:left;"> Umbral </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 3cm; "> Vivienda decorosa </td>
   <td style="text-align:left;width: 3cm; "> Materialidad </td>
   <td style="text-align:left;width: 3cm; "> El hogar habita una vivienda con techos o paredes construidas predominantemente con materiales de desecho, o piso de tierra sin piso ni contrapiso. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; ">  </td>
   <td style="text-align:left;width: 3cm; "> Espacio habitable </td>
   <td style="text-align:left;width: 3cm; "> Más de dos miembros del hogar por habitación en la vivienda (excluyendo baño y cocina) </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; ">  </td>
   <td style="text-align:left;width: 3cm; "> Espacio apropiado para cocinar </td>
   <td style="text-align:left;width: 3cm; "> El hogar habita una vivienda que no cuenta con un espacio para cocinar con canilla y pileta </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; "> Abastecimiento de agua potable </td>
   <td style="text-align:left;width: 3cm; "> Origen y llegada del agua a la vivienda </td>
   <td style="text-align:left;width: 3cm; "> El agua no llega por cañería dentro de la vivienda que habita el hogar, o su origen no es red general o pozo surgente protegido. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; "> Servicio higiénico </td>
   <td style="text-align:left;width: 3cm; "> Acceso y calidad del servicio higiénico </td>
   <td style="text-align:left;width: 3cm; "> El hogar no accede a baño de uso exclusivo o la evacuación del servicio sanitario no es a través de la red general, fosa séptica o pozo negro. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; "> Energía eléctrica </td>
   <td style="text-align:left;width: 3cm; "> Acceso a energía eléctrica </td>
   <td style="text-align:left;width: 3cm; "> El hogar no cuenta con energía eléctrica en la vivienda que habita. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; "> Artefactos básicos de confort </td>
   <td style="text-align:left;width: 3cm; "> Calefacción </td>
   <td style="text-align:left;width: 3cm; "> El hogar no cuenta con ningún medio para calefaccionar la vivienda que habita. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; ">  </td>
   <td style="text-align:left;width: 3cm; "> Conservación de alimentos </td>
   <td style="text-align:left;width: 3cm; "> El hogar no cuenta con heladera o freezer. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; ">  </td>
   <td style="text-align:left;width: 3cm; "> Calentador de agua para el baño </td>
   <td style="text-align:left;width: 3cm; "> El hogar no posee calefón, termofón, caldereta o calentador instantáneo. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 3cm; "> Educación </td>
   <td style="text-align:left;width: 3cm; "> Asistencia a enseñanza formal de niños y adolescentes </td>
   <td style="text-align:left;width: 3cm; "> Al menos un integrante del hogar con edad comprendida entre los 4 y los 17 años no se encuentra asistiendo a un centro educativo formal, no habiendo finalizado enseñanza secundaria. </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Fuente:</span> <sup></sup> Tomado de Calvo et al. (2013)</td></tr></tfoot>
</table>


A partir de estos indicadores y los feminicidios georreferenciados se realiza un
análisis espacial exploratorio y se aplican técnicas para detectar autocorrelación espacial. De esta manera, se busca responder las preguntas de la investigación que refieren a cómo se distribuyen los feminicidios y si existen algunas zonas donde se presentan más casos. En particular, se utiliza el estadístico $I$ de Moran para detectar si hay una asociación espacial en los datos. El estadístico $I$ se usa para identificar *clusters* de áreas de interés con un riesgo similar de la ocurrencia de feminicidio. Un valor de $I$ cercano a $+1.0$ indica agrupaciones, es decir, unidades geográficas similares entre sí. Un valor cercano a $0$ indica no correlación, es decir, que el feminicidio se produce aleatoriamente a lo largo y ancho del territorio. Un valor cercano a $-1.0$ indica dispersión, esto es, que las unidades geográficas son diferentes entre sí (Anselin, 1995). Entonces, niveles positivos de la $I$ de Moran, sugieren una dependencia espacial positiva y estaría indicando que niveles similares de la tasa de feminicidios se encuentran agrupados. Dado que el estadístico $I$ no permite identificar los patrones locales de asociación espacial, es decir, si existen o no *clusters*^[En estadística el término cluster refiere a agrupamientos de los datos.] de feminicidios concentrados en lugares particulares del territorio analizado, se calculan los Indicadores Locales de Autocorrelación Espacial (LISA, por sus siglas en inglés) para cada región de análisis y se analizan sus resultados. De los LISA se podría obtener, por ejemplo, que un barrio con una alta tasa de feminicidios esté rodeado de barrios también con altas tasas de feminicidio, que daría cuenta de una autocorrelación espacial positiva. 


Posteriormente, con el objetivo de identificar la relación entre las características medibles de vulnerabilidad socioeconómica y la tasa de feminicidios se estiman los modelos por Mínimos Cuadrados Ordinarios (MCO) a diferentes niveles de agregación espacial. Como resultado se busca dar respuesta a la pregunta que orienta la investigación: ¿Existe relación entre las características socioeconómicas y la distribución espacial de los feminicidios en Montevideo en el período 2010-2019? Posteriormente, se describen los resultados de cada uno de los modelos y se analiza si existe algún problema de especificación^[La especificación de un modelo implica seleccionar una forma funcional para el modelo y la elección de las variables a incluir. Cometer errores en este proceso implicaría, por ejemplo, seleccionar una forma funcional incorrecta, omitir variables relevantes o incluir variables irrelevantes. Como resultado el modelo estimado será sesgado e inconsistente y, por lo tanto, no se debería usar.] al no considerar la presencia de correlación espacial. Dado que la variable dependiente es una tasa, esto podría violar uno de los supuestos del modelo MCO, por lo que se prueban modelos que consideran los datos normalizados a través de la implementación de logaritmos naturales. Se ponen a prueba tres modelos de regresión^[Es un modelo matemático que busca determinar la relación entre una variable dependiente, en este caso la TF, con respecto a otras variables, llamadas explicativas o independientes, en este caso la IPP. Asimismo, el modelo busca determinar cuál será el impacto sobre la variable TF ante un cambio en la(s) variable(s) explicativa(s).], el más básico un modelo lineal y otros dos con la variable dependiente en logaritmos:

<!-- formulas modelos -->
1- Modelo log-lineal: $$log(TF_j) =  \alpha + \beta*IPP_j + \epsilon_j$$

2- Modelo lineal: $$TF_j =  \alpha + \beta*IPP_j + \epsilon_j$$

3- Modelo log-log: $$log(TF_j) =  \alpha + \beta*log(IPP)_j + \epsilon_j$$


Donde $log(TF)$ es el logaritmo de la tasa de feminicidios del período, $\alpha$ es la constante del modelo, $\beta$ el parámetro asociado a la variable independiente $IPP$ o su logaritmo, que es la incidencia de la pobreza en personas, $\epsilon$ es el error aleatorio y, por último, $j$ indica cada una de las áreas de interés consideradas.

Para la estimación de cada modelo se utiliza el método habitual de MCO y se analiza la
bondad del ajuste a partir del $R^2$ y el $R^2$ ajustado. Además se comprueba la significatividad del modelo^[La significatividad de un modelo implica que las variables independientes pueden explicar el comportamiento de la variable dependiente.] a partir del $p−valor$ asociado al estadístico $F$, considerando como hipótesis nula que los coeficientes de las variables explicativas son cero, es decir, que las variables consideradas no son relevantes para estimar a la variable dependiente. Por lo tanto, se busca rechazar esta prueba de manera de obtener un modelo significativo. La regresión por MCO estima parámetros globales y asume una relación constante entre las variables en toda la región en que se distribuyen los datos. Por este motivo, es que se prueban los supuestos del modelo y en particular, los que dan cuenta de una posible autocorrelación espacial de los residuos.

Los métodos de estadística espacial propuestos permiten visualizar el fenómeno en forma
de mapas para detectar zonas calientes, donde se puede observar una concentración de puntos, así como también, asociar el feminicidio con otras variables que se distribuyen en el espacio como puede ser el nivel socioeconómico de las personas. Agregar la dimensión espacial al estudio de los feminicidios, sumando información de la ECH y el Censo es un insumo adicional a la política pública en pro de su mayor eficiencia para combatir la VBG y su expresión letal: el feminicidio. Esto es, la identificación de *clusters* espaciales donde el fenómeno se da en mayor medida permite concentrar esfuerzos en esas unidades territoriales donde el feminicidio ocurre con mayor intensidad. Por otro lado, permitiría la constatación de que el feminicidio afecta en mayor medida a mujeres con determinado nivel socioeconómico, podría brindar insumos para diseñar medidas estatales más adecuadas para abordar los problemas de las mujeres en situación de riesgo a raíz de la VBG que vivencian.

## Limitaciones de las fuentes de datos

Contar con información completa, de calidad y oportuna es clave en la política pública,
tanto para la prevención como para la atención y la respuesta. También permite comprender
cómo la recolección de los datos y su uso contribuyen o limitan la comprensión del fenómeno de los feminicidios y con ello ayudan o no a su combate. Uruguay, a diferencia de la mayoría de los países de la región, por no decir todos, tiene algunas facilidades para contar con un registro exhaustivo de los casos de feminicidios y los intentos de feminicidios. La reducida población en relación con los demás países del continente, la proactividad de las organizaciones feministas que desarrollan su propio registro y que se movilizan cuando ocurre un feminicidio, sumado al trabajo del Observatorio de Criminalidad del MI, son ventajas con las que cuenta el país para medir la magnitud del fenómeno.

Sin embargo, existen una serie de problemas y limitaciones que presentan los registros
actuales. La principal fuente oficial de información acerca de los femicidios en Uruguay
proviene de los registros policiales. Estos registros no fueron diseñados con propósitos
estadísticos y solo están sistematizados desde 2013, a partir de la puesta en marcha del SGSP en todo el país. Una parte sustantiva de la información sobre los femicidios se encuentra en los partes policiales y esto no se traduce en variables que alimenten la base de datos y, por lo tanto, no se pueden utilizar para el análisis estadístico. Por otro lado, existen problemas en el registro de las variables que son de interés en los casos de femicidios o directamente no se registran, por ejemplo, identidad de género, condición socioeconómica, denuncias previas, medidas de protección, etc.). Esto dificulta la categorización de los casos, la comparabilidad en el tiempo para un mismo país y entre países. Como fue mencionado en los primeros capítulos, es necesario incorporar al análisis de los feminicidios la interseccionalidad y para esto es relevante contar con variables asociadas a las mujeres asesinadas que den cuenta de su identidad de género, ascendencia étnico-racial, nivel socioeconómico, entre otras. 

