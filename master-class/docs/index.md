# Master Class Git & GitHub

<!-- For full documentation visit [mkdocs.org](https://www.mkdocs.org). -->

## Comandos de configuraion Git

* `git config --global user.name` - Configurar usuario global de git.
* `git config --global user.email` - Configurar correo global de git.
* `git config --global core.editor` - Configurar editor de texto.
* `git config --global core.autocrlf true` - Configurar saltos de liena para windows.

## Comandos de Git

* `git init` - Iniciar un repositorio de Git.
* `git status` - Ver estatus actual del repositorio.
* `git add archivo.txt` - Agregar archivo al area de Stage (Cambiar "Archivo.txt" por el nombre de tu archivo).
* `git commit -m "mensaje"` - Agregar cambios al repositorio local.
* `git rm archivo.txt` - Eliminar archivo.
* `git restore --stage` - Sacar cambios del area de Stage.
* `git restore` - Descartar cambios en el directorio.
* `git mv archivo.txt nuevo_nombre.txt` - Cambiar nombre de archivo (Cambiar "archivo.txt" por el nombre de tu archivo y "nuevo_nombre.txt" por el nombre que desas asignar).
* `git status -s` - Resumen del estatus del repositorio.
* `git diff` - Ver los cambios realizados en los archivos.
* `git dig --stage` - Ver los cambios realizados en los archivos en el area de Stage.
* `git log` - Ver historial de cambios en el repositorio.
* `git log --online` - Ver historial de cambios de manera resumida.


## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
