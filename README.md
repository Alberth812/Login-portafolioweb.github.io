# Login-portafolioweb.github.io
Portafolio web con login 

![image](https://github.com/user-attachments/assets/8ca8cf22-a3d1-4563-8849-7911dfdc554a)

Para el siguiente trabajo de programacion web elaboramos un portafolio web a partir de una plantilla, sin embargo debiamos complementar elementos y crear nuevos con los conocimientos previamente adquiridos en trabajos anteriores y lo aprendido en clase.




Descripcion de proyecto:

El proyecto es un portafolio web personal con un sistema de inicio de sesión. Incluye una página principal de login (Login.html) donde los usuarios pueden iniciar sesión o registrarse, asl iniciar sesion nos redirecciona a la pagina (index.html) que muestra información sobre mi, habilidades, proyectos y un formulario de contacto. El diseño utiliza Bootstrap para la apariencia responsiva y moderna, e integra imágenes y logos almacenados en la carpeta assets/img/.



Menús que la componen

portafolio.html: El menú de navegación principal incluye:

Inicio

Sobre mí

Proyectos

Contacto

Login.html: solo es un formulario de login/registro.



Plantilla utilizada:

El proyecto utiliza la plantilla "Start Bootstrap Grayscale" para la página principal (index.html), que es un tema moderno y responsivo basado en Bootstrap.
Para el login, se usa Bootstrap 5 y estilos personalizados, pero no una plantilla específica de login, sino un diseño propio con Bootstrap.

enlace de descarga de la plantilla utilizada:  https://startbootstrap.com/theme/grayscale




Descripción de cada sección

portafolio.html

Menú de navegación: Barra superior fija con enlaces a las secciones principales.


Masthead: Encabezado con título y subtítulo de bienvenida.

Sobre mí: Tarjeta con foto de perfil, nombre, escolaridad, pasatiempos y una breve descripción personal.

Habilidades: Sección con íconos y nombres de lenguajes de programación, bases de datos y herramientas de diseño.

Proyectos: Galería de proyectos con imágenes y descripciones breves.

Contacto: Formulario para enviar un correo electrónico y tarjetas con dirección, correo y teléfono.

Redes sociales: Íconos con enlaces a Twitter, Facebook y GitHub.

Footer: Pie de página con derechos reservados.




Estructura del portafolio (portafolio.html)

Navbar: Barra de navegación fija arriba, con enlaces a secciones internas (Inicio, Sobre mí, Proyectos, Contacto).

Masthead: Encabezado grande con título, subtítulo y botón de inicio.

Sección "Sobre mí": Tarjeta con foto, nombre, escolaridad, pasatiempos y descripción personal.

Sección "Habilidades": Listado de lenguajes de programación, bases de datos y herramientas de diseño, cada uno con su ícono y nombre.

Sección "Proyectos": Tres proyectos destacados, cada uno con imagen, título y descripción:

Login (sistema de inicio de sesión)

3D (figuras con OpenGL)

Render (modelado y renderizado en Blender)

Sección "Contacto": Formulario para enviar correo, con validación y mensajes de éxito/error.

Sección "Dirección, Correo, Teléfono": Tarjetas con información de contacto y enlaces a redes sociales.

Footer: Pie de página con derechos reservados.



Implementación de su JavaScript

Validación del formulario de contacto:

Al enviar el formulario, revisa si el correo contiene un @.

Si no es válido, muestra mensaje de error.

Si es válido, muestra mensaje de éxito y limpia el formulario.



Librerías externas:

Bootstrap para componentes y responsividad.

Font Awesome para íconos.

SB Forms para manejo avanzado de formularios (comentado, requiere activación).




Implementación de su CSS

Archivo principal:

Usa styles1.css (no styles.css), que probablemente contiene estilos personalizados y los de Bootstrap.

Estilos esperados:

Colores de fondo claros y oscuros para secciones alternas.

Tarjetas con bordes redondeados y sombras.

Imágenes responsivas (img-fluid).

Tipografía personalizada (Google Fonts).

Botones y campos de formulario estilizados con Bootstrap.

Secciones bien separadas y centradas, con márgenes y paddings adecuados.

Íconos grandes y coloridos para habilidades y contacto.



Metodos de validacion de correo:

Correo electrónico:

El input tiene type="email" y required, lo que valida que el usuario escriba un correo válido y que el campo no esté vacío.
Además, hay mensajes personalizados de error usando Bootstrap (data-sb-validations="required,email" y mensajes en <div class="invalid-feedback">).
En el script personalizado, también se valida que el correo contenga un @ antes de mostrar el mensaje de éxito.





Capturas de previsualizacion:

portafolio.html (Portafolio)
![image](https://github.com/user-attachments/assets/16db69ee-645f-4d60-8955-5299aa5be8ba)
![image](https://github.com/user-attachments/assets/ef7d7e05-f577-4b20-bd91-2714c119a392)
![image](https://github.com/user-attachments/assets/57828a5c-25b1-4bca-9889-e136ad4b67fd)
![image](https://github.com/user-attachments/assets/224c3bfd-1944-43b8-ae8e-bb411d652115)
