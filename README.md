



## 1. Preparación del entorno
- Hacemos fork del repositorio que nos has dado (https://github.com/damiancastelao/ExamenCOD)
- Clonar el repositorio
- Traer todas las ramas del remoto


## 2. Creacion Rama Readme

Despues de clonar el repositorio, creo la rama Readme con el Readme.md

## 3. Problema en la rama interface

Al revisar la rama `interface` se ve que el último commit no debería incluirse en la versión final.

En vez de modificar la rama original, se ha creado una nueva rama desde el último commit correcto para evitar problemas.

Se crea la rama `interface-clean` y se usa esa para la integración en `main`.



### 4.Creacion de la Rama Limpia

- Se crea una nueva rama desde el último commit válido.
- Se evita modificar la rama original

### 5. Merge de la rama limpia a main

- Se realiza la integración de la rama interface_limpia en main.
- Esta rama contiene la versión corregida sin el último commit erróneo de interface.


### 6. TAG DE VERSION

Creación del tag


`git checkout main`
`git tag v1.0`
`git push origin v1.0`

Se marca el commit final como versión estable v1.0
Permite crear la release en GitHub a partir de esta versión
