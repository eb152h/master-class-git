# Clase de Git y GitHub

## Crear repositorio en GitHub

1. Ingresar a  [GitHub](https://www.github.com){target="_blank"}

2. Dar click en el icono de `Perfil` y posterior click en `Repositorios`
![Ver repositorios](images/ver-repositorios.png)

3. Dar click en el boton `New`
![Nuevo repositorio](images/nuevo-repositorio.png)

4. LLenar los datos del repositorio.
    -   Nombre de repositorio.
    -   Descripcion
    -   En `Configuracion` puedes indicar si quieres que el repositorio sea `Publico` o `Privado`

![Datos de nuevo repositorio](images/datos-crear-repositorio.png)

## Clonar repositorio

1. Crear una carpeta en para clonar el repositorio, damos click derecho sobre la carpeta creada y seleccionarmos `Open Git Bash here`.
![Abrir Git Bash](images/abrir-git-bash.png)

2. Al ingresar a nuestro repositorio desde GitHub, en el apartado de `Configuracion rapida` podemos copiar la URL para poder clonarlo.
![Copar URL de repositorio](images/copiar-url-repositorio.png)

3. Desde Git Bash escribimos el comando `git clones url` para descargar (Clonar) el repositorio desde Git Hub.
```bash
git clone https://github/usuario/repositorio.git
```

## Areas de trabajo de Git

```plaintext
[Working Directory] --(git add)--> [Staging Area] --(git commit)--> [Local Repository] --(git push)--> [Remote Repository]
```

1. Working Directory (Directorio de Trabajo)
    - Es la carpeta en tu computadora donde editas, creas o eliminas archivos. Aquí es donde ocurre el trabajo diario. Todo lo que ves y modificas directamente está en el working directory.

2. Staging Area (Área de Preparación)
    - Es una especie de espacio intermedio. Aquí decides qué cambios quieres incluir en tu próximo “commit”. Cuando usas git add, mueves archivos del directorio de trabajo a la staging area.

3. Repository (Repositorio Local)
    - Es la base de datos interna de Git, donde se guardan de manera permanente todos los cambios confirmados (“commits”). Cuando usas git commit, los archivos que están en la staging area pasan al repositorio local.

4. Repositorio Remoto
    - Es un repositorio que está en un servidor externo (por ejemplo, GitHub, GitLab, Bitbucket), y se utiliza para compartir tu trabajo y colaborar con otros. Usas git push para subir tus cambios al repositorio remoto y git pull o git fetch para descargar cambios de otros.

