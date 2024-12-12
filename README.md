# Medical Assistant

A .NET Core application that serves as an intelligent medical assistant, helping users with their health-related queries and managing medical information.

## Features

- User authentication with JWT tokens
- External authentication providers support
- PostgreSQL database for data storage
- Serilog logging system
- Clean architecture with Domain-Driven Design
- RESTful API endpoints
- Swagger documentation

## Project Structure

```
src/
├── Core/
│   ├── Domain/        # Entities, Value Objects, Aggregates
│   └── Services/      # Business logic and application services
├── Infrastructure/
│   ├── Data/          # Database context and configurations
│   └── Logging/       # Logging configurations and services
└── API/               # Web API controllers and configurations

tests/
├── UnitTests/
└── IntegrationTests/
```

## Prerequisites

- .NET 8.0 SDK
- PostgreSQL 15+
- Visual Studio 2022 or VS Code

## Getting Started

1. Clone the repository
2. Update the connection string in appsettings.json
3. Run database migrations
4. Start the application

## Technology Stack

- ASP.NET Core 8.0
- Entity Framework Core
- PostgreSQL
- ASP.NET Core Identity
- JWT Bearer Authentication
- Serilog
- Swagger/OpenAPI

## License

This project is licensed under the MIT License.