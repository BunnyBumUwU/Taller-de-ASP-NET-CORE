Proyecto ASP.NET Core – Lista de Tareas

Este proyecto fue desarrollado durante el talle de  "Uso de ASP.NET Core" y consiste en una aplicación web usando el patrón Modelo-Vista-Controlador (MVC).

Funcionalidades

Aplicación web con ASP.NET Core MVC.

Registro y autenticación de usuarios.

Listas de tareas personalizadas por usuario.

Operaciones CRUD en tareas: crear, ver, actualizar y eliminar.

Filtrado y orden de tareas por prioridad.

Cómo ejecutar el proyecto
1. Clonar el repositorio
git clone https://github.com/BunnyBumUwU/Taller-de-ASP-NET-CORE

2. Abrir el proyecto

Abre la solución en Visual Studio o Visual Studio Code.

3. Configurar la base de datos

Actualiza la cadena de conexión en appsettings.json.

Ejecuta las migraciones:

dotnet ef database update

4. Ejecutar la aplicación
dotnet run
Accede a la app en: https://localhost:7236

Tecnologías utilizadas

ASP.NET Core 7.0

Entity Framework Core

SQL Server

Bootstrap (diseño responsivo)
