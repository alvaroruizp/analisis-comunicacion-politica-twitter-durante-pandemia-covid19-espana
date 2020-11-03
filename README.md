# Análisis de la comunicación política en Twitter durante 2020
Análisis de la comunicación política en Twitter en España 2020

## Memoria
Este notebook pretende ser un análisis exploratorio de la comunicación política en Twitter de los cinco principales partidos a nivel nacional, analizando sus similitudes y diferencias entre grupos, el perfil comunicativo de cada uno de los grupos, y si ha habido diferencias o cambios conforme la pandemia del COVID-19 ha ido evolucionando. Para ello, se analizan más de 130.000 tweets comprendidos desde el 1 de enero de 2020 hasta el 21 de octubre del mismo año, que han sido recopilados mediante la API de Twitter y la librería Tweepy. También se ha recopilado información relativa al sexo y edad de cada diputado mediante un scraping con BeautifulSoup a la web del Congreso.
El análisis consta de 3 fases:
1.	Tratamiento de los datos: Cómo se han recogido, qué transformaciones han sufrido los datos para poder manipularlos, dataframes empleados, etc.
2.	Análisis cuantitativo de los datos: ¿Cómo twittean?: Perfilado por grupo político, análisis cuantitativo de actividad, tweets, número de retweets, followers, fecha de publicación, tendencias, etc.
3.	Análisis cualitativo: ¿Qué twittean? Análisis de las palabras empleadas.
Los tweets pertenecen a 273 diputados, entre los que se encuentran los líderes de cada uno de los partidos y están repartidos de la siguiente forma:
-	PSOE: 103 Diputados que suman un total de 44461 tweets
-	PP: 77 Diputados que suman 28097 tweets
-	Vox: 48 Diputados que suman 31640 tweets
-	Unidas Podemos: 35 Diputados que suman 18831 tweets
-	Ciudadanos: 10 Diputados que suman 7280 tweets

La idea surge por una motivación personal por la política actual junto con el ascenso de las redes sociales como canal de comunicación activo y bidireccional. Las redes sociales ayudan a ganar elecciones, la polarización vende, y el ‘zasca’ viraliza. **¿Cómo emplean nuestros políticos twitter? ¿Hay diferencias significativas entre grupos? Y dentro de los grupos, ¿hay diferencias respecto a variables sociodemográficas como el sexo y la edad? ¿Está influenciada la comunicación por su papel de turno en la política? ¿La crisis provocada por la COVID-19 ha influido en la comunicación de los grupos?**


Estas son algunas preguntas que se pretenden contestar dentro del estudio, aunque con limitaciones. Principalmente, hay una limitación de tiempo que no ha permitido ahondar más en los datos, quedando muchos de ellos aún vírgenes para explorar en un futuro. En segundo lugar, la capacidad técnica del equipo, que no permite efectuar análisis de variables complejas (como el texto) en un periodo corto de tiempo. Por esta razón, este estudio pretende ser un primer punto de partida hacia una investigación más en profundidad donde puedan emplearse técnicas de machine learning y Deep learning para conocer más en profundidad el qué y el cómo de la comunicación política.


A la hora de obtener datos, han sido necesarias varias herramientas de scraping que se detallan dentro del documento. Todos los datos han sido recopilados, salvo los datos relativos al número de contagios y fallecimientos provocados por la COVID-19 que han sido descargados directamente desde la página del Ministerio de Sanidad y Our World in Data.
Los datos han sido procesados en varios Notebook y puestos en común dentro del principal, que se adjuntan con la memoria. Sin embargo, se han empleado documentos a modo de borrador que no serán incluidos.

Las conclusiones sacadas del análisis sugieren la idea de grupos políticos más veteranos, en los que las redes sociales aún no son un arma política de comunicación como puedan ser otros, y los grupos políticos jóvenes, con una fuerte presencia, tanto de seguidores como de diputados en activo.

Vemos en las gráficas que los dos partidos que más hacen uso de la plataforma son Vox y Unidas Podemos, en muchos casos con patrones de uso parecidos y una correlación entre sus variables que apuntan en el mismo sentido. Aunque con diferencias entre ellos, ambos partidos conocen bien Twitter y se mueven bien dentro de ese ambiente, cuentan con una legión de seguidores que viralizan su contenido, prácticamente sea cual sea, y que exponen el altavoz de su ideario político a un nivel mucho mayor que el Partido Socialista o el Partido Popular. Ciudadanos, por su contra, sigue una tendencia similar a Vox y Unidas Podemos, pero la escasez de diputados (solamente 10) provoca que su rendimiento dentro de Twitter no sea similar al del partido morado.

Como conclusiones destacables, no vemos un cambio significativo en la comunicación de los grupos que han tenido un papel clave en la pandemia cuando su papel ha pasado de activo a pasivo con el final del Estado de Alarma (PSOE, UP, PP), sin embargo, si vemos unos patrones comunes en el uso de Twitter conforme la pandemia avanzaba. Posiblemente, ser partidos de gobierno con responsabilidades políticas condiciona la comunicación, y por ello las diferencias tan grandes a partidos como Vox.
La segunda conclusión, comentada anteriormente, es la gran diferencia entre partidos convencionales y nuevos partidos, o partidos de la neopolítica, donde queda patente una forma de comunicación radicalmente diferente entre ambos grupos.

Se seguirán agregando conclusiones, resultados e hipótesis conforme vaya avanzándose el desarrollo de la investigación y sus análisis.
