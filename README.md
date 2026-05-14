# Sistema GeHO - Gestión de Habitaciones y Operaciones

Sistema centralizado para la gestión automatizada de habitaciones, reservas y perfiles de huéspedes. Este proyecto integra una arquitectura moderna con enfoque en portabilidad y escalabilidad.

## 🚀 Tecnologías Utilizadas
* **Backend:** ASP.NET Core (C#) - Web API.
* **Frontend:** Interfaz Web.
* **Base de Datos Relacional:** SQL Server (ejecutándose en Docker).
* **Base de Datos NoSQL:** Auditoría y logs (ejecutándose en Docker).
* **Infraestructura:** Docker & Docker Compose.

## 📂 Estructura del Proyecto
* `/src`: Código fuente (Backend y Frontend).
* `/database`: Scripts de inicialización SQL y configuración NoSQL.
* `/docker`: Archivos de configuración para contenedores.
* `/docs`: Documentación técnica, diagramas y evidencias.

## 🛠️ Configuración del Ambiente
*(Próximamente: Instrucciones para levantar el proyecto con Docker Compose)*

## 🌿 Flujo de Trabajo (Git Flow)
Para mantener el orden y la trazabilidad, seguimos estas reglas:
1. **Ramas Principales:** `main` (producción) y `develop` (desarrollo).
2. **Ramas de Tarea:** `feature/nombre-tarea` (siempre salen de `develop`).
3. **Integración:** Solo mediante **Pull Requests** aprobados.

## 💬 Convención de Commits
Se debe usar el formato `tipo: descripción`:
* `feat:` Nuevas funcionalidades.
* `fix:` Corrección de errores.
* `docs:` Cambios en documentación.
* `ci:` Configuraciones de Docker/Deployment.
