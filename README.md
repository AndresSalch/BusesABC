# BusesABC

BusesABC es un proyecto en Flutter que incluye una API en .NET para gestionar datos relacionados con los autobuses. Su principal función es permitir la compra de tiquetes de bus y ofrecer la visualización en tiempo real de la localización del chofer. Este proyecto está estructurado para soportar múltiples plataformas, incluyendo Android, iOS, Windows, Linux, macOS y la web.

---

## Screenshots
<div Style="display: flex; justify-content: space-evenly;">
<img src="https://github.com/AndresSalch/APP_BUSES/blob/main/Screenshot_20240421-040403.jpg" height="300" />
<img src="https://github.com/AndresSalch/APP_BUSES/blob/main/Screenshot_20240404-203543.jpg" height="300" />
<img src="https://github.com/AndresSalch/APP_BUSES/blob/main/Screenshot_20240404-203530.jpg" height="300" />
<img src="https://github.com/AndresSalch/APP_BUSES/blob/main/Screenshot_20240404-203425.jpg" height="300" />
</div>

---

## Cómo Empezar

### Requisitos Previos

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [SDK de .NET](https://dotnet.microsoft.com/download)

### Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/tuusuario/BusesABC.git
    cd BusesABC
    ```

2. Instala las dependencias de Flutter:
    ```sh
    flutter pub get
    ```

3. Restaura las dependencias de .NET:
    ```sh
    cd API_FLUTTER/ApiFlutter
    dotnet restore
    ```

### Ejecutando el Proyecto

#### Aplicación Flutter

Para ejecutar la aplicación Flutter, usa el siguiente comando:
```sh
flutter run
```

#### API .NET

Para ejecutar la API de .NET, navega al directorio de la API y usa el siguiente comando:

```sh
cd API_FLUTTER/ApiFlutter
dotnet run

```

## Detalles del Proyecto

### Flutter

La parte de Flutter del proyecto se encuentra en el directorio lib. Contiene el código principal de la aplicación para la gestión de autobuses.

### API .NET

La API de .NET se encuentra en el directorio ApiFlutter. Proporciona los endpoints para gestionar los datos relacionados con los autobuses.

---

## License

BusesABC © 2023 by Herberth Andrés Alfaro Vega is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

