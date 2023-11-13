# M1.Actividad
Actividad 1 de la materia de Modelación de sistemas multiagentes con gráficas computacionales

Dado:

Habitación de MxN espacios.
Número de agentes.
Porcentaje de celdas inicialmente sucias.
Tiempo máximo de ejecución.
Realiza la siguiente simulación:

Inicializa las celdas sucias (ubicaciones aleatorias).
Todos los agentes empiezan en la celda [1,1].
En cada paso de tiempo:
Si la celda está sucia, entonces aspira.
Si la celda está limpia, el agente elije una dirección aleatoria para moverse (unas de las 8 celdas vecinas) y elije la acción de movimiento (si no puede moverse allí, permanecerá en la misma celda).
Se ejecuta el tiempo máximo establecido.
Para un espacio de 100x100, considera los siguientes escenarios:

Escenario 1: 1 agente, 90% de celdas sucias.
Escenario 2. 2 agentes, 90% de celdas sucias.

