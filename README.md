# Triple Espresso
Nombre del proyecto:
web_project_coffeeshop

Descripción del proyecto y su funcionalidad:
Este proyecto se basa en una página de inicio de una cafetería, la cual se divide en varias secciones.

En la primera sección, podemos ver el header, donde se encuentra alojado el logo "Triple Espresso" y un menú que contiene tres ítems conectados con la sección de página correspondiente. Estamos utilizando un hover para que, cuando el cursor pase por encima de ellos, cambien de color. También encontramos el título de la página y una breve descripción.

En esta primera parte podemos ver un header footer que tiene la clase header__footer, donde se muestra el horario y un párrafo con diferencias de estilo, ya que estamos utilizando un color de fuente, un estilo de fuente y un tamaño diferente al resto del contenido.

En la segunda parte de la página de inicio encontramos la sección de recetas, donde hay un título con tamaño h2 y una descripción que utiliza una etiqueta <p>. Se pueden ver dos videos dispuestos de manera horizontal; para lograr esto, utilizamos un diseño flex. Debajo de los videos podemos ver un título con la duración de cada uno; para esto se usó una etiqueta <p> y se posicionó con padding.

En la tercera parte, se encuentra la sección "Reservar una mesa", donde podemos ver un formulario que pide el nombre, número de comensales, fecha, hora y correo. Este formulario está centrado con una etiqueta flex y justify-content: center. También podemos ver el botón de submit, que tiene un diseño especial: cuando pasamos el cursor por encima, se aclara el color azul del botón para que el usuario pueda identificarlo de manera más visual. Por último, en esta sección encontramos un checkbox que solicita aceptar los términos y condiciones de la página. Al marcarlo, se muestra una imagen de un check de color morado.

En la última sección, podemos encontrar el footer o pie de página, donde aparece un círculo que está posicionado de manera particular. Utilizamos una etiqueta CSS de posicionamiento absolute, que nos permitió ubicarlo donde debía ir, y aplicamos un z-index: 0 para que quedara detrás de los demás elementos, ya que parte del círculo sobresale del footer. También podemos ver los iconos de redes sociales, que tienen un efecto hover que cambia a un color más claro cuando el cursor pasa por encima. Además, cada uno cuenta con una etiqueta href, que por el momento no redirecciona a otra parte de la página. Finalmente, tenemos un footer de copyright donde se muestra el año y el nombre de la persona que realizó la página, en este caso, mi nombre.

Descripción de las tecnologías y técnicas utilizadas:

En la estructura del proyecto nos basamos en las reglas de BEM (Block Element Modifier), tanto en la forma y ubicación de los archivos como en la nomenclatura de las clases que se utilizan en el HTML y el CSS.

En el archivo HTML, encontramos una etiqueta que nos indica el idioma utilizado, que en este caso es español. Dentro de la etiqueta <head> se alojan las etiquetas <meta> y los <link> donde vinculamos las hojas de estilo y también las fuentes utilizadas.

Después de esto, encontramos el <body> o cuerpo de la página. Dentro de esta etiqueta se incluye todo el contenido visible en la web, junto con las clases correspondientes que se relacionan con los estilos definidos en los archivos CSS.

En la base principal de la estructura está el <header>. Dentro de este, se encuentra una etiqueta <nav> que contiene el logo y el menú, con etiquetas que llevan las clases correspondientes según las reglas BEM.

También tenemos un <div> con la clase header__footer y otro con la clase header__footer-paragraph. Esto completa la estructura del <header>.
Después, encontramos la etiqueta <main>, que contiene la información principal de la página. Dentro de esta, en la primera parte, se encuentra la sección con la clase recipes, donde también está la etiqueta <iframe> que contiene los videos con los enlaces de YouTube.

Después de esto, encontramos la segunda parte, que corresponde a un formulario dentro de una etiqueta <form>. Cabe destacar que estamos utilizando la metodología BEM, por lo que todas las clases están organizadas siguiendo esta estructura.

En el archivo CSS principal ocurre algo particular: únicamente contiene ocho líneas de código, pero en ellas se utiliza @import, que nos direcciona a las hojas donde se encuentran los estilos predeterminados. Estos archivos CSS también están organizados bajo la metodología BEM.

Si quieres, puedo ayudarte a redactar la siguiente parte, a unir todo en un texto completo o a hacerlo más formal y profesional.



