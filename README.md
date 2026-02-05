#  Ticket System

Aplicación web para la gestión de tickets de soporte técnico.  
Permite a los usuarios registrarse, iniciar sesión, crear solicitudes y hacer seguimiento a sus tickets.

Este proyecto fue desarrollado como práctica enfocada principalmente en **backend**.

##  Contexto del cliente

Una empresa necesita un sistema interno para gestionar solicitudes de soporte técnico.
Actualmente reciben peticiones por WhatsApp y correo, lo que genera desorden y pérdida de información.

El cliente solicita una aplicación web que permita:
- Registro e inicio de sesión de usuarios
- Creación de tickets de soporte
- Visualización del estado de los tickets


##  Funcionalidades

- Registro de usuarios
- Inicio de sesión
- Creación de tickets
- Listado de tickets
- Estructura backend con separación de responsabilidades
- Persistencia de datos usando SQLite


##  Tecnologías

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js
- SQLite


##  Estructura del proyecto

ticket-system/
│
├── Back-end/
│ ├── src/
│ │ ├── controllers/
│ │ ├── routes/
│ │ ├── models/
│ │ ├── services/
│ │ ├── database/
│ │ ├── app.js
│ │ └── server.js
│ ├── package.json
│ └── package-lock.json
│
├── front-end/
│ ├── css/
│ ├── js/
│ └── pages/
│
├── README.md
└── .gitignore

