# da-promo-47-lesson-git
Leccion de Git de la promo 47

## Motivos por cuales no puedo subir a GIt

1. No estoy en la ruta del repositorio en la terminal
```bash
fatal: not a git repository (or any of the parent directories): .git
```

Soluciones: 
- Verificar que estoy en la ruta correcta: estoy en un repositorio de git teniendo la carpeta oculta .git
- En la terminal estoy posicionado en la carpeta del repositorio
  

2. Asegurarme de haber ejecutado los tres git: 

Si me olvido de alguno de los tres git, y me sale este mensaje: 

```bash
Everything up-to-date
```
Solución: Ejecutar los tres git: 

```bash
git add -A
git commit -m "mensaje"
git push
```

3. Que pasa cuando hay conflictos

Significa que hay cambios en el repositorio remoto que no tengo en mi repositorio local.

```bash
error: failed to push some refs to 'https://github.com/Adalab/da-promo-47-lesson-git.git'
``

Solución:

```bash

git pull
```


