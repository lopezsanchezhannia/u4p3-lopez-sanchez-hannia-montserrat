<!-- título del repo: cambia por tus nombres reales -->
# U4S8 — Lopez Sanchez Hannia Montserrat

<!-- sección con la URL pública de Render -->
## Demo en vivo (producción)
<!-- tu dirección real de Render de esta práctica -->
https://u4s7-lopez-sanchez-hannia-montserrat.onrender.com

## Qué hace este proyecto
<!-- reemplaza el texto entre corchetes por tu descripción -->
La vitrina de servicios es un sistema web service que ofrece la oportunindad de almacenar diferentes servicios, con su descrpcion y precio del servicio. Entrar como administrador y crear cuentas como usuario u operador. 

<!-- sección con las tecnologías usadas -->
## Stack técnico
<!-- las 4 herramientas del curso -->
Django + MySQL (Aiven) + Tailwind CSS + Render

<!-- sección con la prueba de seguridad de la Semana 6 -->
## Cómo se prueba el aislamiento por usuario
<!-- pega aquí la explicación que escribiste en el README de la Semana 6 -->
El usuario_a y usuario_b entran con correo y contraseña cada uno distinta. 
Con sesion iniciada como el primer usuario crea dos servicios y cierra la sesion.
con la sesion en el usuario_a en /servicios/ deben aparecer dos sevicios de a, nunca de usuario_b.
Al momento de ver el usuario en el url y el id del servicio, si modificamos por otro id no correspondiente muestra un señalamiento de 404, no el formulario de edicion del otro usuario. 
Obtuve el resultado esperado.

<!-- sección con el recorrido del curso -->
## Historial de unidades
<!-- Unidad 1 -->
- Unidad 1: portafolio estático con HTML5 + Tailwind
<!-- Unidad 2 -->
- Unidad 2: modelo Servicio migrado a MySQL, deploy dinámico en Render
<!-- Unidad 3 -->
- Unidad 3: CRUD completo con ModelForms + autenticación y sesiones
<!-- Unidad 4 -->
- Unidad 4: paginación, búsqueda, UI review y defensa final