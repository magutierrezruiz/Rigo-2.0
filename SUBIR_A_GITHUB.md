# Crear un repositorio nuevo y compilar

1. Crea un repositorio nuevo y vacío en GitHub.
2. Descomprime este ZIP.
3. Sube **todos los archivos y carpetas que están dentro de la carpeta descomprimida** a la raíz del repositorio.
4. Comprueba en GitHub que `codemagic.yaml`, `build.gradle`, `settings.gradle` y la carpeta `app` aparezcan directamente en la página principal del repositorio; no deben quedar dentro de una subcarpeta adicional.
5. Conecta ese repositorio nuevo a Codemagic.
6. Selecciona el workflow **AlgebrAventura 2.0 FIX3 - sin Gradle Wrapper**.
7. Ejecuta el build.
8. Cuando termine correctamente, descarga `app-debug.apk` desde Artifacts.

Si Codemagic muestra un workflow llamado `AlgebrAventura APK Debug` o un paso llamado `Verificar Gradle`, está leyendo otro `codemagic.yaml` y no este paquete.
