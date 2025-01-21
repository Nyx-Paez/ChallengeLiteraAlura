Biblioteca Literaria - LiterAlura
LiterAlura es un proyecto desarrollado en Java con Spring Boot y Gradle, que tiene como objetivo almacenar y gestionar información sobre libros a través de una API, realizando búsquedas en una base de datos PostgreSQL.

Características
Búsqueda de libros: Permite buscar libros por título, autor, idioma, temas y número de descargas.
Almacenamiento: Almacena información de libros y autores en una base de datos PostgreSQL.
Estadísticas: Genera estadísticas sobre el número de descargas de los libros.
Integración de API: Obtiene datos de libros de la API de Gutendex y los adapta para su almacenamiento en la base de datos.
Tecnologías Utilizadas
Java 17
Spring Boot: El framework principal del proyecto.
Gradle: Herramienta para la gestión de dependencias.
JPA (Java Persistence API) y Hibernate: Para la gestión de entidades y relaciones en la base de datos.
PostgreSQL: Base de datos para almacenar libros y autores.
Jackson: Utilizado para la deserialización de datos en formato JSON.
API de Gutendex: Fuente para obtener información sobre libros.
Instalación y Configuración
Clonación del Repositorio: Se debe clonar el repositorio y acceder a la carpeta del proyecto.

Configuración de la Base de Datos:

Crear una base de datos en PostgreSQL.
Actualizar el archivo de configuración con las credenciales de acceso a la base de datos.
Construcción del Proyecto: Se necesita construir el proyecto para preparar la aplicación para su ejecución.

Ejecución de la Aplicación: Iniciar la aplicación para comenzar a usarla.

Opción Sin Línea de Comando: Alternativamente, se puede utilizar Spring Initializr para configurar el proyecto desde su interfaz web, ingresando los detalles necesarios.

Uso
Al iniciar la aplicación, se presentará un menú interactivo en la consola con las siguientes opciones:

Buscar Libros: Permite buscar libros en la API de Gutendex y almacenarlos.
Listar Libros: Muestra todos los libros almacenados.
Filtrar Libros por Idioma: Permite listar libros según el idioma.
Listar Autores: Presenta todos los autores junto a sus libros.
Encontrar Autores por Año: Muestra los autores vivos organizados por año.
Top 10 Libros Más Descargados: Lista los libros más descargados.
Buscar Autores por Nombre: Facilita la búsqueda de autores mediante su nombre.
Análisis de Datos: Muestra estadísticas sobre el número de descargas.

Recursos Adicionales
Documentación de Spring Boot.
Métodos de Consulta JPA.
API de Gutendex.
Postman para manejar solicitudes de API.
