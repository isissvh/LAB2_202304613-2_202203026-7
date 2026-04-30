# Laboratorio 2: Arquitectura y Organización de Computadores

## 1. Integrantes
* **Nombre:** Isidora Villegas | **Rol:** 202203026-7
* **Nombre:** Héctor Chanampe | **Rol:** 202304613-2
* **Paralelo:** 201


---

## Contexto  
Readme de la tarea 2 de la asignatura de arquitectura y organización de computadores. Aquí encontrará información importante sobre como se desarrolló la tarea hasta como poder utilizar el programa.

## Desarrollo

1. Para un mejor orden se creó primero un diagrama con todos los posibles valores del display
2. Luego se crearon tanto la tabla de verdad como los Mapas de Karnaugh
3. Se procedió a las simplificaciones de cada expresión obtenida
4. Con aquellos resultados se crearon los circuítos con la herramienta 'logisim-evolution'
   - Dentro del circuito se crearon 'main' (prinicipal para el funcionamiento) y los subcircuitos 'A', ... 'G'
5. Se comprobaron todos los mensajes y su funcionamiento óptimo

## Supuestos utilizados

Para las funciones de los segmentos $S_f$ y $S_a$, se asumió que la simplificación mediante compuertas XOR y NOR respectivamente era preferible para mantener un diseño compacto.

## Instrucciones para ejecutar el circuito

1. Cargue el archivo decodificador.circ en el software.
2. Asegúrese de estar posicionado en el circuito llamado "main".
3. Seleccione la herramienta Poke (icono de la mano en la barra superior).
4. Interactúe con los pines de entrada etiquetados como A0, A1, A2 y A3 para ingresar el código binario deseado.
5. El display central mostrará automáticamente el símbolo decodificado correspondiente al suceso de la partida.