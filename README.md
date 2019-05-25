# Buenas prácticas de desarrollo con GIT

En este repositorio intentaré seguir los trabajos en clase, aplicando y demostrando el uso de buenas prácticas tanto de escritura de código como de uso de la herramienta git. A continuación dejo algunas claves útiles.

## Control de versiones con GIT

A continuación expongo algunas claves para trabajar con GIT, tal como a mi me resultó útil.

### Cambios pequeños

Es una excelente práctica añadir pequeños cambios al repositorio, cada uno contenido en su propia commit, en lugar de un paquete de cambios grande.

Por ejemplo, si te fijas en el registro de cambios o la lista de commits, vas a ver que primero agregué el archivo de solución, junto con un par de archivos específicos de git muy útiles.

Pensá en que en el desarrollo de software cada cosa tiene que estar documentada y git lo que hace es guardar los cambios en lugar de los archivos completos.

Si los cambios que haces están contenidos en varios archivos, lo ideal es que estén estrechamente relacionados.

### Mensajes claros

Cuando escribas el mensaje de una commit, lo mejor es detallar exactamente qué cambio hiciste. No es necesario detallar cambios específicos de código, pero sí un mensaje genérico que indique el modo de operación tras el cambio.

Por ejemplo:

    Cambio.

Este mensaje, para una commit, no es muy claro, por lo que si alguien ve este mensaje, tendrá que bucear por el archivo de diferencias para determinar qué cambios hiciste.

    Se cambió el orden de los operandos en el módulo de división, estaban ordenados incorrectamente.

Este mensaje detalla un poco mas el cambio, sin ser demasiado específico ni incluir líneas de código.

### Un archivo *README* en la raíz de cada repositorio

Por ejemplo este archivo está en la raíz del repositorio.

En realidad, es un archivo de texto plano con algunas adiciones. El formato se llama *Markdown* y es muy útil para escribir documentación sin usar Word. Además, hay herramientas integradas en github que permiten referenciar algunos de sus contenidos sin mucho trámite.

### Un archivo *.gitignore* como mínimo

El archivo [.gitignore](.gitignore) lista los archivos o patrones de nombres de archivos que se ignoran del repositorio. Por ejemplo, en el archivo que genera *Visual Studio*, se listan todas las carpetas que contienen configuración de la PC o resultados de compilación. Es decir, cuando subís código con este tipo de cosas ignoradas, evitas que tu repositorio crezca en tamaño.

Dejé el archivo sin modificar en el repositorio para que lo puedas leer y ver como funciona.

## Código

Esta sección la voy a escribir en otro momento.

## Conclusión

En el mundo del desarrollo de software se nos pide mucha rigurosidad con la documentación y con el código. Generalmente, sobre todo si trabajas como programador, tenés que seguir un modelo ya diseñado y planeado hasta el más mínimo detalle. Por eso es importante prestar atención a la mayor cantidad posible de detalles.

Denuevo, cualquier cosa en que necesites ayuda para la asignatura, solo tenés que preguntarme. Si querés, podés abrir un tema en el foro o abrir una issue en este repositorio mismo.