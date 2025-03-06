Este trabajo es de Marin Salazar Juan Sebastian

Las preguntas son del 2 al 6 pero como quite el uno, aqui aparecen como del 1 al 5.

1.- Qué hace document.querySelector(".display");?
Este código busca en el documento HTML un elemento con la clase .display y lo selecciona.
Funciona asi: 
document hace referencia al documento HTML.
querySelector(".display") selecciona el primer elemento que tenga la clase "display".
Se usa para acceder al display de la calculadora, donde se muestran los números y resultados.

2.- ¿Qué hace const buttons = document.querySelectorAll("button");?
Este código selecciona todos los elementos <button> en el HTML y los guarda en una NodeList (una lista similar a un array).
Funciona asi: 
querySelectorAll("button") selecciona todos los botones del documento.
const buttons almacena la lista de botones.
Se usa para agregar eventos a cada botón de la calculadora.

3.- ¿Qué hace buttonText = button.textContent;?
Esta línea obtiene el texto dentro del botón que se ha presionado.
Funciona asi: 
button.textContent accede al contenido de texto dentro del botón.
Se usa para saber qué número u operación fue presionada.

4.- ¿Qué hace y cómo funciona buttons.forEach((button) => { ... }?\n
Este código recorre todos los botones de la calculadora y ejecuta una función en cada uno.
Funciona asi: 
buttons.forEach(...) itera sobre cada botón en la lista de botones.
button representa cada botón individual en cada iteración.
Se usa para agregar eventos a cada botón de la calculadora.

5.- ¿Qué hace y cómo funciona button.addEventListener("click", () => { } )?
Este código detecta cuando un botón es presionado y ejecuta una función en respuesta.
Funciona asi: 
addEventListener("click", () => { }) espera a que el usuario haga clic en el botón.
Cuando el usuario hace clic, la función dentro del { } se ejecuta.


