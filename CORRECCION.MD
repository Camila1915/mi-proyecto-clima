Corrección de malas prácticas
1. No se incluyo el archivo index.css en el <head>
Problema:
El HTML no tenoa el enlace al archivo de estilos index.css, asi que la página se veia sin diseño (solo texto plano).

Por qué es una mala práctica:
-La web pierde su apariencia visual (colores, diseño, etc.).
-Puede dificultar la navegación para algunos usuarios.
-Es difícil de mantener o arreglar errores si no se ve bien.

Solución:
Se agregó el enlace al CSS en el <head>:
<link rel="stylesheet" type="text/css" href="index.css">

Beneficios:
-La web ahora se ve como debe.
-Mejora la experiencia y accesibilidad para los usuarios.
-Es facil de mantener.

2. El HTML no tenia comentarios explicativos
Problema:
No había comentarios en el código que expliquen para que sirve cada parte del HTML.

Por qué es una mala práctica:
.Hace más difícil entender o modificar el código despues.
-Complica el trabajo en equipo.
-Puede llevar a errores al no saber que hace cada sección.

Solución:
Se agregaron comentarios que explican:
-La estructura del HTML.
-Secciones como el encabezado, contenido principal, mapa y pie de página.
-Elementos clave como el clima, el mapa y sus controles.

Beneficios:
-Más fácil de leer y mantener.
-Ayuda a otros a entender el código rápido.
-Reduce errores y facilita futuras mejoras.





