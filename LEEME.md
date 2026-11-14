# Gatas Guerreras: proyecto Android

App Android mínima que muestra el juego (`app/src/main/assets/index.html`) a pantalla completa y en horizontal.
No usa Capacitor ni npm.

## Opción A: crear el APK en la nube con GitHub (sirve desde el teléfono)

1. Crea una cuenta gratis en github.com y un repositorio nuevo, por ejemplo `gatas-guerreras`.
2. Sube TODO el contenido de esta carpeta al repositorio, en la rama `main`
   (incluida la carpeta oculta `.github`).
3. Abre la pestaña **Actions**. La tarea "Crear APK" arranca sola y tarda unos minutos.
4. Cuando termine en verde, abre **Releases** y descarga `GatasGuerreras.apk`.
5. Ábrelo en tu Android y permite "instalar apps desconocidas".

## Opción B: con Android Studio en un computador

1. Abre esta carpeta con Android Studio (File → Open) y espera la sincronización.
2. Build → Build Bundle(s) / APK(s) → Build APK(s).
3. El archivo queda en `app/build/outputs/apk/debug/app-debug.apk`.

## Cambiar el juego

Reemplaza `app/src/main/assets/index.html` por la versión nueva y vuelve a compilar.
