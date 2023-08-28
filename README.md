# P0
Práctica 0: Subir archivos a github

1. Creé una carpeta en local llamada "P0".

2. Creé un repositorio en github que está en https://github.com/AnxoMV/P0.git y lo conecté mediante el siguiente comando:

git clone https://github.com/AnxoMV/P0.git

3. Hice un archivo llamada "Hola Mundo.txt"
    a. Lo añadir al staging con: git add .
    b. Hice el commit: git commit -m "Añadido mi primer archivo al staging"
    c. Subí los cambios: git push

4.
    a. Creación de la rama: git branch development
    b. Me moví a la rama: git checkout development
    c. Añadí cambios al archivo "Hola Mundo.txt"
    4. Los subí al staging con: git add .
    5. Hice el commit: git commit -a -m "Añadiendo cambios a development"
    6. Lo subí: push origin development

5.  Hago el merge de la rama principal con development:
    a. git merge development
    b. Lo subo: push

6. Modifico el archivo de Readme.md
    a. 