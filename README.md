# Flutter Movie Catalog
![68747470733a2f2f692e696d6775722e636f6d2f3775434269](https://github.com/user-attachments/assets/fdcdd967-fbf0-4f68-96b7-bb0ea66c906b)

Flutter Movie Catalog es una aplicación móvil desarrollada en Flutter que permite a los usuarios explorar y descubrir películas. La aplicación muestra una lista de películas populares, permite buscar por título, ver detalles específicos de cada película, y marcar películas como favoritas.

## Características

- **Explorar Películas**: Visualiza una lista de películas populares actualizadas.
- **Búsqueda de Películas**: Busca películas por título para encontrar tus favoritas rápidamente.
- **Detalles de la Película**: Visualiza información detallada de cada película, incluyendo sinopsis, fecha de lanzamiento, calificaciones, y más.
- **Favoritos**: Marca y organiza tus películas favoritas para un fácil acceso.
- **Interfaz Intuitiva**: Diseño moderno y fácil de usar, inspirado en Material Design.

## Tecnologías Utilizadas

- **Lenguaje**: Dart
- **Framework**: Flutter
- **Arquitectura**: MVVM (Model-View-ViewModel)
- **APIs**: The Movie Database (TMDb) API para obtener datos de las películas.
- **Dependencias**:
  - **http**: Para realizar solicitudes a la API de TMDb.
  - **provider**: Para la gestión del estado.
  - **flutter_bloc**: Para la implementación del patrón BLoC.
  - **cached_network_image**: Para la carga y almacenamiento en caché de imágenes.

## Instalación

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/albingg98/Flutter_MovieCatalog.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd Flutter_MovieCatalog
    ```
3. Instala las dependencias necesarias:
    ```bash
    flutter pub get
    ```
4. Obtén tu clave de API de [TMDb](https://www.themoviedb.org/documentation/api) y configúrala en el proyecto.
5. Ejecuta la aplicación en un emulador o dispositivo:
    ```bash
    flutter run
    ```
