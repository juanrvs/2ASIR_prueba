# 2ASIR_prueba
Prácticas con git y github y creación de **proyectos de typescript**
Hemos instalado node.js y typescript con npm install -g typescript, según la documentación.
Hemos creado el proyecto typescript que nos crea un fichero .json, hemos configurado el .gitignore para que no muestre algo concreto.

Comandos vistos:

git init
git add .
tsc --init
tsc -w
git commit -m "First commit"
git remote -v
git push -u origin master
git remote add origin remote repository URL

¿Cómo creamos o actualizamos nuestro proyecto en github?

    Creamos un nuevo repositorio en GitHub, en nuestro caso se llamará "2ASIR_prueba".
    En el archivo tsconfig.json (creado con el comando tsc --init) debemos cambiar el Outdir y descomentar la línea, añadimos la ruta "./dist".

Iniciamos el directorio local como un repositorio Git con el comando:

    git init

A continuación añadimos los ficheros a nuestro directorio local a través de:

    git add .

Confirmamos los archivos que se han almacenado en el repositorio local con:

    git commit -m "First commit"

Añadimos al siguiente comando la URL de nuestro repositorio de GitHub donde se subiran los archivos locales.

    git remote add origin remote repository URL

Escribimos el siguiente comando:

    git remote -v

Con el siguiente comando los cambios realizados se subiran a nuestro repositorio de GitHub.

    git push -u origin master