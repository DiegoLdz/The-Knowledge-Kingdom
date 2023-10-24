## 📝 Descripción

Si estás buscando una forma sencilla y rápida de construir APIs en ASP.NET, Minimal API es tu amigo. Esta nota te dará una visión general de qué es Minimal API y cómo puedes comenzar con él.

## 🤔 ¿Qué es Minimal API?

Minimal API es una característica de ASP.NET Core que permite crear APIs web con el mínimo de código y configuración posible. Es especialmente útil para prototipos, microservicios o cualquier proyecto donde quieras poner en marcha una API de manera rápida.

## 🌟 Características

### Menos es Más

- Escribe menos código para lograr las mismas tareas en comparación con las aproximaciones tradicionales.

### Rápido y Eficiente

- Diseñado con rendimiento en mente; consume menos recursos y ofrece tiempos de respuesta rápidos.

### Flexible

- Aunque es minimalista en su enfoque, puedes ampliarlo y añadirle más funcionalidades según las necesidades del proyecto.

## 🛠️ ¿Cómo funciona?

En un proyecto ASP.NET, puedes configurar una Minimal API directamente en el archivo `Program.cs`, sin necesidad de crear controladores o modelos específicos si no los necesitas.

var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();

app.MapGet("/", () => "Hello World!");

app.Run();

## 🚀 Primeros Pasos

1. **Instala ASP.NET Core**: Asegúrate de tener instalada la versión adecuada de ASP.NET Core que soporte Minimal API.
    
2. **Crea un Nuevo Proyecto**: Utiliza Visual Studio o la línea de comandos para crear un nuevo proyecto de ASP.NET Core.
    
3. **Edita `Program.cs`**: Abre el archivo `Program.cs` y empieza a añadir tus rutas y lógica de negocio.
    
4. **Ejecuta y Prueba**: Una vez que hayas añadido algunas rutas y lógica, ejecuta la aplicación para probarla.