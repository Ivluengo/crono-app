# Biblioteca para añadir un cronómetro en tu app

## ¿Cómo usarlo?

1. Añade el script en tu template html antes de ejecutarlo.

```html
<script src="./Crono.js"></script>
```

2. Crea unos maravillosos botones `html` que sirvan para ejecutar las acciones del `Crono()`.
3. Añade un elemento que se encargará de mostrar nuestro segundero.
4. En tu archivo principal `JavaScript` crea una nueva instancia de un `Crono()` y pásale como argumento el elemento que se encargará de mostrar el segundero.

```javascript
const c1 = new Crono(output);
```
5. Los métodos encargados de hacer funcionar el `Crono()` son:
6. 
```javascript
const c1 = new Crono(output);

c1.startCrono(); // Empieza a contar

c1.stopCrono(); // Finaliza el contador

c1.resetCrono(); // Resetea todos los valores a 0
```
7. El `Crono()` se encargará de revisar cualquier posible error.

Enjoy! ⌚😃
