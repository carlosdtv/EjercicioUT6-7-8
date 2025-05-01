
# Ejercicio 4 - Api Rick y Morty

Aplicación que realiza una petición a la API pública de Rick y Morty https://rickandmortyapi.com/) para mostrar personajes de la serie con sus datos que se encuentran en la API.

## Tecnologías utilizadas

- .NET Framework 4.8
- Visual Studio 2022
- .NET 6.0 o superior
- WPF (Windows Presentation Foundation)
- API REST (https://rickandmortyapi.com/)
- HttpClient
- C#

### Arquitectura y diseño

## Patrón de diseño utilizado

- MVVM (Model-View-ViewModel)

## Componentes clave del proyecto

- Modelos: representan los datos de los personajes de la API.
- ViewModels: presentan la lógica de presentación y gestionan la carga de datos desde la API.
- Vistas (Views): XAML con interfaz que presenta los personajes en filas.

## Integración de la aplicación con la API

- Endpoint utilizado: https://rickandmortyapi.com/api/character
- Se usa HttpClient para las solicitudes GET.
- Los datos JSON se deserializan a objetos C#.

### Configuración y uso

## Requisitos del sistema

- Sistema operativo W10 o superior
- .NET 6.0 o superior
- Visual Studio 2022 o superior

## Instalación y ejecución

1. Clonar el repositorio: git clone https://github.com/carlosdtv/EjercicioUT6-7-8.git
2. Abrir el archivo .sln con Visual Studio
3. Restaurar paquetes NuGet si es necesario
4. Establecer modo de compilación en Release o Debug
5. Ejecutar con F5 o dotnet run desde la carpeta del proyecto

## Consumo de la API

- No requiere autenticación
- Se utiliza el endpoint https://rickandmortyapi.com/api/character
- Los datos se gestionan en el ViewModel y se enlazan a la vista mediante data binding.

