# EventManagementSystem

Sistema de gestión de eventos desarrollado con ASP.NET , siguiendo los principios de **Clean Architecture**.

---

## 📁 Estructura del Proyecto

EventManagementSystemBackEnd/
├── Domain/ # Entidades del dominio y contratos (interfaces)
│ ├── Entities/
│ └── Interfaces/
├── Application/ # Casos de uso y DTOs
│ ├── UseCases/
│ └── DTOs/
├── Infrastructure/ # Implementaciones concretas (BD, servicios externos)
│ ├── Repositories/
│ ├── Services/
│ └── Data/
├── Presentation/ # Capa de presentación (Razor Pages, Middleware)
│ ├── Controllers/
