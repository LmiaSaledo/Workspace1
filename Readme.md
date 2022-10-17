# Git y Markdown

## Indice 
*  ¿Qué es Git?
* ¿Caracteristicas de Git?
*  ¿El funcionamiento de Git?
* Terminos tecnicos que se utilizan en Git
#
* ¿Qué es Markdown?
 * Conceptos basicos de Markdown.
 

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

## repository
### Un repositorio es el elemento más básico de GitHub. Es más fácil imaginarlos como carpetas de proyecto. Un repositorio contiene todos los archivos de un proyecto (incluyendo la documentación), y almacena el histórico de modificaciones de cada archivo. Los repositorios pueden tener múltiples colaboradores y pueden ser tanto públicos como privados.
#
## commit
### Un commit se puede entender como la confirmación de una modificación individual en un archivo (o serie de archivos). Es como cuando guardas un archivo, excepto que con Git, cada vez que haces commit se crea un ID único (también conocido como SHA o hash) que te permite registrar qué cambios se hicieron y quién los hizo. Los commits generalmente contienen un mensaje de commit que consiste en una breve descripción de los cambios realizados.
#
## push
### Literalmente, empujar. Se refiere a enviar tus cambios confirmados (tus commits) a un repositorio remoto, como por ejemplo un repositorio alojado en GitHub. Si cambias algo localmente, querrás hacer push de esos cambios para que los demás miembros de tu equipo puedan acceder a ellos.
#
## pull
### Literalmente, tirar. Se refiere a traer los cambios del servidor remoto y combinarlos con tu copia local. Por ejemplo, si alguien ha editado el archivo remoto en el que ambos estáis trabajando, querrás hacer pull de esos cambios a tu copia local para que esté actualizada.
#
## issue
### Los issues son sugerencias de mejora, tareas o cuestiones relacionadas con el repositorio o el proyecto. Cualquiera puede crear issues (en un repositorio público), y los moderan los colaboradores del repositorio. Cada issue contiene su propio foro de dissusión, y se puede etiquetar y asignar a un usuario.
#
## pull request
### Los pull requests o, literalmente, solicitudes de tirar, son cambios propuestos para un repositorio que un usuario ha enviado, y que pueden ser aceptados o rechazados por los colaboradores del repositorio. Igual que los issues, los pull requests tienen cada uno su propio foro de discusión.
#
## branch
### Un branch o, literalmente, rama, es una versión paralela de un repositorio. Está contenido dentro del repositorio, pero no afecta al branch principal o master, permitiéndote trabajar libremente sin estropear la versión “real”. Cuando has terminado de realizar los cambios que querías hacer, puedes hacer merge de tu branch al branch principal para publicar tus cambios.
#
## merge
### Literalmente, combinar. Hacer merge toma los cambios de un branch (en el mismo repositorio o también desde un fork), y los aplica en otro. Esto a menudo ocurre como un pull request (que se puede entender como una solicitud de hacer merge), o a través de la línea de comandos. Un merge puede realizarse automáticamente a través de un pull request en la interfaz web de GitHub siempre y cuando no haya cambios que generen conflictos, o puede hacerse siempre via línea de comandos.
#
## remote
### La versión remota es una versión de algo que está alojada en un servidor, muy probablemente GitHub en este contexto. Puede estar conectado a clones locales de forma que los cambios se sincronicen.
#
## local
### La versión local es la copia que tienes del repositorio en tu ordenador, sobre la que trabajas.
#
## clone
### Un clon es la copia de un repositorio que se aloja en tu ordenador, en lugar de en un servidor en alguna parte, o el acto de realizar esa copia. En tu clone puedes editar los archivos en tu editor preferido y utilizar Git para llevar un registro de esas modificaciones sin necesidad de tener conexión a internet. Sin embargo, este clon está conectado a la versión remota de forma que los cambios se puedan sincronizar entre ambos. Puedes hacer push de tus cambios locales a la versión remota para mantenerlas sincronizadas cuando estés online.
#
## fork
### Un fork o, literalmente, tenedor, es una copia personal de un repositorio de otro usuario que se aloja en tu cuenta. Los forks te permiten modificar libremente cualquier proyecto sin alterar el original. Los forks se mantienen relacionados con el original, de manera que puedes enviar un pull request al autor del repositorio original para que lo actualice con tus cambios. También puedes mantener tu fork actualizado haciendo pull de las modificaciones del original.
#
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