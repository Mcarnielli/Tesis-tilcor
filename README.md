# Tilcor — Tesis

Proyecto de tesis para [Analista en sistemas], IES Córdoba.

## Descripción
[Optimizacion de tiempo y facilidad de registros, para TILCOR, la app cuenta con un monitoreo IoT para que no se le escape ningun dato a la empresa]

## Tecnologías

- Base de datos:  PostgreSQL — Motor de base de datos relacional principal. Almacena clientes, lotes, producción, pedidos y facturas.

TimescaleDB — Extensión de PostgreSQL especializada en series temporales. Almacena los datos de los sensores IoT con compresión automática a los 7 días.

SQL (DDL/DML) — Lenguaje de consulta usado para la definición de tablas, índices, vistas y tipos enumerados.




- Frontend:  React.js — Framework de JavaScript para la construcción de interfaces web dinámicas y reactivas. Mencionado en la propuesta del sistema para el desarrollo del dashboard principal.

HTML5 — Lenguaje de marcado base de toda la aplicación web TILCOR desarrollada.

CSS3 — Hojas de estilo con variables CSS, animaciones, flexbox y grid para el diseño responsive de la app.

JavaScript (Vanilla JS) — Lógica de la app TILCOR: navegación, cálculos de postura, simulación de sensores, renderizado dinámico.

Tabler Icons — Librería de íconos vectoriales usada en la interfaz de TILCOR App (cdn.jsdelivr.net/npm/@tabler/icons-webfont).

Chart.js — Librería de JavaScript para la generación de gráficas interactivas: curva de producción vs tabla genética, temperatura, humedad y mortalidad semanal.

PWA (Progressive Web App) — Tecnología que permite instalar la app web en el celular como si fuera una app nativa, con soporte offline.

Service Worker — Script de JavaScript que permite el funcionamiento offline de la PWA y el cacheo de recursos.

Web App Manifest — Archivo JSON que define nombre, ícono, colores y comportamiento de la PWA al instalarse.
            

-Backend: Python — Lenguaje de programación principal del backend.

Django — Framework web de Python usado para la lógica de negocio, modelos de datos y administración.

Django REST Framework (DRF) — Extensión de Django para construir la API REST que conecta el frontend con la base de datos.

Django Channels — Extensión de Django para WebSocket, permite el envío de datos en tiempo real al dashboard IoT.

Celery — Librería de Python para la ejecución de tareas asincrónicas: reportes automáticos, envío de alertas y notificaciones programadas.

Gunicorn — Servidor WSGI de Python para correr Django en producción.

JWT (JSON Web Tokens) — Estándar de autenticación stateless usado para la gestión de sesiones y roles de usuario.



IoT / TIEMPO REAL

MQTT (Message Queuing Telemetry Transport) — Protocolo de mensajería ligero para la comunicación entre los sensores del galpón y el sistema.

Eclipse Mosquitto — Broker MQTT open source que recibe y distribuye los mensajes de los sensores.

Paho MQTT (Python) — Librería de Python para conectar el backend al broker MQTT como cliente suscriptor.

WebSocket — Protocolo de comunicación bidireccional en tiempo real entre el servidor y el dashboard del navegador.






## Estado
[Terminado / En progreso] — [3ºaño]
