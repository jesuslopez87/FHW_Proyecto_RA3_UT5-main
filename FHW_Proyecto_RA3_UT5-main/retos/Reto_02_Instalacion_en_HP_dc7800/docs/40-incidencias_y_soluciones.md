# Problemas encontrados y soluciones aplicadas

En esta sección se recopilan los fallos o dificultades del proceso.  
No importa que hayan sido pequeños o grandes: lo importante es que queden bien explicados.

## Incidencia 1
- Descripción: El ordenador no encendía o se apagaba de forma repentina debido a un exceso de consumo energético.
- Cuándo apareció: Al intentar encender el equipo por primera vez, antes de poder iniciar la instalación.
- Posible causa: La fuente de alimentación no tenía la capacidad suficiente (vatios) para soportar todo el hardware conectado.
- Solución aplicada: Se desconectaron y retiraron 3 tarjetas de expansión que no eran estrictamente necesarias para el equipo.
- Resultado: El consumo de energía disminuyó y el PC logró arrancar y mantenerse encendido de forma estable.

## Incidencia 2
- Descripción: El equipo presentaba errores de lectura de hardware y el sistema no detectaba ninguna unidad de almacenamiento para la instalación.
- Cuándo apareció: Durante las comprobaciones iniciales de arranque (POST) y al llegar a la fase de particionado de discos.
- Posible causa: Un mal ensamblaje físico; los módulos de RAM no estaban bien encajados en sus ranuras y los cables del disco duro estaban sueltos o sin conectar.
- Solución aplicada: Se abrió el equipo, se volvieron a asentar correctamente los módulos de memoria RAM y se conectaron los cables de datos (SATA) y de alimentación al disco duro.
- Resultado: La BIOS reconoció la totalidad de la memoria RAM y el disco duro apareció visible y listo para ser utilizado por el instalador.

## Incidencia 3
- Descripción: La pantalla se quedaba completamente en negro y el sistema se congelaba al intentar arrancar el instalador desde el pendrive.
- Cuándo apareció: Justo después de seleccionar el USB en el menú de arranque
- Posible causa: Muerte del PC
- Solución aplicada: Intentar la instlacion en otro PC
- Resultado: Correcto

## Aprendizaje técnico

Durante esta práctica hemos aprendido que muchos de los problemas al instalar un sistema operativo provienen del hardware y no del software. Para futuras instalaciones, el primer paso será realizar una revisión física del equipo (comprobar que la RAM, los discos y los cables estén bien conectados) y asegurar que la fuente de alimentación no esté sobrecargada. Además, hemos aprendido a no atascarnos ante un fallo de incompatibilidad de software/hardware (como el problema de arranque con Ventoy), descubriendo que usar un equipo alternativo para instalar el sistema en el disco es una solución muy práctica y efectiva que nos permite avanzar.
