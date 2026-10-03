# Cuenta bancaria — Git y pull requests

**Autor:** Martin Gonzalez Rico

## Cómo correr

    ./correr.sh

## Mis pull requests

| # | Qué cambió |
|---|---|
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   Respuesta:`git add` prepara los cambios para guardarlos en el próximo commit. `git commit` guarda esos cambios en el historial de Git.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   Respuesta:Porque el merge se hizo en el repositorio remoto (GitHub), pero mi `main` local todavía no tenía esos cambios. `git pull` descargó y aplicó los cambios del repositorio remoto.

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   Respuesta:El nuevo commit se agregó automáticamente al mismo PR, porque el PR está asociado a esa rama.

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   Respuesta: Para proteger la rama principal y evitar cambios que puedan romper el proyecto. Normalmente se trabaja en ramas y se revisan los cambios mediante un Pull Request antes de hacer merge.

## En este repositorio se encuentra las cuestionarios de capitulo 3 y 4 .
