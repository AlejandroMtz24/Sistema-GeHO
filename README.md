# Sistema GeHO - Gestión de Habitaciones y Operaciones

Sistema centralizado para la gestión automatizada de habitaciones, reservas y perfiles de huéspedes. Este proyecto integra una arquitectura moderna enfocada en la portabilidad, escalabilidad y el cumplimiento de estándares de ingeniería de software.

## 👥 Equipo de Trabajo
* **DevOps:** Alejandro Martínez Bernal (#22100209) - Gestión de infraestructura, contenedores y flujo de trabajo.
* **Backend Developer:** Jorge Arturo Mata Camacho (#C21100514) - Desarrollo de la Web API y lógica de negocio.
* **DBA (Database Administrator):** Christhofer Solis Zamarron (#21100295) - Diseño y gestión de bases de datos.
* **Frontend Developer:** Jael Garcia Martinez (#21100202) - Desarrollo de la interfaz y experiencia de usuario.

## 🚀 Tecnologías Utilizadas
* **Backend:** ASP.NET Core (C#) - Web API.
* **Frontend:** Interfaz Web (HTML/CSS/JS).
* **Bases de Datos:** SQL Server (Relacional) y MongoDB (NoSQL para auditoría).
* **Infraestructura:** Docker & Docker Compose para contenerización.

## 📂 Estructura del Proyecto
* **`/database`**: Scripts de inicialización y configuración de datos.
  * `/sql-server`: Definición de tablas, procedimientos y esquemas relacionales.
  * `/mongodb`: Scripts de inicialización y configuración para la base de datos NoSQL.
* **`/docker`**: Orquestación de servicios mediante `docker-compose.yml`.
* **`/docs`**: Documentación técnica y evidencias del proyecto.
  * `/diagrams`: Diagramas de arquitectura, entidad-relación y casos de uso.
  * `/evidence`: Guías de ejecución, manuales y evidencias de pruebas.
* **`/src`**: Código fuente de la aplicación.
  * `/backend`: Proyecto ASP.NET Core Web API.
  * `/frontend`: Archivos de la interfaz de usuario.

## 🛠️ Requisitos del Sistema
Para ejecutar este proyecto, es necesario contar con:
* **Docker Desktop** (última versión estable).
* **Git** para el control de versiones.
* **.NET 8 SDK** (para desarrollo local del Backend).
* **Visual Studio 2022** o **VS Code**.

## 🌿 Flujo de Trabajo (Git Flow)
1. **Ramas Principales:** `main` (producción) y `develop` (desarrollo).
2. **Ramas de Tarea:** `feature/nombre-tarea` (se originan desde `develop`).
3. **Integración:** El código se integra mediante **Pull Requests** revisados por el DevOps.

## 💬 Convención de Commits
Formato obligatorio: `tipo: descripción`
* **`feat:`** Nuevas funcionalidades.
* **`fix:`** Corrección de errores.
* **`docs:`** Cambios en documentación.
* **`ci:`** Configuraciones de integración y Docker.
* **`test:`** Adición o corrección de pruebas.
* **`refactor:`** Mejoras al código que no cambian su función.
