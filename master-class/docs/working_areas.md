# Areas de trabajo de Git

1. **Working Directory (Directorio de Trabajo)**
    - Es la carpeta en tu computadora donde editas, creas o eliminas archivos. Aquí es donde ocurre el trabajo diario. Todo lo que ves y modificas directamente está en el working directory.

2. **Staging Area (Área de Preparación)**
    - Es una especie de espacio intermedio. Aquí decides qué cambios quieres incluir en tu próximo “commit”. Cuando usas git add, mueves archivos del directorio de trabajo a la staging area.

3. **Repository (Repositorio Local)**
    - Es la base de datos interna de Git, donde se guardan de manera permanente todos los cambios confirmados (“commits”). Cuando usas git commit, los archivos que están en la staging area pasan al repositorio local.

4. **Repositorio Remoto**
    - Es un repositorio que está en un servidor externo (por ejemplo, GitHub, GitLab, Bitbucket), y se utiliza para compartir tu trabajo y colaborar con otros. Usas git push para subir tus cambios al repositorio remoto y git pull o git fetch para descargar cambios de otros.

![Areas de trabajo](images/working_areas.png)
