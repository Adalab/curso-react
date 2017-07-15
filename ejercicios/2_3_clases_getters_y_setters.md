# Clases: Getters y setters

## Descripción del ejercicio

Este ejercicio es una continuación de los ejercicios [ 1](2_1_clases_uso_basico) y [2](2_2_clases_herencia) de esta sesión. Para poder realizarlo es necesario terminar estos antes.

Vamos a crear un setter para el contenido del botón llamado `label`, que además de actualizar el texto del botón llame al método `render` para que se pinte automáticamente. La idea es que, en vez de cambiar la propiedad `text` de nuestros botones, utilicemos este setter para cambiar el texto de nuestro botón de la siguiente manera:

```js
const favButton = new Button('.fav-button', 'Marcar como favorito', 'star');

button.label = 'Fav';
```

## Enlaces

- [Solución](http://jsbin.com/xixaguyona/1/edit?html,js,output)
