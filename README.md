# Plataforma Web para la Gestion de Actividades

## Descripcion
Es una aplicación que permite administrar proyectos y tareas desde una interfaz web intuitiva.

El sistema facilita la planificación, asignación y seguimiento de actividades dentro de un equipo de trabajo mediante una arquitectura cliente-servidor y una API REST.


---

# Objetivos
- Centralizar la gestion de actividades
- Facilitar la organizacion de eventos
- Registrar las actividades realizadas
- LLevar contol de avance del proyecto

---

# Funcionalidades
- Inicio de sesion
- Gestion de usuarios (crear, editar, eliminar, listar)
- Gestion de actividades (crear, editar, eliminar, listar)
- Gestion de proyectos (crear, editar, eliminar, listar)
- Dashboard con estadisticas
- API REST para gestion de actividades
- Integracion Continua
- Despliegue Continuo

---

# Tecnologias

## Frontend
- HTML
- CSS
- JavaScript

## Backend
- Node.js
- Express

## Base de Datos
- MySQL

## CI/CD
- GitHub Actions

## Deploy
- Render

## Monitoreo
- Prometheus

---

# Estructura del Proyecto

```
miproyecto/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── app.js
│
├── frontend/
│   ├── css/
│   ├── js/
│   ├── pages/
│   └── index.html
│
├── database/
│   ├── schema.sql
│   └── data.sql
│
├── docs/
│   ├── api.md
│   └── diagramas/
│
├── images/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# Requisitos

- Node.js 22+
- MySQL 8+
- Git
- Visual Studio Code
- npm

---

# Instalacion'
## Clonar el repositorio

```bash
git clone https://github.com/RamsesHrndz/Proyecto-Ramses-DevOps.git
```

Entrar al proyecto

```bash
cd Proyecto-Ramses-DevOps
```

Instalar dependencias del backend

```bash
cd backend
npm install
```

Instalar dependencias del frontend

```bash
cd ../frontend
npm install
```

---

# Configuración

Crear un archivo

```
.env
```

Ejemplo

```
PORT=3000

DB_HOST = localhost
DB_PORT = 3306
DB_NAME = Gestion_Act
DB_USERNAME = root
DB_PASSWORD = password

JWT_SECRET = secret
```

---

# Ejecutar Backend

```bash
cd backend
npm start
```

---

# Ejecutar Frontend

Abrir el archivo

```
index.html
```

o iniciar un servidor local.

---

# Monitoreo

El sistema utiliza:

- Prometheus para recolección de métricas.

Se monitorean métricas como:

- Tiempo de respuesta
- Uso de CPU
- Uso de memoria
- Errores HTTP
- Disponibilidad

---

# Autor
Ramses Hernández Vazquez, un joven entusiasta que quiere aprender chino mandarin.
