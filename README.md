# EB-2022-1-CC50
# Objetivo del proyecto
+ Realizar un análisis exploratorio de los datos referente al dataset consignado al equipo de trabajo.
   + Como parte del punto anterior se busca:
      + Cargar el conjunto de datos,
      + Inspeccionar el conjunto de datos para la identificación de datos faltantes, datos atípicos, datos no relacionados (decidir las técnicas de preprocesamiento),
      + De la inspección pre-procesar y limpiar el conjunto de datos,
      + Visualización del nuevo y limpio conjunto de datos.
+ Al culminar el proyecto, el equipo brindará información útil en base a una serie de preguntas, en conjunto con sus respectivas visualizaciones para su fácil comprensión.
+ Al concluir el proyecto de datos, el equipo habrá desarrollado un modelo básico predictivo para concretar el desarrollo de un proyecto de analítica, buscando predecir el grado de satisfacción de la empresa en torno a un video que puedan publicar.


# Integrantes: 
+ Ian Steve González Vidalón - 202021767 (z3r0st)
+ Rebeca Liliana Bravo Navarro - 201711448 (relibrana)
+ Roberto Carlos Basauri Quispe - 20181C074

# Descripción del conjunto de datos
El conjunto de datos utilizado para el estudio contiene información relevante sobre los videos de Youtube que estuvieron en tendencias entre el 14 de noviembre de 2017 y el 14 de junio de 2018 en Canadá. El dataset almacena toda la información en el formato csv. Al leerlo como un DataFrame de la librería Pandas, se obtiene un total de 20 columnas y 40881 observaciones totales. Cada observación comprende la información referente a cada video que llegó a
tendencias.

Entre las principales piezas de información por video, se encuentra el título, la fecha en la que ingresó a tendencias, la cantidad de vistas, “me gusta”, “no me gusta”y la cantidad de comentarios. Estos últimos tres valores son especialmente importantes, ya que el algoritmo de Youtube que determina qué videos ingresan a tendencias toma como entrada la cantidad de interacciones, es decir, las vistas, “me gusta”, comentarios y veces que fue compartido.
Por otra parte, se presentan atributos binarios que permiten obtener información relevante sobre el estado del video, por ejemplo si este fue removido o si los comentarios fueron desactivados. También se encuentra información geográfica, como las coordenadas y estado (de Canadá) del cliente desde el cual se subió el video.

# Conclusiones
+ De este proyecto, el preprocesamiento del conjunto de datos fue clave para darle inicio al desarrollo de todos los puntos solicitados, de este paso dependía que los valores no sean ilógicos de procesar y sobre todo que se pueda extraer algún tipo de conocimiento válido de este.
+ Del conjunto de datos preprocesado, solo se requirió filtrar lo que la pregunta demandaba. Para tener un dataset uniforme para el equipo de trabajo.
+ En cuanto a la información recopilada por pregunta podemos concluir lo siguiente:
   + Que un video sea concurrente de estar en tendencia, no quiere decir que sea el que mayor reacciones pueda tener, como se puede apreciar con el caso de ‘entertainment’ y ‘music’, que el primero es el que lidera por diferencia las cantidades de videos que posee que están en tendencia, mientras que el segundo, lidera como categoría que más reacciones positivas tiene en promedio por video. Y esto es lógico, un video que entretiene se reproducirá más veces sin necesidad de tener que estar logueado, dándole muchas vistas, compartidas y aumentando su tasa de popularidad del canal que crea contenido de ese estilo, mientras que un video musical o música, uno reacciona porque le gusta o porque lo quiere guardar en una lista personalizada (acción que se puede realizar en Youtube).
   + Por otro lado, se puede concluir del análisis de ratios, que las películas son las que mejor visibilidad dan por la cantidad de comentarios, que se pueden traducir como críticas o ideas a nuevos aportes a la comunidad de películas, mientras que las categorías de música y comedia son las que mejor proporción tienes en cuanto a likes and dislikes, lo cual se puede constatar con el cálculo promedio de likes y dislikes del punto anterior. Esta última información se puede traducir que el público más disfruta un vídeo orientado a la comedia y a la música.


# Licencia de uso
MIT license
