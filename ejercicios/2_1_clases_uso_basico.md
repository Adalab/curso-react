# Clases: Uso básico

## Descripción del ejercicio

El objetivo de este ejercicio es crear una clase que podamos reutilizar en múltiples ocasiones para crear botones con distintas características.

Esta clase, además, deberá tener un método `render` que al ejecutarse añada el texto y el icono al botón.

Para crear la clase le pasaremos tres parámetros:
- Un selector HTML
- El texto que tendrá el botón
- El nombre de un icono de [Font Awesome](http://fontawesome.io/icons/)

La idea final sería tener un botón en nuestro html (ej: `<button class="btn"></button>`) y, mediante el siguiente código, hacer que ese botón tenga un texto y un icono:

```js
var button = new Button('.btn', 'Pulsame', 'stats');
button.render();

```

Probaremos a crear dos botonos distintos en el HTML y el respectivo código JavaScript para ambos. De esta forma comprobaremos que nuestro código funciona de forma diferente cuando le pasamos parámetros diferentes a la hora de crear las instancias.

**Nota:** La palabra render significa mostrar una imágen dentro de una vista y es un término muy común en el ámbito de la informática. En el caso de este ejercicio, el método `render` hace referencia a que se pinta el botón, de ahí el nombre.

### Bonus

Ejecutar el método `render` cada vez que creamos un botón es algo muy repetitivo, sería mejor que este método se ejecutase al crear cada botón. Como parte bonus de este ejercicio, haremos que el botón se renderice directamente al ser creado.

## Pistas

Para usar los iconos de Font Awesome debemos llevar a cabo dos pasos:

1. Primero deberemos enlazar el CSS del archivo de Font Awesome, cómo hemos hecho hasta ahora con las fuentes de Google Fonts. La ruta de Font Awesome es la siguiente: `https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css`
2. Después deberemos introducir el código HTML necesario para poder usar el icono. Veréis el código de cada icono en la página de cada uno de ellos. Por ejemplo, [aquí](http://fontawesome.io/icon/star/) tenéis la página del icono para la estrella. Podéis buscar otros iconos en el [listado de iconos de Font Awesome](http://fontawesome.io/icons/)

## Enlaces

- [Código inicial en JSBin](http://jsbin.com/huyofozeje/edit?html,js,output)
- [Solución](http://jsbin.com/wejinapivi/1/edit?html,js,output)
- [Solución (Bonus)](http://jsbin.com/qezatakufi/edit?html,js,output)
