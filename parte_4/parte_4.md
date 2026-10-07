1. Explica la diferencia entre Git y GitHub.
Git es un sistema de control de versiones que permite guardar y controlar los cambios de un proyecto en la computadora.
GitHub es una plataforma en línea que permite almacenar repositorios Git y colaborar con otras personas.
2. Explica para qué sirve .gitignore.
Sirve para indicar a Git qué archivos o carpetas no debe incluir en el repositorio. Por ejemplo, archivos temporales, contraseñas o la carpeta .venv.
3. Explica por qué .venv no debe almacenarse normalmente en GitHub.
Porque .venv contiene todas las dependencias instaladas y puede ocupar mucho espacio. Además, esas dependencias pueden instalarse nuevamente en otra computadora usando requirements.txt.
4. Explica para qué sirve requirements.txt.
Sirve para registrar las librerías y versiones que necesita un proyecto de Python. Así, otra persona puede instalar las mismas dependencias fácilmente.
5. Explica la diferencia entre Stage, Commit y Push.
Stage (git add) → prepara los cambios que se quieren guardar.
Commit (git commit) → guarda esos cambios en el historial local.
Push (git push) → sube los commits al repositorio remoto, como GitHub.
6. Explica por qué un repositorio puede tener varios commits antes de realizar un push.
Porque los commits se guardan localmente y no es necesario subirlos inmediatamente a GitHub. Puedes realizar varios commits mientras trabajas y después hacer un solo git push para subir todos esos commits al repositorio remoto.