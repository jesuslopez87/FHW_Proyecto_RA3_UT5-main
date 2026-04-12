# Tabla comparativa de ISOs


| ISO             | Versión            | Arquitectura | RAM mínima | Disco mínimo | Tamaño ISO | Ventajas                                                      | Inconvenientes                                      | Decisión   |
| ----------------- | --------------------- | -------------: | ------------: | --------------: | ------------: | --------------------------------------------------------------- | ----------------------------------------------------- | ------------- |
| antiXISO 01     | 23.1                |          x64 |      256 MB |          5 GB |      2,1 GB | Completa, lista para usar, ultraligera sin systemd.           | Interfaz anticuada, sin comandos systemd estándar. | Principal   |
| PuppyISO 02     | BookwormPup 10.0.12 |          x64 |      300 MB |         ~1 GB |      791 MB | Corre directamente en RAM, ultrarrápida frente a HDD lentos. | Sistema de guardado persistente algo confuso.       | Alternativa |
| Tiny CoreISO 03 | 15.0 CorePlus       |          x64 |      128 MB |         50 MB |       25 MB | Inmune a hardware obsoleto, consumo casi inexistente.         | Demasiado básica, requiere instalar todo a mano.   | Respaldo    |

## Resumen de la comparación

Tras analizar las características del HP Compaq dc7800, **antiX Linux se perfila como la opción principal (más equilibrada)** . Ofrece una experiencia de escritorio lista para usar nada más instalarse, con herramientas suficientes para una clase sin ahogar la memoria.

**Puppy Linux queda como una alternativa muy fuerte** gracias a su carga en RAM, ideal si comprobamos que el desgaste del disco duro mecánico hace inusable antiX. Finalmente, **Tiny Core se reserva como la opción de seguridad absoluta (respaldo)** ; si nada más funciona, Tiny Core arrancará sin dudarlo, aunque requerirá un mayor esfuerzo de configuración manual por parte del usuario
