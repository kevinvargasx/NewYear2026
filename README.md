# Un clic, un nuevo comienzo

Este es un proyecto sencillo en HTML, CSS y JavaScript que simula una animación de Año Nuevo. Al hacer clic en la pantalla inicial, la página muestra un mensaje de bienvenida con una interfaz visual festiva. El fondo cambia a un amanecer y se despliegan tarjetas motivacionales que alientan al usuario a reflexionar sobre lo que desea para el nuevo año.

## Funcionalidades

- **Pantalla de inicio**: Muestra el año "2026" y un mensaje que invita a hacer clic para comenzar el nuevo año.
- **Animación de estrellas**: Aparecen estrellas parpadeando aleatoriamente en el fondo, creando un ambiente nocturno.
- **Transición al amanecer**: Después de hacer clic, el fondo de la página cambia a un amanecer, con colores cálidos y brillantes.
- **Tarjetas motivacionales**: Tres tarjetas aparecen con mensajes inspiradores: "Renovar", "Soñar" y "Crecer".
- **Formulario de cierre**: El usuario puede escribir sus deseos para el año en un campo de texto al final de la página.

## Estructura de Archivos

El proyecto consta de un solo archivo HTML que incluye:
- **HTML**: La estructura del contenido, incluyendo las pantallas iniciales y finales.
- **CSS**: Estilos para la página, incluyendo la animación de las estrellas, el fondo dinámico, y las transiciones de los elementos.
- **JavaScript**: Funciones para iniciar la animación, cambiar el fondo y mostrar el contenido motivacional.

## Detalles del Código

### HTML
- El archivo contiene una estructura básica de página con etiquetas `<div>`, `<h1>`, `<p>`, y `<input>`.
- El contenido principal está envuelto en un `div` con clase `.pantalla`, que contiene el texto inicial y los elementos interactivos.

### CSS
- Se utiliza la fuente **Poppins** desde Google Fonts.
- La animación de las estrellas y el cambio de fondo están definidos en las reglas de estilo.
- Se aplican transiciones de suavizado a varios elementos, como el fondo de la página y los elementos de las tarjetas.

### JavaScript
- El script genera 80 estrellas que se posicionan aleatoriamente en la pantalla y parpadean.
- La función `iniciar()` es llamada al hacer clic en la pantalla inicial, ocultando la pantalla de inicio y mostrando el contenido del nuevo año.

## Requisitos

Este proyecto no tiene dependencias externas, solo requiere un navegador web moderno que soporte HTML5, CSS3 y JavaScript.

## Cómo usar

1. Descarga el archivo HTML y ábrelo en tu navegador.
2. Haz clic en la pantalla que muestra "2026" para iniciar la animación y ver el contenido.
3. Escribe tus deseos para el nuevo año en el campo de texto al final.

## Personalización

- Puedes cambiar el año en el `div` con la clase `.anio` para personalizar el mensaje.
- También puedes modificar los colores del fondo cambiando las propiedades `background` en el CSS.
- Las tarjetas y los mensajes pueden ser fácilmente modificados en el código HTML.

## Licencia

Este proyecto es de código abierto, puedes modificarlo y usarlo libremente.

