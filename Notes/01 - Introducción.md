## 01 - Qué son y para qué nos sirven HTML y CSS
-------------------------------------------------------------

**HTML**: Es un lenguaje de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.

**CSS**: Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.

## 02 - DOM, CSSOM, Render Tree y el proceso de renderizado de la Web
-------------------------------------------------------------
**DOM**: Document Object Model. Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.

**CSSOM**: así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.

**Render Tree**: es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.

Pasos que sigue el navegador para construir las páginas web:

1.  Procesa el HTML para construir el DOM.
2.  Procesa el CSS para construir el CSSOM.
3.  El DOM se une con el CSSOM para crear el Render Tree.
4.  Se aplican los estilos CSS en el Render Tree.
5.  Se “_pintan_” los nodos en la pantalla para que los usuarios vean el contenido de la página web.

