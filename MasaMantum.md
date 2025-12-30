# PLAN DE IMPLEMENTACIÓN BI MASA

## MANTENIMIENTO

### Hoja de excel 1

Mantenimiento realiza procesos de mantenimiento cada 250 horas alimentando en un excel día a día el último horómetro. De allí se extrae un indicador que consiste en un porcentaje de cumplimiento de mantenimiento programados vs mantenimiento realizado.
A mantenimiento le interesaría que se alimentara automáticamente mes a mes.

### Hoja de excel 2

Se ingresan la información del equipo y la frecuencia del mantenimiento, la fecha y horómetro y/o kilometraje del último mantenimiento y el tipo de mantenimiento ejecutado (M1, M2, M3, M4), una serie que ellos manejan de 1 a 5, próximo mantenimiento, fecha del último registro y último registro (horómetro y/o kilometraje), horas o kilometraje faltante, estado actual y, si aplica, la actividad ("pedir material"), crea una ID y activa la OT. La OT activa la SLC basado al tipo de mantenimiento. Luego se genera el registro para generar la orden en matum, activar la OT y la SLC.

Cuando se cierra la OT en mantum se deja registro en el excel haciendo un cambio de color de azul a blanco.

### Mantum

1) Listado general de ordenes de trabajo (OT):
    * Para cerrar la OT en mantum se debe cumplir con:
        * le deben pasar la OT física (checklist) registrando horómetro y la fecha en el que se realizó.
        * Cumplir con que se haya realizado una salida de los insumos (columna "Retroalimentación" de mantum).

            IMPORTANTE: Columna "Actividades" filtrado por MP4. MP = mantenimiento preventivo, va de 1 al 5, el resto son correctivas

2) Informe variables resultado AM: Cuando van a cerrar la OT podrían registrar el Horómetro al momento de cerrar la OT, pero hasta el momento no se está haciendo --> Columna "ultima lectura".

3) Informe general ordenes de trabajo: Serviría para revisar cuantas OT se han realizado por x periodo de tiempo, para revisar costos.

4) Informe AM dinámico: puede servir para verificar cuantas OT se han hecho correctivas y cuantas preventivas.

5) Revisar:
    * idinstalacionesproceso
    * idvariableequipo: descripción de equipos
    * id_paroequipo: se puede sacar el tiempo medio entre fallas, tiempo de duración de paro

**IMPORTANTE:**

* Revisar con mantenimiento que las OT que deberían estar cerradas hasta el momento realmente se cierren. Ej: AH05, aparece con 3 OT abiertas.
* Revisar con Mantenimiento que se comience a alimentar el horómetro.
Montar un indicador que se vaya actualizando a medida que se vaya limpiando.
* Se necesita el indicador de que es latonería y pintura, que es reparación electrica, etc, es decir, separar lo preventivo de lo correctivo.
