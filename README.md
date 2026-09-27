# proyecto_curso_2627

# Problema a resolver:
Mis amigos y yo actualmente usamos Excel para hacer una especie de liga entre todos, en la que tenemos que acertar los resultados de los partidos del mundial de futbol, 
ganando el que mas resultados haya acertado a lo largo del torneo. El problema es que manejar Excel para poner los resultados de cada partido es muy tedioso y largo, ademas de que solo 
la persona que ha creado el excel puede ver los resultados en tiempo real, mientras que el resto de participantes tienen que esperar a que se les pase una foto de la tabla para ver su posicion en ella, y el sistema de puntuacion por acertar resultados en el Excel es muy basico y rudimentario, sin margen de personalizar el sistema de puntuacion para cada torneo, por ejemplo, que da los mismos puntos por acertar un resultado obvio que uno improbable, o que no diferencia a quien acierta muchas veces seguidas de quien acierta de forma aislada.
![Tarjeta del rol de cliente](tarjeta_rol_cliente.jpg)
![Nota del rol de profesional](tarjeta_rol_profesional.jpg)

# Datos del problema

## Introduccion de datos

Los usuarios deberan introducir los resultados exactos, indicando:
-La cantidad de grupos maximo que van a haber en el torneo inicialmente
-La cantidad de equipos maximo que hay por grupo
-Intoducir en cada grupo los equipos correspondientes
-El resultado numerico de cada partido
-En caso de un empate, elegir un ganador obligatoriamente para que pase a la siguiente fase.

Los datos para comprobar los resultados y cruces reales estan disponible en la web de la FIFA: https://www.fifa.com/es/tournaments/mens/worldcup/canadamexicousa2026/standings

## procesamiento
Segun los resultados puestos pasaran unos equipos u otros a la siguiente fase. Los cruces en la siguiente fase dependen del grupo en el que se encuentra ese equipo, y de la posicion en la que ha quedado en dicho grupo. El Excel no calcula los cruces de la siguiente fase, por lo que se tienen que meter a mano los cruces en cada fase. Se quiere procesar autmaticamente los cruces segun se vayan rellenando los resultados de los partidos. Y se quiere procesar tambien las rachas de aciertos consecutivos poniendo un mutliplicador de puntos que vaya aumentando con la racha y que resultados que hayan puesto poca gente den mas puntos en funcion de la probabilidad en caso de acierto. Asi los resultados poco probables dan mas puntos 

## Despliegue en la nube
Para ver tu posicion en la tabla de clasificacion con respecto a tus amigos en tiempo real se necesita despliegue en la nube

# Referencias
Algunas app de referencias son las ligas fantasy de football.

# Lenguajes
Usare Python como lenguaje para realizar el proyecto

# Documentacion adicional
Captura de la configuracion de Git: [ver aqui](docs/config_git.png)
