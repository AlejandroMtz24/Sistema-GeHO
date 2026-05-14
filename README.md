# Sistema GeHO - Gestión de Habitaciones y Operaciones

Sistema centralizado para la gestión automatizada de habitaciones, reservas y perfiles de huéspedes. Este proyecto integra una arquitectura moderna enfocada en la portabilidad, escalabilidad y el cumplimiento de estándares de ingeniería de software.

## 👥 Equipo de Trabajo
* **DevOps:** Alejandro Martínez Bernal (#22100209) - Gestión de infraestructura, contenedores y flujo de trabajo.
* **Backend Developer:** Jorge Arturo Mata Camacho (#C21100514) - Desarrollo de la Web API y lógica de negocio.
* **DBA (Database Administrator):** Christhofer Solis Zamarron (#21100295) - Diseño y gestión de bases de datos.
* **Frontend Developer:** Dana Jael Garcia Martinez (#21100202) - Desarrollo de la interfaz y experiencia de usuario.

## 🚀 Tecnologías Utilizadas
* **Backend:** ASP.NET Core (C#) - Web API.
* **Frontend:** Interfaz Web (HTML/CSS/JS).
* **Bases de Datos:** SQL Server (Relacional) y NoSQL (Auditoría).
* **Infraestructura:** Docker & Docker Compose para contenerización.

## 📂 Estructura del Proyecto
* `/src`: Código fuente (proyectos de Backend y Frontend).
* `/database`: Scripts de inicialización, esquemas y archivos NoSQL.
* `/docker`: Configuraciones de contenedores y orquestación.
* `/docs`: Documentación técnica, diagramas de arquitectura y evidencias.

## 🛠️ Requisitos del Sistema
Para ejecutar este proyecto, es necesario contar con:
* **Docker Desktop** (última versión estable).
* **Git** para el control de versiones.
* **.NET 8 SDK** (para desarrollo local del Backend).
* **Visual Studio 2022** o **VS Code**.

## 🌿 Flujo de Trabajo (Git Flow)
Para garantizar la integridad del código, seguimos estas reglas:
1. **Ramas Principales:** `main` (producción) y `develop` (desarrollo).
2. **Ramas de Tarea:** `feature/nombre-tarea` (siempre se originan desde `develop`).
3. **Integración:** El código solo se integra mediante **Pull Requests** revisados y aprobados por el DevOps.

## 💬 Convención de Commits
Es obligatorio usar el formato `tipo: descripción` para mantener la trazabilidad:
* **`feat:`** Nuevas funcionalidades (ej: `feat: agregar registro de huéspedes`).
* **`fix:`** Corrección de errores (ej: `fix: error en conexión SQL`).
* **`docs:`** Cambios en documentación (ej: `docs: manual de instalación`).
* **`ci:`** Configuraciones de integración y Docker (ej: `ci: actualizar docker-compose`).
* **`test:`** Adición o corrección de pruebas (ej: `test: prueba unitaria de login`).
* **`refactor:`** Mejoras al código que no cambian su función (ej: `refactor: optimizar búsqueda`).

## 📋 Módulos Principales (En desarrollo)
* **Gestión de Habitaciones:** Control de inventario y estados.
* **Módulo de Reservas:** Asignación de fechas y disponibilidad.
* **Registro de Huéspedes:** Perfiles y estancia.
* **Seguridad:** Control de acceso basado en roles.
