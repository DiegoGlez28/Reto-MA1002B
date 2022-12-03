
# Reto-MSED: Ecuaciones Lotka-Volterra

## Integrantes del equipo: 

- Alan Alberto Mota Yescas - A01753924  
- Daniela Pamelin Alvarez Guarneros - A01026164  
- Diego Arturo González Juarez - A01747987  
- Sebastian Jimenez Alcantara - A01754993  
- Hendrik Steven Arias López - A01378065  

## Objetivo: 

Lo que se busca realizar esta tercera fase es encontrar una solución estocástica de las ecuaciones de Lotka-Volterra.  

El modelo matemático que se utlizara es una cadena de Markov continua. Es decir es una serie de eventos, donde la probabilidad de que ocurra el próximo evento depende del evento inmediato anterior, cada evento realizado tiene variables, condiciones y datos que ayuda al resultado del próximo evento.  

Ahora bien si se considera un ecosistema donde hay presas (presas, P) y depredadores (D). La descripción de la dinámica del sistema se puede hacer a través de los posibles procesos:  

- P → 2P  
- P+D →2D  
- D → 0  

El primero de ellos representa el crecimiento de las presas, el segundo el crecimiento de los depredadores como consecuencia de comer las presas y el tercero la muerte de los depredadores por razones naturales.
