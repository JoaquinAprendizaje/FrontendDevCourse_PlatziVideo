## 13 - Anatomía de una declaración CSS: Selectores, Propiedades y Valores
------------------------------------------------------------------
Nuestros estilos con CSS se componen de:

*   **Selector**: son la referencia a los elementos HTML que queremos estilizar. Los nombres de estas etiquetas van seguidas de una llave de apertura y otra de cierre (**`{}`**). Por ejemplo: **`h1 {}`**.
*   **Propiedades**: son el tipo de estilo que queremos darle a nuestros elementos. Van seguidas de dos puntos (**`:`**). Las propiedades deben estar dentro de las llaves del selector que definimos anteriormente. Podemos escribir diferentes propiedades en un mismo selector. Por ejemplo: **`h1 { color: }`**.
*   **Valores**: son el estilo que queremos que tomen nuestros elementos HTML con respecto a una propiedad. Van seguidas de un punto y coma (**`;`**). Por ejemplo: **`h1 { color: red; }`**.
`

    h1 {
      color: red;
    }
`

## 14 - Tipos de selectores, pseudo-clases y pseudo-elementos
-----------------------------------------------------

\***(asterisco)**: Es el selector universal. Las propiedades se aplicaran a todos los elementos de nuestro HTML.

**Tipo**: Son selectores que se aplican a cierto elemento HTML en específico. Las propiedades se aplicaran a la etiqueta que queremos, por ejemplo `p`, `body`, `html`, `div`, etc.

**Clase**: Si nuestras etiqueta de HTML tienen un atributo de `class` podemos usar ese valor o identificador para que los cambios en el CSS afecten únicamente a ese elemento.

**ID**: Es similar al anterior, si la etiqueta HTML tiene un ID podemos afectar solo ese elemento.

Las **Pseudo-clases** y **Pseudo-elementos** nos permiten ser aún más específicos con qué elemento o partes de nuestros elementos deben recibir los estilos.

Para usarlas debemos definir el selector base (por ejemplo, **`p`**) seguido de dos puntos y la pseudo-clase que queremos estilizar (por ejemplo: **`p:first-child`**). En el caso de los pseudo-elementos debemos usar el dos puntos 2 veces (**`p::first-letter`**).

    /* Asterisco (universal) */
    * {
      margin: 0;
    }
    
    /* Tipo */
    h1 {
      color: red;
    }
    
    /* Clase */
    .saludo {
      font-size: 2em;
    }
    
    /* ID */
    #id {
      border-radius: 20px;
    }
    
    /* Pseudo-clases */
    p:first-child {
      color: white;
    }
    
    p:last-child {
      color: purple;
    }
    
    p:nth-child(2n) {
      color: red;
    }