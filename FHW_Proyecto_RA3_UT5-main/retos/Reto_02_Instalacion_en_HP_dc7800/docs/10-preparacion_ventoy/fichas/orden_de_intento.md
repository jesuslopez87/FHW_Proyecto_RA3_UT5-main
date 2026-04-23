# Ficha · Orden de intento de instalación

## Orden previsto

1. **Primera opción:** antiX Linux
   - Motivo: Ofrece un excelente equilibrio entre bajo consumo de recursos y un entorno de trabajo completo. Al estar basada en Debian, suele tener muy buena compatibilidad de hardware legacy y su instalador es bastante estable.
2. **Segunda opción:** Puppy Linux
   - Motivo: Es extremadamente ligera y tiene la particularidad de cargarse completamente en la memoria RAM. Es la alternativa perfecta si antiX falla o si el disco duro mecánico del equipo presenta problemas de lentitud o lectura.
3. **Tercera opción:** Tiny Core Linux
   - Motivo: Es la distribución más minimalista y de menor tamaño. Se reserva como último recurso absoluto por si el hardware tiene limitaciones extremas, aunque requiere mucha más configuración manual por parte del usuario.

## Justificación breve

El orden elegido sigue una lógica de "mayor a menor usabilidad/facilidad" dentro del espectro de las distribuciones ligeras. Se empieza con antiX, que da la experiencia más parecida a un escritorio tradicional (ideal para dejar el equipo funcional). Si falla, se recurre a Puppy para descartar problemas de disco duro gracias a su ejecución en RAM. Finalmente, Tiny Core queda como el "salvavidas" técnico si las otras dos no logran arrancar.

## Regla de cambio

La ISO no arranca desde el menú de Ventoy (se queda la pantalla en negro o da un error de kernel panic).

El instalador se congela completamente en algún paso y no permite continuar tras varios minutos.

El instalador no es capaz de detectar el disco duro del HP Compaq para realizar las particiones.

La instalación falla repetidamente al intentar escribir en el disco o al instalar el gestor de arranque (GRUB).

Tras indicar que la instalación ha sido un éxito, el equipo no es capaz de arrancar desde el disco duro.
