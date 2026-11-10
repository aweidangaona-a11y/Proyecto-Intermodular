# DeskFlow — Gestión de soporte al cliente

Aplicación web sencilla para gestionar clientes, incidencias y técnicos desde el navegador. No requiere instalar dependencias ni configurar un servidor.

## Ejecutar

1. Descarga o clona este repositorio.
2. Abre `index.html` con un navegador moderno (Chrome, Firefox, Edge o Safari).
3. Para compartirla en una red o publicarla, sirve la carpeta con cualquier servidor web estático o habilita GitHub Pages.

## Funciones

- Panel principal con estadísticas de clientes, tickets abiertos/resueltos, distribución por estado y actividad reciente.
- Alta, edición, búsqueda, consulta y eliminación de clientes, con su ficha, tickets e historial.
- Creación y edición de tickets asociados a clientes, con prioridad, asignación de técnico y estados Abierto, En proceso, Pendiente y Resuelto.
- Gestión de técnicos y reasignación de incidencias.
- Persistencia automática en el `localStorage` del navegador.

## Persistencia y privacidad

Los datos se guardan localmente en el navegador y perfil donde se usa la aplicación. No se envían a un servidor ni se sincronizan entre dispositivos. Borrar los datos del sitio o cambiar de navegador puede eliminarlos. Para uso compartido multiusuario, se necesita conectar la interfaz a una API y una base de datos con autenticación y copias de seguridad.
