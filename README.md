feature_grupo
# retro_read_me

  

En esta actividad vamos a hacer una pequeña retroalimentación de git, donde se hace el paso a paso de como crear un proyecto en git, usando sus diferentes comandos, donde usamos comandos como: "git add , git checkout", entre otros.

  

## 1. Archivos

  
```
 retro_read_me

-- index.html

-- Readme.md
```
  

## 2. Inicializar repositorio con Git

  

```bash

git  init

```

  

## 3. Conectar con repositorio remoto (GitHub)

  

Primero se crea el repositorio en GitHub llamado `retro_read_me`, luego se ejecuta:

  

```bash

git  remote  add  origin  https://github.com/Estebantupapa/retro_read_me.git

```



  

## 4. Crear ramas

  

```bash

git  checkout  -b  main

git  checkout  -b  feature-index

```

  

## 5. Hacer cambios y commits
 

```

git  add  index.html

git  commit  -m  "Se agregó contenido básico a index.html"

```

  

Volver a `main`, fusionar y hacer push:

  

```bash

git  checkout  main

git  merge  feature-index

git  push  -u  origin  main

git  push  -u  origin  feature-index

```

  

## Confirmaciones realizadas

  

- Repositorio tiene dos ramas: `main` y `feature-index`.

- Se han realizado al menos dos commits.

- El archivo `index.html` tiene contenido HTML vacio por el momento.

- Este `README.md` contiene toda la documentación paso a paso.

 main
