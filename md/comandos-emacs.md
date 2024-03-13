# Guía personal de comandos para EMACS 

## Funcionalidades esenciales
Salir ->  CTRL+X, CTRL+C,
Detener emacs/comando con seguridad -> CTRL+G
Iterar varias veces un comando: C+U(numero)(comando)
Iterar varias veces un caracter:  C+U(numero)(caracter)

Buscar ayuda comando -> CTRL+H, k, (comando)

## Desplazamiento por el documento 

Subir -> ALT+V (REPAG)
Bajar -> CTRL+V (AVPAG)
Centrar la vista en el cursor -> CTRL+L

ALT+< Principio de la pantalla 
ALT+> Final de la pantalla

## Mover el cursor

CTRL+B (back, atras en la linea) <-
CTRL+F (forward, adelante en la línea) ->
CTRL+P (prev, linea anterior)
CTRL+N (next, linea suguiente)

### Al principio de una línea u oración

CTRL+A -> Principio de una línea 
CTRL+E -> Final de una línea

ALT+A -> Principio de una oración 
ALT+E -> Final de una oración

## Ventanas

Volver a 1 ventana -> CTRL+X 1

CTRL+ALT+V -> Deslizar ventana emergente hacia abajo
CTRL+X+O -> Focalizarse en la otra ventana
CTRL+X+4+CTRL+F -> Focalizarse en otra ventana con un nombre de archivo
CTRL+X+3-> Partir verticalmente
CTRL+X+2-> Partir horizontalmente

## Escribir 

Quitar modo solo lectura: CTRL+x CTRL+q 

CTRL+/ -> Deshacer

### Eliminar

ALT+DELETE -> Eliminar por palabras
 
CTRL+D -> Botón de suprimir
ALT+D-> Boton de suprimir 
or palabras

CTRL+K -> Eliminar linea a partir de posición del cursor
CTRL+Espacio -> Seleccionar texto 
CTRL+W -> Cortar texto seleccionado 
CTRL+Y -> Pegar texto cortado

## Archivos (comandos extendidos): 

Crear archivo -> CTRL+x CTRL+f 
Guardar archivo -> CTRL+x CTRL+s
Ver buferes de archivos -> CTRL+X, CTRL+Cambiar
Cambiar de archivo - CTRL+X b TUTORIAL.es

Recuperar copia de seguridad guardada: ALT+X recover-file

Reemplazar strings: ALT+X repl s (enter) (stringacambiar) (enter) (stringcambiado) 

## Modos

Hay varios modos en emacs, en cada cual los comandos pueden variar dependiendo de la tarea. 
Por ejemplo, *markdown-mode* permite trabajar con markdown.

Para redactar texto: ALT-X text-mode

Para conseguir un ajuste en parrafo: ALT-X auto-fill-mode

Cambiar caracteres de largo para los parrafos: CTRL+X+F

Cambiar el parrafo a la forma actual: ALT+Q

Buscar texto: CTRL+s (texto) adelante CTRL+r (texto) atras -> 

### Modo líneas

Debe instalarse y luego ejecutarse en ALT+X (display-line-numbers-mode). 

### Nuevos modos

Pueden incrustarse nuevos modos mediante la modificación del archivo de inicio, que está en `.emacs.d>int.el`. 
