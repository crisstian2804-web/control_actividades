1. Analiza
git status
git add README.md
git commit -m "Actualiza documentación"
git push

este conjunto de comandos sirve para guardar y subir un cambio específico al repositorio remoto.
git status
Muestra el estado del repositorio y permite ver qué archivos fueron modificados.
git add README.md
Agrega el archivo README.md al área de preparación (staging) para incluirlo en el próximo commit.
git commit -m "Actualiza documentación"
Guarda los cambios preparados en el historial local con el mensaje indicado.
git push
Envía el commit desde el repositorio local hacia el repositorio remoto, por ejemplo, GitHub.

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

La operación que falta es:
git commit -m "Descripción del cambio"

¿Para qué sirve?
git commit guarda los cambios preparados con git add en el historial local de Git. El mensaje indica qué se modificó.

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

La operación que utilizaría es git clone.

¿Por qué?
git clone permite copiar un repositorio desde GitHub a la computadora, creando un repositorio local con sus archivos e historial.

Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
Indica qué operación utilizarías y explica por qué.

La operación que utilizaría es git pull.

¿Por qué?
git pull permite descargar los cambios más recientes del repositorio remoto y actualizar el repositorio local.