# Jose Escobedo

**Ingenieria Electronica y Automatica | Sistemas Embebidos, Robotica y Desarrollo de Software**

Estudiante de Ingenieria Electronica y Automatica en la Universidad de Oviedo. Mi trabajo se centra en la convergencia entre hardware y software: desarrollo de firmware para sistemas embebidos, redes de sensores IoT, modelado de sistemas de robotica autonoma y aplicaciones nativas orientadas a privacidad y alto rendimiento.

---

## Areas de Especializacion

- **Sistemas Embebidos e IoT:** Diseno y programacion de firmware para microcontroladores (ESP32, PIC, arquitecturas ARM/AVR), integracion de sensores ambientales e industriales, comunicacion inalambrica LoRaWAN y optimizacion de consumo (Deep Sleep).
- **Robotica y Modelado de Sistemas:** Especificacion formal y arquitectura mediante SysML v2 aplicada a vehiculos terrestres no tripulados (UGV), sistemas de control y automatizacion.
- **Desarrollo Movil y de Software:** Aplicaciones nativas Android en Kotlin con arquitecturas reactivas y servicios del sistema de bajo nivel, asi como herramientas web centradas en privacidad que procesan datos exclusivamente en el lado del cliente.

---

## Proyectos Destacados

### [ScrollStop](https://github.com/josescobedov/ScrollStop)
Aplicacion nativa Android desarrollada en Kotlin orientada al bienestar digital y control de tiempo de pantalla.
- **Arquitectura:** Servicio de accesibilidad (`AccessibilityService`) reactivo con consumo nulo de recursos en reposo.
- **Privacidad estricta:** La aplicacion no solicita permisos de internet (`android.permission.INTERNET`), garantizando que ningun dato abandone el dispositivo.
- **Interfaz:** Diseno minimalista optimizado para paneles OLED con perfiles de uso y descansos configurables.
- **Tecnologias:** Kotlin, Android SDK, Gradle, Jetpack.

### [SecurDoc Local](https://github.com/josescobedov/securdoc-local)
Herramienta web de ofuscacion y proteccion de documentos confidenciales (DNI, pasaportes, contratos) antes de su envio digital.
- **Procesamiento en cliente:** Manipulacion de imagenes y rasterizado de PDF ejecutado íntegramente en la memoria del navegador.
- **Seguridad documental:** Algoritmo de conversion a blanco y negro de luminancia perceptual (Rec. 709) con contraste adaptable y superposicion de marcas de agua diagonales de alta resistencia a borrado.
- **Tecnologias:** JavaScript (ES6+), HTML5 Canvas API, PDF.js, jsPDF, Tailwind CSS.
- **Acceso:** [Demo en vivo](https://josescobedov.github.io/securdoc-local/)

### [BosqueLab LoRa Node](https://github.com/josescobedov/BosqueLab)
Nodo de telemetria ambiental para monitorizacion forestal remota de largo alcance.
- **Hardware y sensores:** Microcontrolador TTGO T-Beam / ESP32 con transceptor LoRa SX1276. Monitorizacion de CO (MQ7), gases generales (MQ135), particulas en suspension (SDS011 PM2.5/PM10), CO2 (SCD30) y variables barometricas (BME280).
- **Red y autonomia:** Transmision de paquetes compactados binarios hacia The Things Network (TTN) mediante LoRaWAN OTAA y gestion de energia mediante ciclos de hibernacion profunda.
- **Tecnologias:** C++, PlatformIO, Arduino-LMIC, ESP-IDF.

### [UGV SysML v2](https://github.com/josescobedov/UGV-sysml-)
Modelado formal y modular de ingenieria de sistemas para Vehiculos Terrestres No Tripulados (UGV) pesados de doble traccion adaptado a requerimientos tecnicos reales bajo el nuevo estandar SysML v2.

---

## Tecnologias y Herramientas

| Categoria | Tecnologias |
| :--- | :--- |
| **Lenguajes** | C, C++, Kotlin, Python, JavaScript, HTML5 / CSS3 |
| **Hardware y Embebidos** | ESP32, LoRa / LoRaWAN, PlatformIO, MPLAB X (PIC), Quartus II (FPGA), Arduino |
| **Ingenieria y Sistemas** | SysML v2, ROS, Control Automatico, Instrumentacion Electronica |
| **Entornos y Herramientas** | Android Studio, Git, Linux / Bash, VS Code |

---

## Metricas de GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=josescobedov&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estadisticas de GitHub" width="48%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=josescobedov&layout=compact&theme=tokyonight&hide_border=true" alt="Lenguajes mas utilizados" width="44%">
</div>

---

## Contacto y Enlaces

- **GitHub:** [github.com/josescobedov](https://github.com/josescobedov)
- **Localizacion:** Asturias, Espana
