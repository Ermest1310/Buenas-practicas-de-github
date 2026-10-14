
# EyePilot - Control de silla de ruedas inalámbrica

Aplicación Android en Kotlin para controlar una silla de ruedas por Bluetooth,
mediante un joystick en pantalla o el seguimiento ocular con la cámara.

## Funcionalidades

- Control con joystick táctil
- Control ocular (detección facial con MediaPipe Face Landmarker)
- Calibración ocular
- Comunicación Bluetooth con el microcontrolador de la silla

## Tecnologías

- Kotlin, Android Studio, Gradle (Kotlin DSL)
- MediaPipe Face Landmarker
- Arduino (código `.ino` del controlador)
- Proteus (simulación del circuito)

## Estructura del repositorio

- `app/`: código fuente de la aplicación Android
- `gradle/`: configuración de Gradle
- `Proyecto_Silla_de_ruedas_inalambrico/`: código Arduino, circuito y app Joystick (MIT App Inventor)

## Cómo ejecutar la app

1. Clonar el repositorio
2. Abrir la carpeta en Android Studio
3. Esperar la sincronización de Gradle
4. Ejecutar en un dispositivo Android (se necesita Bluetooth y cámara)

## Equipo

- Nombre 1
- Nombre 2
