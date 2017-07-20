# Lista con API de pokemons

## Requisitos

Para realizar este ejercicio crearemos el código desde Atom y comprobaremos que funciona correctamente usando la última versión de Chrome (59).

## Descripción del ejercicio

Vamos a crear un listado de pokemon utilizando este API, para mostrar información sobre

- Id (1, 2, 3...)
- Nombre
- Tipo (puede ser múltiple, pero máximo serán 2)
- Imagen

## Recursos

- [API de Pokemon](https://pokeapi.co/). Tiene un límite de peticiones por día, si se sobrepasa, deja de funcionar y parece que no devuelve nada, pero es porque el servidor prohibe la conexión a la IP que estés utilizando en ese momento.
- [Repositorio con archivos JSON de los pokemon](github.com/adalab/pokemon-data). Hemos creado este repositorio para poder trabajar con un JSON como si se tratase de la API de Pokemon y no nos corte el acceso a los datos. Para solicitar un archivo tendremos que ir a la ruta `https://github.com/Adalab/pokemon-data/raw/master/<nombreDelArchivo>`, donde `nombreDelArchivo` será el nombre del archivo que queramos solicitar. Un ejemplo: [https://github.com/Adalab/pokemon-data/raw/master/1.json](https://raw.githubusercontent.com/Adalab/pokemon-data/master/1.json). **Nota:** En ese repositorio sólo está la información de los pokemons del 1 al 3.
