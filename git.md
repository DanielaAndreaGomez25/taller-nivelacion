# Introducción a Markdown

Markdown es un lenguaje de marcado ligero que permite dar formato a texto plano de manera sencilla. 
Se utiliza principalmente en GitHub para documentar proyectos.



* GIT

 1. ¿Qué es un repositorio en Git?

Un repositorio es un espacio donde Git almacena los archivos de un proyecto y su historial de cambios. 
A diferencia de un proyecto normal, permite guardar versiones y trabajar en equipo.

 2. Áreas principales de Git

- Working Directory: donde se editan los archivos.
- Staging Area: donde se preparan los cambios antes del commit.
- Repository: donde se almacenan los commits definitivos.

 3. ¿Cómo representa Git los cambios?

Git utiliza:
- Blob: contenido de archivos.
- Tree: estructura de carpetas.
- Commit: registro de cambios.
- Tag: referencia a un commit específico.

 4. ¿Qué es un commit?

Es un registro que guarda los cambios realizados en el proyecto, incluyendo autor, fecha y mensaje.

 5. Diferencia entre git pull y git fetch

- git fetch descarga cambios sin fusionarlos.
- git pull descarga y fusiona automáticamente.

6. ¿Qué es un branch?

Es una rama independiente de desarrollo que permite trabajar en cambios sin afectar la versión principal.

 7. ¿Cómo se realiza un merge?

Se usa git merge. Si dos personas modifican la misma línea, pueden surgir conflictos que se deben resolver manualmente.

 8. ¿Qué hace git add?

Agrega archivos al área de preparación (staging). Si se omite, no se incluirán en el commit.

 9. ¿Qué es .gitignore?

Es un archivo que indica qué archivos no deben ser rastreados por Git.

 10. ¿Qué hace --amend?

Permite modificar el último commit realizado.

 11. ¿Qué es git stash?

Permite guardar cambios temporales sin hacer commit.

 12. ¿Cómo deshacer cambios?

- git reset
- git revert
- git checkout

13. ¿Qué es origin y upstream?

Origin es el repositorio remoto principal.  
Upstream se usa cuando se trabaja con forks.

14. ¿Cómo inspeccionar el historial?

- git log
- git diff
- git show
