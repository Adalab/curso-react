# Mostrar evoluciones de Pokemon

## Requisitos

Para realizar este ejercicio crearemos el código desde Atom y comprobaremos que funciona correctamente usando la última versión de Chrome (59).

Este ejercicio es una continuación del [ejercicio 1](6_1_lista_api_pokemons.md) de esta sesión. Para poder realizarlo es necesario realizar ese ejercicio previamente.

## Descripción del ejercicio

Sobre el listado que hemos generado en el ejercicio anterior vamos a mostrar si el pokemon es una evolución de otro.

En la información de un pokemon encontraremos una URL con más información sobre su especie donde podremos encontrarlo.

Tendremos que realizar esta petición de la petición inicial al servidor, así que tendremos que encadenar promesas y hacer dos peticiones distintas con el `fetch`.

## Recursos

- [API de Pokemon](https://pokeapi.co/). Tiene un límite de peticiones por día, si se sobrepasa, deja de funcionar y parece que no devuelve nada, pero es porque el servidor prohibe la conexión a la IP que estés utilizando en ese momento.
- [Repositorio con archivos JSON de los pokemon](github.com/adalab/pokemon-data). Hemos creado este repositorio para poder trabajar con un JSON como si se tratase de la API de Pokemon y no nos corte el acceso a los datos. Para solicitar un archivo tendremos que ir a la ruta `https://github.com/Adalab/pokemon-data/raw/master/<nombreDelArchivo>`, donde `nombreDelArchivo` será el nombre del archivo que queramos solicitar. Un ejemplo: [https://github.com/Adalab/pokemon-data/raw/master/1.json](https://raw.githubusercontent.com/Adalab/pokemon-data/master/1.json). **Nota:** En ese repositorio sólo está la información de los pokemons del 1 al 3.
