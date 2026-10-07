1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.
Fork:
Crear una copia del repositorio del otro desarrollador en tu propia cuenta de GitHub.
Clone:
Descargar esa copia del repositorio a tu computadora para poder trabajar localmente.
Branch:
Crear una nueva rama para trabajar en los cambios sin afectar la rama principal.
Modificar archivos:
Realizar los cambios, agregar funciones, corregir errores o modificar el código necesario.
Commit:
Guardar los cambios en el repositorio local con un mensaje que explique qué se modificó.
Push:
Subir la nueva rama y sus commits desde tu computadora a tu repositorio de GitHub.
Pull Request:
Solicitar al desarrollador original que revise tus cambios y considere agregarlos a su repositorio.
Review:
El desarrollador revisa el código y puede aprobarlo, solicitar cambios o hacer comentarios.
Modificar archivos nuevamente:
Si se solicitan cambios durante la revisión, realizas las correcciones y haces otro Commit y Push.
Merge:
Cuando los cambios son aprobados, el desarrollador integra tu rama con la rama principal mediante un Merge.

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.

es incorrecta
Clone: Crea una copia del repositorio en tu computadora, no dentro de tu cuenta de GitHub. Sirve para descargar el proyecto y trabajar con él de manera local.
Fork: Crea una copia del repositorio directamente en tu cuenta de GitHub. Esto permite modificar el proyecto desde tu propio repositorio y posteriormente enviar un Pull Request al repositorio original.

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

los cambios todavía no forman parte del repositorio original.
Después de hacer Fork, Clone, Branch, Modificar, Commit y Push, los cambios están únicamente en tu repositorio.
Para incorporarlos al repositorio original debes:
.Crear un Pull Request desde tu repositorio hacia el repositorio original.
.El desarrollador original debe revisar los cambios.
.Si los aprueba, realiza un Merge.
.Después del Merge, tus cambios pasan a formar parte del repositorio original.

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

Cuando el propietario selecciona Request Changes, significa que encontró algo que debes corregir en tu código.

Debes:
Revisar los comentarios del propietario.
Modificar los archivos según las correcciones solicitadas.
Hacer un nuevo Commit con los cambios.
Hacer nuevamente Push a la misma rama.
No necesitas crear otro Pull Request. El Pull Request original se actualiza automáticamente cuando haces Push a la misma rama.
Después, el propietario puede revisar nuevamente los cambios y, si todo está correcto, aprobarlos y hacer Merge.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

Esto sucede porque el Merge se realizó en GitHub, es decir, en el repositorio remoto. Los cambios no se descargan automáticamente al repositorio local del propietario.
Para actualizar su repositorio local debe realizar:
git pull
Esta operación descarga los cambios del repositorio remoto y los integra en el repositorio local.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.

La herramienta que utilizaría es Sync Fork de GitHub.
Sync Fork: Actualiza tu Fork en GitHub con los cambios nuevos que existen en el repositorio original.
git pull: Actualiza tu repositorio local descargando los cambios desde un repositorio remoto.
Diferencia:
Sync Fork → actualiza el Fork en GitHub.
git pull → actualiza el repositorio en tu computadora.

