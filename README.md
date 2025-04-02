# eHub - Eports Team Manager - Backend

[![.NET](https://img.shields.io/badge/.NET-6.0-blue)](https://dotnet.microsoft.com/)
[![Clean Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-brightgreen)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Backend para aplicación de gestión de equipos de esports (League of Legends) construido con .NET 6 siguiendo Clean Architecture y Domain-Driven Design. Proyecto escalable con futura integración de frontend Android.

## Características Técnicas

- ✅ **Clean Architecture** con 4 capas: Domain, Application, Infrastructure y Presentation
- 🎯 **Domain-Driven Design** (DDD) con entidades y agregados
- 🚀 **RESTful API** con documentación Swagger/OpenAPI
- ⚙️ **Entity Framework Core** como ORM (SQL Server/PostgreSQL)
- 🔄 **Patrón Repository** y **Unit of Work** para acceso a datos
- 💉 **Inyección de Dependencias** (Microsoft DI)
- 📡 **CQRS** con MediatR para separación de comandos y consultas
- ✅ **Validaciones** con FluentValidation
- 🔐 Autenticación JWT
- 🧪 **Testing** con xUnit y Moq
- 🏗️ Principios SOLID y DRY
- 🌐 Integración con **API de Riot Games** (League of Legends)

## Funcionalidades Principales

### 1. Historial de Partidas
- Integración con API de Riot Games para obtener partidas recientes
- Cacheo de resultados para mejor performance
- Sistema de actualización asíncrona de datos

### 2. Gestión de Equipos
- Creación/Edición de equipos con roles (capitán, miembro)
- Calendario colaborativo con eventos y recordatorios
- Sistema de tareas asignables (Scrum-like)
- Invitaciones y solicitudes de unión

### 3. Logros y Progreso
- Sistema de logros desbloqueables basados en tareas
- Badges y recompensas virtuales
- Seguimiento de progreso individual/grupal
- Integración con sistema de tareas

## Requisitos e Instalación

1. Clonar repositorio
   ```bash
   git clone https://github.com/tu-usuario/esports-team-manager.git
