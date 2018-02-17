# Rastreador de "System Calls"

Se debe poder ejecutar otro programa, pasarle argumentos seleccionados por el usuario y rastrear todos los ustem calls utilizados por el otro programa.

Sintaxis de ejecucion:

rastreador [opciones rastreador] Prog [opciones de prog]

Las [opciones rastreador] podrian no venir del todo o aparecer en cualquier orden o combinacion valida.

AL final de la ejecucion, aparecera una tabla acumulativa que muestre todos los System_Calls utilizados por Prog, asi como el numero de veces que utilizo cada uno.

Las opciones de prog no seran analizadas ni consideradas por rastreador.

Las [opciones de rastreador] validas son:

- -v desplegara un mensaje cada vez que detecte un system call de prog. Se debe desplegar la mayor cantidad posible de detalles respecto a cada system call.

- -V sera indentico a la opcion -v. Pero hara una pausa hasta que el usuario presione cualquier tecla para continuar con la ejecucion de prog.
