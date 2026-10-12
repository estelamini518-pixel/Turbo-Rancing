# Turbo Racing: Carrera Extrema

Videojuego móvil inspirado en la propuesta del proyecto Turbo Racing. Esta primera versión incluye:
- Menú de inicio y pantalla de carrera.
- Pista con perspectiva visual, automóvil deportivo dibujado en pantalla y obstáculos.
- Controles táctiles para girar, acelerar y frenar.
- Nitro con barra de energía.
- Velocidad, cronómetro, puntuación, pausa y meta.
- Workflow de GitHub Actions para generar el APK de Android.

## Crear el APK con GitHub
1. Crea un repositorio en GitHub llamado `Turbo-Racing`.
2. Sube **todo el contenido** de esta carpeta, incluyendo la carpeta oculta `.github`.
3. Abre la pestaña **Actions** y selecciona **Build Turbo Racing APK**.
4. Pulsa **Run workflow** si no se ejecutó automáticamente.
5. Cuando termine en verde, entra a la ejecución y descarga el artefacto **Turbo-Racing-APK**.
6. Descomprime el artefacto descargado: dentro estará `app-release.apk`.
7. Pasa el APK a tu teléfono Android e instálalo. Es posible que Android solicite permitir instalaciones desde esa fuente.

## Importante
- El juego es una primera versión jugable con perspectiva 2D simulando una pista de carreras; no es todavía un modelo 3D real de Unity.
- La compilación Android se genera en GitHub Actions; no se incluye un APK precompilado en este ZIP.
- No elimines `.github/workflows/build-apk.yml`; es el archivo que automatiza la compilación.
