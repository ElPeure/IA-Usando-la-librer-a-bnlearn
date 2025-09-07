Usando la librería bnlearn (https://pypi.org/project/bnlearn/), y un
dataset con al menos 10.000 filas. (Crowdedness at the Campus Gym)

Los profesores del curso tienen una carga de trabajo abrumadora, a lo que se suma
la gran cantidad de juegos pendientes en sus librerías. Suponga que uno de ellos
posee 30 juegos, denominados J1, J2,...,J30, y que va rotando el avance de un juego
día a día para no hacer monótono este proceso. Cada transición entre el juego Ji y el
juego Jk, ocurre con una cierta probabilidad 0<P(Jk|Ji)<0.1. En base a lo anterior, se
pide:

Generar un modelo automatizado que simule este escenario,
asignando las probabilidades de transición de acuerdo con las reglas
descritas.

Realizar un random-walk mostrando cómo van cambiando las
probabilidades de jugar los distintos juegos. El random-walk debe ser
ejecutado hasta llegar a una convergencia definida por usted, a través de un
parámetro de usuario epsilon. Analizar los resultados obtenidos.

Calcular la distribución estacionaria de la cadena de Markov
mediante un método analítico. Comparar y analizar estos resultados en
relación con lo obtenido en el punto anterior.
