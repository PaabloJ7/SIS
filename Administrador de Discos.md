# Administrador de Discos

1. **Indica el número de discos que tiene vuestro equipo de clase, la capacidad de cada uno de los discos y el tipo de sector de arranque que usa.**

| Num Disco | Estado   | Tamaño | Disp   | Din  | GPT  |
| --------- | -------- | ------ | ------ | ---- | ---- |
| 1         | En Linea | 465GB  | 1024kb |      | *    |
| 2         | En Linea | 447GB  | 101MB  |      | *    |



2. **Para cada uno de los discos, realiza una tabla con las particiones que tiene indicando para cada una de las particiones, el tipo de partición la capacidad y el desplazamiento.**

Num Particion | Tipo        | Tamaño | Desplazamiento |
| ------------- | ----------- | ------ | -------------- |
| Particion 1   | Sistema     | 100 MB | 1024 KB        |
| Partición 2   | Principal   | 185 GB | 101 MB         |
| Partición 5   | Desconocido | 58 GB  | 185 GB         |
| Partición 3   | Principal   | 101 GB | 244 GB         |
| Partición 4   | Desconocido | 120 GB | 345 GB         |

| Num Particion | Tipo         | Tamaño | Desplazamiento |
| ------------- | ------------ | ------ | -------------- |
| Particion 1   | Reservado    | 16 MB  | 1024 KB        |
| Partición 2   | Principal    | 221 GB | 117 MB         |
| Partición 3   | Principal    | 224 GB | 222 GB         |
| Partición 4   | Recuperación | 522 MB | 446 GB         |

   

3. **Realiza una tabla con los volúmenes que tiene el equipo e indica: su número, letra asignada, sistema de archivos, capacidad, etiqueta, el tamaño y el tipo.**

   | Num Volumen | Letra | Etiqueta  | Formato | Tipo      | Tamaño | Info    |
   | ----------- | ----- | --------- | ------- | --------- | ------ | ------- |
   | Volumen 1   |       | DATA_ASIR | NTFS    | Partición | 185GB  |         |
   | Volumen 2   | H     | DATA_DAW  | NTFS    | Partición | 101GB  |         |
   | Volumen 3   |       |           | FAT32   | Partición | 100MB  | Sistema |

   

4. Veamos en detalle un volumen. Selecciona uno de los volúmenes del equipo cuyo sistema de archivos sea de tipo NTFS e indica el espacio ocupado por esta unidad.

5. Selecciona la partición de tipo “principal” que tenga más capacidad e indica: si es una partición activa, si es oculta, qué letra tiene asignada en el equipo y el sistema de archivos.

6. Por último, vamos a seleccionar el disco con más capacidad y anotaremos de este: modelo de disco duro, el tipo y si es disco de arranque.

Una vez recogidos estos datos, vamos a reflexionar sobre éstos respondiendo a las siguientes preguntas (las reflexiones son personales y debatidas y consensuadas en pareja):

1. Observa el disco que seleccionaste en el ejercicio 2, anota para este disco su tipo de sector de arranque (anotado en el ejercicio 1) y el número de particiones total que posee. ¿Es posible que este tipo de sector de arranque maneje ese número de particiones? ¿Por qué?

2. En la lista de particiones del ejercicio 2, observa el desplazamiento de la última partición ¿por qué tiene ese valor? Razona la respuesta.

3. En la lista de volúmenes, probablemente exista un volumen que no tiene nada de capacidad (0B), ¿por qué crees que sucede esto?

4. En el ejercicio 5 se pedía que anotaras si la partición seleccionada es “activa”. Indica qué es la partición activa de un disco duro.
