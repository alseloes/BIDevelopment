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
    * Revisar que es _idam_ en informevariablesresultadoam

**IMPORTANTE:**

* Revisar con mantenimiento que las OT que deberían estar cerradas hasta el momento realmente se cierren. Ej: AH05, aparece con 3 OT abiertas.
* Revisar con Mantenimiento que se comience a alimentar el horómetro.
Montar un indicador que se vaya actualizando a medida que se vaya limpiando.
* Se necesita el indicador de que es latonería y pintura, que es reparación electrica, etc, es decir, separar lo preventivo de lo correctivo.
* Consultar si hay más KPIS de mantenimiento (Gustavo).

## ABASTECIMIENTO

### Inquietudes

1) Datos generales de órdenes de compra/Almacén: Qué hacer con las que están en almacén 01?
2) Columnas Estado, Estado SOC, Estado aprobación... cual es la lógica de la nomemclatura
3) Código SOC --> SLC-XXX? Todas tienen SLC
4) Qué tan objetivo se alimenta la fecha de espera?
5) cual es el criterio de aceptación para saber si una entrega está retrasada? cual es la tolerancia?
6) Qué tanto se alimenta la fecha de entrega? por qué no siempre se alimenta?
7) Cuales son los KPIs qué se están manejando?
8) Id bodega a veces llega null... qué hacer en esos casos?
9) Estado almacén: Qué es un almacén inactivo?

## OPERACIONES

## GESTIÓN HUMANA
