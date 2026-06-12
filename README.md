# FavPlace

**FavPlace** es una aplicación iOS nativa desarrollada en SwiftUI que permite a los usuarios interactuar con un mapa interactivo para guardar y gestionar sus lugares favoritos. Utiliza el framework moderno de MapKit para iOS 17+ y almacena la información de forma local.

## Características
* **Mapa Interactivo:** Explora el mapa utilizando las APIs modernas de `MapKit` y `MapReader`.
* **Guardado de Lugares:** Mantén presionado o toca cualquier coordenada en el mapa para abrir un diálogo personalizado que permite asignarle un nombre y marcarlo como favorito.
* **Marcadores Personalizados (`Annotations`):** Los marcadores cambian de color dinámicamente en el mapa según el estado de favorito (Cian para favoritos, Negro para normales).
* **Carrusel de Favoritos:** Una hoja inferior deslizante (`PresentationDetents`) muestra un carrusel horizontal con las ubicaciones guardadas.
* **Cámara Animada:** Al seleccionar una tarjeta en la lista inferior, la cámara del mapa vuela suavemente hacia las coordenadas del lugar guardado.
* **Persistencia Local:** Los lugares se guardan automáticamente en el dispositivo utilizando codificación `Codable` y `UserDefaults`.

---

## Tecnologías Utilizadas
* **SwiftUI** (Arquitectura de vistas declarativa, Sheets nativos, Materiales translúcidos).
* **MapKit** (Map, MapReader, MapCameraPosition, Map annotations).
* **CoreLocation** (Manejo de coordenadas `CLLocationCoordinate2D`).
* **Foundation** (Protocolo `Codable` y `JSONEncoder`/`JSONDecoder` para serialización de datos).

---

**FavPlace** is a native iOS application built with SwiftUI that allows users to interact with an intuitive map to save and manage their favorite locations. It leverages the modern MapKit framework for iOS 17+ and stores data locally.

## Features
* **Interactive Map:** Explore the map utilizing modern `MapKit` and `MapReader` APIs.
* **Save Locations:** Tap on any coordinate on the map to trigger a custom dialog to name the location and mark it as a favorite.
* **Custom Markers (`Annotations`):** Map pins dynamically change color based on their favorite status (Cyan for favorites, Black for regular locations).
* **Favorites Carousel:** A modern bottom sheet overlay (`PresentationDetents`) presents a horizontal scrollable list of all saved locations.
* **Animated Camera Flyover:** Tapping any card in the list smoothly animates the map camera to center directly onto the saved location's coordinates.
* **Local Persistence:** All locations are automatically synchronized and stored on the device using `Codable` serialization and `UserDefaults`.

---

## Technologies Used
* **SwiftUI** (Declarative view hierarchy, native bottom sheets, translucent materials).
* **MapKit** (Map, MapReader, MapCameraPosition, Map annotations).
* **CoreLocation** (Handling `CLLocationCoordinate2D` structures).
* **Foundation** (`Codable` protocol along with `JSONEncoder`/`JSONDecoder` for data serialization).
