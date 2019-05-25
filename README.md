# Buenas pr�cticas de desarrollo con GIT

En este repositorio intentar� seguir los trabajos en clase, aplicando y demostrando el uso de buenas pr�cticas tanto de escritura de c�digo como de uso de la herramienta git. A continuaci�n dejo algunas claves �tiles.

## Control de versiones con GIT

A continuaci�n expongo algunas claves para trabajar con GIT, tal como a mi me result� �til.

### Cambios peque�os

Es una excelente pr�ctica a�adir peque�os cambios al repositorio, cada uno contenido en su propia commit, en lugar de un paquete de cambios grande.

Por ejemplo, si te fijas en el registro de cambios o la lista de commits, vas a ver que primero agregu� el archivo de soluci�n, junto con un par de archivos espec�ficos de git muy �tiles.

Pens� en que en el desarrollo de software cada cosa tiene que estar documentada y git lo que hace es guardar los cambios en lugar de los archivos completos.

Si los cambios que haces est�n contenidos en varios archivos, lo ideal es que est�n estrechamente relacionados.

### Mensajes claros

Cuando escribas el mensaje de una commit, lo mejor es detallar exactamente qu� cambio hiciste. No es necesario detallar cambios espec�ficos de c�digo, pero s� un mensaje gen�rico que indique el modo de operaci�n tras el cambio.

Por ejemplo:

    Cambio.

Este mensaje, para una commit, no es muy claro, por lo que si alguien ve este mensaje, tendr� que bucear por el archivo de diferencias para determinar qu� cambios hiciste.

    Se cambi� el orden de los operandos en el m�dulo de divisi�n, estaban ordenados incorrectamente.

Este mensaje detalla un poco mas el cambio, sin ser demasiado espec�fico ni incluir l�neas de c�digo.

### Un archivo *README* en la ra�z de cada repositorio

Por ejemplo este archivo est� en la ra�z del repositorio.

En realidad, es un archivo de texto plano con algunas adiciones. El formato se llama *Markdown* y es muy �til para escribir documentaci�n sin usar Word. Adem�s, hay herramientas integradas en github que permiten referenciar algunos de sus contenidos sin mucho tr�mite.

### Un archivo *.gitignore* como m�nimo

El archivo [.gitignore](.gitignore) lista los archivos o patrones de nombres de archivos que se ignoran del repositorio. Por ejemplo, en el archivo que genera *Visual Studio*, se listan todas las carpetas que contienen configuraci�n de la PC o resultados de compilaci�n. Es decir, cuando sub�s c�digo con este tipo de cosas ignoradas, evitas que tu repositorio crezca en tama�o.

Dej� el archivo sin modificar en el repositorio para que lo puedas leer y ver como funciona.

## C�digo

Esta secci�n la voy a escribir en otro momento.

## Conclusi�n

En el mundo del desarrollo de software se nos pide mucha rigurosidad con la documentaci�n y con el c�digo. Generalmente, sobre todo si trabajas como programador, ten�s que seguir un modelo ya dise�ado y planeado hasta el m�s m�nimo detalle. Por eso es importante prestar atenci�n a la mayor cantidad posible de detalles.

Denuevo, cualquier cosa en que necesites ayuda para la asignatura, solo ten�s que preguntarme. Si quer�s, pod�s abrir un tema en el foro o abrir una issue en este repositorio mismo.