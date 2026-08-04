# 📍 FavPlace

FavPlace es una aplicación nativa para iOS desarrollada con **SwiftUI** que permite guardar, organizar y gestionar ubicaciones personalizadas mediante un mapa interactivo basado en **MapKit**. Los usuarios pueden crear lugares, asignarles un nombre, marcarlos como favoritos y navegar entre ellos mediante animaciones fluidas de la cámara del mapa.

El objetivo principal de este proyecto fue profundizar mis conocimientos sobre el framework moderno de mapas de Apple, fortaleciendo el manejo del estado de aplicaciones, la persistencia local y el desarrollo de interfaces interactivas.

---

# Características

- 🗺️ **Mapa interactivo**
  - Explora el mapa utilizando las APIs modernas de MapKit y MapReader disponibles en iOS 17.

- 📍 **Guardado de ubicaciones**
  - Permite crear ubicaciones personalizadas tocando cualquier punto del mapa y asignándoles un nombre.

- ⭐ **Marcadores dinámicos**
  - Diferencia visualmente las ubicaciones favoritas mediante anotaciones que cambian automáticamente su apariencia.

- 🎠 **Carrusel de favoritos**
  - Accede rápidamente a las ubicaciones guardadas mediante una hoja deslizante construida con PresentationDetents.

- ✈️ **Cámara animada**
  - Desplaza suavemente la cámara hacia la ubicación seleccionada para ofrecer una experiencia de navegación más intuitiva.

- 💾 **Persistencia local**
  - Guarda automáticamente la información utilizando Codable y UserDefaults para conservar los datos entre sesiones.

---

# Tecnologías

- Swift 5
- SwiftUI
- MapKit
- MapReader
- CoreLocation
- UserDefaults
- Codable
- JSONEncoder / JSONDecoder

---

# Decisión técnica

Elegí **UserDefaults** junto con **Codable** porque la aplicación únicamente almacena una pequeña cantidad de información estructurada. Esta solución proporciona una persistencia ligera, sencilla de implementar y adecuada para los requerimientos del proyecto sin añadir la complejidad de una base de datos.

---

# Mayor reto

El mayor desafío fue sincronizar las interacciones del usuario con el mapa manteniendo una interfaz fluida. Coordinar las anotaciones, las animaciones de la cámara y las actualizaciones del estado en SwiftUI requirió una gestión cuidadosa para ofrecer una navegación natural y consistente.

---

# ¿Qué aprendí?

Durante este proyecto fortalecí mis conocimientos en:

- Desarrollo de aplicaciones basadas en mapas con MapKit.
- Manejo del estado utilizando SwiftUI.
- Uso de CoreLocation y coordenadas geográficas.
- Persistencia local mediante Codable y UserDefaults.
- Diseño de componentes reutilizables en SwiftUI.
- Creación de experiencias de usuario más intuitivas mediante animaciones y navegación interactiva.

---

# Requisitos

- macOS 14.0 o superior
- Xcode 15.0+
- iOS 17.0+

---

# Instalación

Clona el repositorio:

```bash
git clone https://github.com/isaSanchez-png/FavPlace.git
```

Abre el proyecto en Xcode, selecciona un simulador de iOS y ejecuta la aplicación presionando **⌘R**.

---

# 📍 FavPlace

FavPlace is a native iOS application built with **SwiftUI** that allows users to save, organize, and manage their favorite locations through an interactive map experience powered by **MapKit**. Users can create personalized locations, visualize them with custom map annotations, and quickly navigate between saved places using an animated map camera.

The main objective of this project was to deepen my understanding of Apple's modern mapping framework while improving my knowledge of state management, local persistence, and interactive user interfaces.

---

# Features

- 🗺️ **Interactive Map**
  - Explore locations using the modern MapKit and MapReader APIs introduced in iOS 17.

- 📍 **Save Custom Locations**
  - Tap anywhere on the map to create a custom location, assign a name, and save it for future reference.

- ⭐ **Dynamic Favorite Markers**
  - Visually distinguish favorite locations through dynamic map annotations that automatically update their appearance.

- 🎠 **Favorites Carousel**
  - Browse saved locations through an interactive bottom sheet built with PresentationDetents.

- ✈️ **Animated Camera Navigation**
  - Smoothly animate the map camera to any selected location, improving navigation and user experience.

- 💾 **Local Persistence**
  - Store locations locally using Codable together with UserDefaults to preserve user information between sessions.

---

# Tech Stack

- Swift 5
- SwiftUI
- MapKit
- MapReader
- CoreLocation
- UserDefaults
- Codable
- JSONEncoder / JSONDecoder

---

# Technical Decision

I chose **UserDefaults** together with **Codable** because the application stores a relatively small amount of structured data. This approach provides a lightweight persistence solution while keeping the implementation simple, maintainable, and appropriate for the project's requirements.

---

# Biggest Challenge

The biggest challenge was synchronizing user interactions with the map while maintaining a responsive interface. Managing map annotations, camera animations, and SwiftUI state updates required careful coordination to ensure every interaction felt smooth and intuitive.

---

# What I Learned

Through this project I strengthened my understanding of:

- Building interactive map-based applications with MapKit.
- Managing application state using SwiftUI.
- Working with CoreLocation and geographic coordinates.
- Persisting structured data using Codable and UserDefaults.
- Designing reusable SwiftUI components.
- Creating intuitive user experiences through animations and interactive navigation.

---

# Requirements

- macOS 14.0 or later
- Xcode 15.0+
- iOS 17.0+

---

# Installation

Clone the repository:

```bash
git clone https://github.com/isaSanchez-png/FavPlace.git
```

Open the project in Xcode, select an iOS Simulator, and press **⌘R** to run the application.
