Agenda de Citas Veterinarias (Proyecto de aprendizaje)
=======================================================

Aplicación desarrollada como **proyecto de práctica frontend**.  
Permite gestionar citas veterinarias de forma local, utilizando **HTML, Bootstrap 5 y JavaScript vanilla**, sin frameworks.

El objetivo principal del proyecto fue **practicar la creación de interfaces dinámicas**, el manejo de estados de UI, validaciones de formularios y la persistencia de datos usando **localStorage**, manteniendo una estructura simple y fácil de entender.

Características
----------------
- Agenda de citas con **creación, edición y eliminación**, persistidas en `localStorage`.
- Uso de **modal de Bootstrap** para capturar información:
  - Mascota
  - Propietario
  - Fecha
  - Hora
  - Síntomas
  - Tipo de animal
- Validaciones de formulario:
  - Campos obligatorios
  - Rango horario permitido (08:00 – 20:00)
  - Límite de caracteres en el campo de síntomas
- **Filtros en tiempo real**:
  - Por estado de la cita (abierta, anulada, terminada)
  - Por nombre de mascota o propietario
- Tarjetas responsivas con **imágenes según el tipo de animal**.
- Cambio de estado de la cita directamente desde cada tarjeta.
- Feedback visual al usuario mediante **SweetAlert2**.

Stack
-----
- HTML5
- CSS3
- Bootstrap 5.3 (CDN)
- Font Awesome (CDN)
- SweetAlert2 (CDN)
- JavaScript vanilla
- localStorage

Scripts
-------
- El proyecto no requiere instalación de dependencias.
- Puede ejecutarse:
  - Abriendo `index.html` directamente en el navegador
  - Usando una extensión tipo **Live Server**

Estructura del proyecto
-----------------------
/
index.html # Maquetado principal, modal y contenedor de tarjetas
style.css # Estilos personalizados sobre Bootstrap
script.js # Lógica CRUD, filtros, validaciones y renderizado dinámico
img/ # Imágenes asociadas al tipo de animal


Cómo ejecutar el proyecto
-------------------------
1. Clonar o descargar el repositorio.
2. Abrir el archivo `index.html` en el navegador (doble clic o Live Server).
3. Crear, editar o eliminar citas.
4. Los datos se guardan automáticamente en el navegador mediante `localStorage`.

Notas de aprendizaje
--------------------
- Práctica de:
  - Uso de modales con Bootstrap.
  - Validaciones de formularios sin frameworks.
  - Manejo de estados de UI con JavaScript vanilla.
- Implementación de persistencia de datos usando `localStorage`.
- Renderizado dinámico de tarjetas y filtros en tiempo real.
- Mejora de la experiencia de usuario mediante alertas y feedback visual.
