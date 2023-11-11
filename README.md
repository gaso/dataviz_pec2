# Descifrando el Destino del Titanic: Un Viaje a Través de los Datos


## Introducción

Este análisis emprende un viaje retrospectivo para revelar las historias que yacen detrás de los números del Titanic. A través de visualizaciones elocuentes e ingeniosas, se investigan las distintas capas sociales presentes en la nave, así como también sus posibilidades para sobrevivir y su perfil demográfico.

## Click para abrir Notebook y explorar resultados en Google Colab
<a href="https://colab.research.google.com/drive/1mOcMIvL0xw8nGxAMN_SATcPHYepJACzK?usp=sharing" target="_blank"><img height="40" alt="Abrir en Colab" src = "https://colab.research.google.com/assets/colab-badge.svg"></a>

### Tecnica de Visualización: Pie Chart
El gráfico circular representa visualmente la distribución porcentual de los pasajeros del Titanic según su clase de viaje. Un vistazo rápido revela que la mayoría de los pasajeros, el 61,5%, viajaron en tercera clase, lo que indica que era la opción más asequible o popular entre los viajeros del Titanic. La primera y segunda clase tienen una representación igual del 19,2% cada una, lo que sugiere que menos pasajeros podrían permitirse o elegir estas opciones más caras. Este tipo de gráfico es útil para comprender la estructura de datos en términos de proporciones y facilita una comparación rápida entre categorías.

![](https://raw.githubusercontent.com/gaso/dataviz_pec2/main/images/Pie_Chart.gif)

#### Sunburst

Entre las variantes del grafico circular se encuentra la llamada Sunburst (Resplandor Solar) el cual permite visualizar la información en forma de anillo conservando cierta jerarquía entre los niveles. Tomando el ejemplo anterior sobre el mismo grafico que nos muestra la segregación de Clases podemos representar por cada una de ellas el desenlace de los pasajeros en función de la clase proporcionándonos más información y un entendimiento más holístico de las relaciones entre las distintas variables.

De este grafico surgen preguntas como ¿Teniendo en cuenta la proporción de los datos hubo mayor prioridad sobre la primera y segunda clase?

![](https://raw.githubusercontent.com/gaso/dataviz_pec2/main/images/Pie_Chart2.png)

### Tecnica de Visualización: Alluvial Diagram

El gráfico aluvial, es una representación visual de cómo las diferentes categorías de datos se conectan y fluyen entre sí, de forma muy similar a como el agua cambia de curso en un río aluvial. Al analizar los datos del Titanic utilizando este método de diagrama, se ilustran las conexiones entre la clase de pasajeros, el género y la tasa de supervivencia; brindándonos una visión integral de su interrelación. Podemos detectar patrones como si las mujeres de primera clase tenían mayores posibilidades de sobrevivir que las de tercera clase; resaltando así la dinámica social y las decisiones de rescate durante el trágico accidente.

En alguna película escuchamos la exclamación de ¡Mujeres y niños primero! ; pues en este grafico podemos observar de una manera muy clara como comparando en términos de proporciones las mujeres pudieron ser rescatadas en mayor numero que los hombres; tambien a través de los datos podemos desvirtúar que al menos en el caso de las mujeres la tercera clase tuvo un número importante de mujeres rescatadas.

![](https://raw.githubusercontent.com/gaso/dataviz_pec2/main/images/Alluvial_Chart.gif)

### Tecnica de Visualización: Rain Cloud Plots

El Rain Cloud Plot generado para el conjunto de datos del Titanic permite observar la distribución de edades de los pasajeros en relación con su supervivencia. Las áreas sombreadas indican densidad de pasajeros por grupo de edad, ampliándose en zonas de mayor concentración. Los puntos del gráfico representan edades individuales distribuidas para minimizar la superposición y mejorar la legibilidad. Los diagramas de caja superpuestos proporcionan un resumen estadístico que destaca las medianas, los cuartiles y los valores atípicos, al tiempo que facilitan la comparación entre los grupos de supervivencia.

![](https://raw.githubusercontent.com/gaso/dataviz_pec2/main/images/rain.gif)
