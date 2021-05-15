# Usabilidad
Corregir errores de una interfaz dada para convertirla en más usable

Trabajo correspondiente a la asignatura DI (Desarrollo de Interfaces) perteneciente a la titulación de Técnico Superior en el Desarrollo de aplicaciones multiplataforma.

Dada una interfaz se nos solicitaba encontrar 5 fallos de usabilidad así como corregirlos. Los fallos que detecté fueron los que siguen:

| COMPONENTE| TIPO| DESCRIPCION DEL FALLO| POSIBLES SOLUCIONES|
| ----- | ---- | ---- | ---- |
| Tabla| No es posible eliminar artículos agregados a la tabla.| Dotar a la tabla de un mecanismo para que puedan seleccionarse varios artículos y de un botón para qué al hacer clic, elimine los artículos seleccionados.|
| Tabla| Si los artículos que deben poder agregarse son los que aparecen en la lista desplegable (suponemos que son cargados desde una BD), los registros de la tabla deben 
de ser no editables| Poner los campos de la tabla como no editables.|
| Campo de ingreso de datos| El sistema conforme vamos introduciendo los datos no avisa si los datos introducidos son incorrectos.| Ir comprobando en el momento que cada componente pierde el foco si los datos introducidos son incorrectos.|
| Campo de ingreso de datos| Cuando se introduce un valor no permitido o no se introduce, el sistema avisa con el mensaje “-Error en nombreDelCampo”, no mostrando un mensaje más 
cercano a la realidad y al usuario.| Utilizar un lenguaje más cercano al usuario para especificar los errores. Por ejemplo: “Debe de completar el campo Localidad”, etc…|
| Botón Guardar| No se indica si se guardaron los datos. Debe de tener el mismo comportamiento que el botón “Aceptar” del menú.| Hacer las comprobaciones oportunas mostrando un 
mensaje al usuario indicando si los datos se guardaron correctamente o hubo algún problema|
