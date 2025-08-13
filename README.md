# ExamenFinalPrograAvanzada
Examen práctico: Consumo de API y UI con Bootstrap
Objetivo
Desarrollar una interfaz web que consuma el endpoint https://jsonplaceholder.typicode.com/users, muestre toda la información de los usuarios en tarjetas, incluya búsqueda en tiempo real, y utilice dos modales: uno para ver el mapa por latitud/longitud y otro para ver la información completa del usuario. Debe usarse JavaScript, HTML, CSS y Bootstrap.

Requisitos técnicos
Tecnologías: HTML, CSS, JavaScript, Bootstrap 5.x.

Consumo de datos: fetch al endpoint indicado, sin librerías adicionales para AJAX.

Render: tarjetas responsivas con toda la información visible y organizada.

Búsqueda: input centrado en la parte superior de la grilla, filtrando por nombre, username, email, ciudad y nombre de la empresa.

Modales:
a) Modal Mapa: muestra un mapa en base a address.geo.lat y address.geo.lng. Se permite cualquier librería de mapas.
b) Modal Empresa: muestra la información completa de la empresa.

Estilo: usar utilidades de Bootstrap; CSS propio solo para ajustes finos.

Sin frameworks adicionales de JS; se permite Leaflet, Google Maps, u otra librería solo para el mapa.

Disposición visual
Encabezado con título del sitio.

Input de filtro centrado horizontalmente.

Contador de resultados visibles.

Grilla de tarjetas con la información principal y botones: Ver mapa y Ver Empresa.

Modal Mapa y Modal Usuario.

Contenido mínimo por tarjeta
Nombre completo y username.

Email y teléfono.

Dirección resumida: street, suite, city, zipcode.

Website clicable en nueva pestaña.

Empresa: nombre visible en la tarjeta.

Botones: Ver mapa y Ver usuario.

Modal Mapa
Título con nombre del usuario y ciudad.

Mapa con marcador en lat, lng.

Enlace para abrir el punto en una pestaña externa.

El mapa debe reajustar tamaño al abrir el modal.

Modal Usuario
Secciones: datos personales, contacto, dirección completa, empresa (name, catchPhrase, bs), geolocalización.

Cierre accesible con teclado y botón.

Comportamiento del filtro
Filtrado en tiempo real sin recargar la página.

Coincidencias parciales, insensible a mayúsculas.

Debe actualizar el contador de resultados.

Validaciones mínimas
Manejar errores de red con mensaje visible.


Lineamientos de entrega
Entregar en github (link) pero ejecutandose como pagina web.

Rúbrica de evaluación (15% de la nota final del curso)
Consumo correcto de la API con fetch y manejo de errores: 3%.

Render de tarjetas con toda la información requerida y diseño responsive: 3%.

Búsqueda en tiempo real con input centrado y contador de resultados: 2 %.

Modal Usuario mostrando información completa y bien estructurada: 2 %.

Modal Mapa funcional con marcador y vista adecuada: 2 %.

Uso adecuado de Bootstrap y usabilidad general: 2 %.

Calidad del código, nomenclatura solicitada y organización de archivos: 1 %.
Total: 15 puntos.

Criterios de aprobación por ítem
Cumple totalmente: puntaje completo.

Cumple parcialmente: mitad del puntaje.

No cumple o presenta errores críticos: cero.

Restricciones
Mantener textos en español.

Pruebas sugeridas
La página carga y muestra 10 usuarios desde la API.

El filtro reduce y aumenta resultados correctamente.

Abrir el modal de mapa y ver marcador en coordenadas del usuario.

Abrir modal de empresa y ver info completa.

Probar en móvil, tablet y escritorio.

Simular error de red cambiando la URL y verificar mensaje de error.
