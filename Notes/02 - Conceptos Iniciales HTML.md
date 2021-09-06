## 03 - Anatomía de un Elemento HTML: Atributos, Anidamiento y Elementos vacíos
-----------------------------------------------------------------------
Nuestros elementos HTML se componen de:

*   **Etiqueta de apertura**: el nombre de nuestra etiqueta encerrado entre símbolos de mayor o menor. Por ejemplo: **`<h1>`**.
*   **Contenido**: dentro de nuestras etiquetas podemos añadir texto u otros elementos HTML, lo que conocemos como **anidamiento**.
*   **Etiqueta de cierre**: son casi iguales que las etiquetas de apertura, pero también necesitan un slash (**`/`**) antes del nombre de la etiqueta. Por ejemplo: **`</h1>`**.

Las etiquetas de apertura también pueden tener atributos. Los atributos nos permiten definir características especiales para nuestros elementos: **`<etiqueta atributo=""valor del atributo"">`**. Por ejemplo: **`<h1 class=""saludo"">`**.

También existen elementos vacíos. Estos elementos no tienen contenido ni etiqueta de cierre, solo etiqueta de apertura y atributos. Por ejemplo: **`<img src=""puppy.png"" alt=""mi mascota"">`**.


## 09 - La importancia del código semántico
-----------------------------------
La semántica HTML no es más que darle sentido y estructura a lo que estas escribiendo. Muy importante para el navegador. No todos los elementos deberían ser un div.


- El código que escribe un desarrollador esta hecho para que lo lean otros humanos.
- HTML semántico nos permite darle mayor accesibilidad a la página, ya que permite que los Screen Readers puedan desplazarse de mejor manera a través de la página.
- También por posicionamiento (SEO) es importante utilizar HTML semántico.
	- Por ejemplo la etiqueta `<em>` a diferencia de `<i>` indica a los bots de Google que el texto marcado es relevante.

## 10 - Tipos de errores en HTML, debugging y servicio de validación de etiquetas
-------------------------------------------------------------------------
**Errores sintácticos**: Son errores de escritura en el código y evitan que el programa funcione. Pueden ser errores de tipado.

**Errores lógicos**: En estos la sintaxis es correcta, pero el código no hace lo que debería. El programa funciona, pero de forma incorrecta.Tipos de errores en HTML, debugging y servicio de validación de etiquetas.

**Debugging**: Proceso de encontrar y corregir errores del código.

### LINK para validar nuestro HTML.

[https://validator.w3.org](https://platzi.com/clases/1640-frontend-developer-2019/21880-tipos-de-errores-en-html-debugging-y-servicio-de-v/url)