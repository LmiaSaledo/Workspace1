
 

 #

 # **Git**
 ### Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

## Sus caracteristicas.
 * Es muy potente
* Fue diseñada por Linus Torvalds
* No depende de un repositorio central
* Es software libre
* Con ella podemos mantener un historial completo de  versiones
* Podemos movernos, como si tuviéramos un puntero en el tiempo, por todas las revisiones de código y desplazarnos una manera muy ágil.
* Es muy rápida
* Tiene un sistema de trabajo con ramas que lo hace especialmente potente
* En cuanto a la funcionalidad de las ramas, las mismas están destinadas a provocar proyectos divergentes de un proyecto principal, para hacer experimentos o para probar nuevas funcionalidades.

## Su funcionamiento.
 1. Crea un "repositorio" (proyecto) con una herramienta de alojamiento de Git (por ejemplo, Bitbucket).
2. Copia (o clona) el repositorio a tu máquina local.
3. Añade un archivo a tu repositorio local y confirma. ("commit") los cambios.
4. Envía ("push") los cambios a la rama principal.
5. Haz cambios en tu archivo con una herramienta de alojamiento de Git y confírmalos.
5. Extrae ("pull") los cambios a tu máquina local
Crea una rama ("branch", versión), haz algún cambio y confírmalo.
5. Abre una solicitud de incorporación de cambios ("pull request": propón cambios a la rama principal).
6. Fusiona ("merge") tu rama con la rama principal.}


# **Markdown**
### Markdown es un lenguaje de marcado ligero creado por John Gruber y Aaron Swartz que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.
#
## Conceptos basicos.
## Encabezados
### Markdown dispone de cuatro niveles de encabezados definidos por el número de # antes del texto del encabezado. Pega los siguientes ejemplos en la caja de texto de la izquierda:
#
# Primer nivel de encabezado
## Segundo nivel de encabezado
#
### Tercer nivel de encabezado
#
#### Cuarto nivel de encabezado
#
## El primer y segundo nivel de encabezado también se pueden escribir como sigue:
#
Primer nivel de encabezado
==========================

Segundo nivel de encabeado
--------------------------

## Lista de compraslista-de-compras
* Frutas 

* Manzanas
* Naranjas
* Uvas
* Lácteos
* Leche
* Queso
### Las listas ordenadas se escriben numerando cada línea. Una vez más, el objetivo de Markdown es producir documentos que sean legibles como texto plano y que a la vez puedan traducirse a otros formatos.
#
Lista de pendientes
------------------
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo
#
## Enlaces de Internetenlaces-de-internet

### Los enlaces de Internet se pueden escribir de dos maneras.

### El título del enlace se encierra primero entre corchetes y después se incluye la dirección completa del URL entre paréntesis.

### Para más tutoriales visita la página [The Programming Historian en español](/es).

### Lo cual se representa así:

### Para más tutoriales visita la página The Programming Historian en español.

### Los enlaces también se utilizan para crear notas a pie de página y son útiles porque, además, ayudan a mantener más ordenado tu documento en texto plano. Las notas a pie se escriben con un par adicional de corchetes con el número de referencia para establecer el vínculo que identifique la etiqueta.

### Un ejemplo es el sitio *[The Programming Historian en español][1]*

### Entonces puedes incluir el URL en otra parte del documento:

### [1]: http://programminghistorian.org/

### Lo cual se despliega de la siguiente manera:

### Un ejemplo es el sitio The Programming Historian en español

## Imágenes

### Se pueden referir las imágenes mediante el uso de !, seguido de un texto alternativo entre corchetes, seguido a su vez por el URL de la imagen y un título opcional entre comillas. Esto no se representará como texto en tu documento pero te permitirá incluir la imagen en la visualización de una página en HTML.
#
![Logo de Wikipedia](https://upload.wikimedia.org/wikipedia/en/8/80/Wikipedia-logo-v2.svg "Wikipedia logo")