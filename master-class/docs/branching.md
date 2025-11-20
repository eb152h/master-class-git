# Ramas o Branches

**¿Qué es una rama en Git?**

Imagina que tu proyecto es un árbol.
La rama principal (llamada por lo general main o master) es el tronco.
Cuando quieres trabajar en una nueva funcionalidad, corregir un error o hacer pruebas sin afectar el trabajo principal, puedes crear una rama (branch).
Cada rama es como una “rama” nueva que crece a partir del tronco.
Esto te permite experimentar sin miedo: si algo sale mal, no afecta al resto del árbol.

**¿Para qué sirven las ramas?**

-   Desarrollar nuevas características sin interrumpir el trabajo de otros.
-   Corregir errores de forma aislada antes de unir los cambios al proyecto principal.
-   Probar ideas o experimentos, sin riesgo para la versión estable.
-   Colaborar en equipo: cada persona puede trabajar en su propia rama.

![Gitflow - Ramas en git](images/ramas.png)

## ¿Como trabajar con ramas?

1. **Crear rama.**
```bash
git branch nombre-de-la-rama
```

2. **Movernos a la rama creada.**
```bash
git checkout nombre-de-la-rama
```

3. **Mover los archivos al area de stage.**
```bash
git add archivo.txt
```

4. **Mover los archivos al repositorio local**
```bash
git commit -m "Modificando archivo.txt"
```

5. **Es necesario movernos a la rama main para poder fusionar las ramas.**
```bash
git checkout main
```

6. **Traer los cambios de la rama creada a main.**
```bash
git merge nombre-de-la-rama
```

## Crear nueva rama en el repositorio remoto

1. **Seguir los pasos del 1 al 4 de la seccion ¿Como trabajar con ramas?**

2. **Hacer push al repositorio origen**
```bash
git push -u origin nueva-rama
```

