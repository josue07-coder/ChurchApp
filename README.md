# ChurchApp 🙏

ChurchApp es un sistema moderno y modular para la **gestión de iglesias**, desarrollado con **Clean Architecture** y tecnologías de .NET. Está diseñado para facilitar el control de miembros, eventos, finanzas, asistencia por grupos y mucho más.

---

## ✨ Características principales

- Registro completo de miembros
- Gestión de grupos (caballeros, damas, jóvenes, niños, etc.)
- Creación de eventos por grupo
- Registro de asistencia por evento y grupo
- Control de ingresos y egresos (finanzas)
- Reportes por mes, grupo y tipo de actividad
- Arquitectura limpia y profesional
- Interfaz web moderna (Blazor WebAssembly)

---

## 🧱 Tecnologías utilizadas

- ASP.NET Core Web API
- Blazor WebAssembly (frontend)
- Entity Framework Core
- SQL Server
- Clean Architecture

---

## 🚀 Estructura del proyecto

```
ChurchApp/
├── Core/
│   ├── ChurchApp.Domain
│   └── ChurchApp.Application
├── Infrastructure/
│   ├── Persistence
│   ├── Identity
│   └── Shared
├── Presentation/
│   └── ChurchApp.API
└── ChurchApp.Client (Blazor WebAssembly)
```

---

## 📦 Instalación local

1. Clona el repositorio:
```bash
git clone https://github.com/josue07-coder/ChurchApp.git
```

2. Restaura los paquetes:
```bash
dotnet restore
```

3. Aplica las migraciones:
```bash
dotnet ef database update --project ChurchApp.Infrastructure
```

4. Ejecuta el proyecto:
```bash
dotnet run --project ChurchApp.API
```

---

## 🤝 Autor

Desarrollado por **Josue Blanco Batista**  
📧 Contacto: josue07.coder@gmail.com

---

## 📄 Licencia

Este proyecto es de uso educativo y comunitario. Puedes modificarlo, reutilizarlo y mejorarlo con fines sociales o eclesiásticos.

