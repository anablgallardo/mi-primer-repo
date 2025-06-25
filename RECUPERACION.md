# Recuperación del archivo errores.sh

## Error simulado
He simulado borrar el archivo `errores.sh` después de haberlo subido al repositorio.

## Comandos utilizados para la recuperación
- ***git reflog***: para ver un registro de todas las operaciones realizadas recientemente en el repositorio y buscar el commit donde se añadió el archivo.
- ***git checkout efef918 -- errores.sh***: para recuperar el archivo de ese commit.

## Que he aprendido
He aprendido que Git guarda toda la información sobre las operaciones que hacemos a nuestros repositorios, y si cometemos el error de borrar algo, podemos recuperarlo con los comandos git `reflog` y `git checkout`.

