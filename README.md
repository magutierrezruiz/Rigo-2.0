# AlgebrAventura 2.0

Videojuego educativo para Android dirigido a grado octavo.

## Contenido
- 13 retos.
- 20 ejercicios posibles por reto.
- 260 ejercicios en el banco total.
- Selección aleatoria de un ejercicio por reto en cada partida.
- Opciones de respuesta mezcladas aleatoriamente.
- 3 vidas y 100 puntos por acierto.
- Reto 13: cubo de un binomio, con suma y diferencia.

## Compilación en Codemagic
Este repositorio incluye `codemagic.yaml` en la raíz. El workflow no depende del Gradle Wrapper del repositorio: descarga Gradle 6.1.1 y ejecuta `clean assembleDebug`.

El APK generado se publica como artefacto desde:

`app/build/outputs/apk/debug/app-debug.apk`

## Configuración Android
- Java 8
- Android Gradle Plugin 4.0.2
- Gradle 6.1.1
- compileSdkVersion 29
- targetSdkVersion 29
- minSdkVersion 21
- versionCode 2
- versionName 2.0
