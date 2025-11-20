# Master Class Git & GitHub

<!-- For full documentation visit [mkdocs.org](https://www.mkdocs.org). -->

## Comandos de configuraion Git

* Configurar usuario global de git.
```bash
git config --global user.name
``` 
* Configurar correo global de git.
```bash
git config --global user.email
``` 
*  Configurar editor de texto.
```bash
git config --global core.editor
``` 
* Configurar saltos de liena para windows.
```bash
git config --global core.autocrlf true
``` 


## Comandos de Git


| Comando                              | Explicación                                                                                 |
|---------------------------------------|-----------------------------------------------------------------------------------------------------|
| `git status`                         | Muestra el estado actual de los archivos en el repositorio: modificados, listos para guardar, etc.  |
| `git add archivo.txt`                | Prepara el archivo para ser guardado en el próximo commit.                                           |
| `git commit -m "mensaje"`            | Guarda de manera permanente los cambios preparados en el historial local del repositorio.            |
| `git rm archivo.txt`                 | Elimina el archivo y lo marca para ser eliminado en el próximo commit.                               |
| `git restore --staged archivo.txt`   | Quita el archivo del área de stage, pero mantiene los cambios en tu directorio de trabajo.           |
| `git restore archivo.txt`            | Revierte los cambios realizados en el archivo desde la última versión confirmada (commit).           |
| `git mv archivo.txt nuevo_nombre.txt`| Cambia el nombre o mueve un archivo y registra el cambio para el próximo commit.                     |
| `git status -s`                      | Muestra un resumen corto del estado de los archivos en el repositorio.                               |
| `git diff`                           | Muestra las diferencias entre los archivos modificados y la última versión confirmada (commit).      |
| `git diff --staged`                  | Muestra las diferencias entre los archivos en stage y la última versión confirmada (commit).         |
| `git log`                            | Muestra el historial de todos los commits realizados en el repositorio.                              |
| `git log --oneline`                  | Muestra el historial de commits de forma breve, con identificador corto y mensaje.                   |
| `git checkout -b nombre-de-la-rama`                  | Crear una nueva rama y cambiarnos.                  |

        
