# Códigos de error Samsung (Redsa Service)

App Android sin internet: abre `app/src/main/assets/index.html` dentro de un WebView.

## Cómo obtener el APK

### Opción A · Android Studio (en una computadora)
1. Instala Android Studio (gratis): https://developer.android.com/studio
2. `File → Open` y elige esta carpeta. Espera a que termine el «Gradle Sync».
3. Menú `Build → Build Bundle(s) / APK(s) → Build APK(s)`.
4. El APK queda en `app/build/outputs/apk/debug/app-debug.apk`. Pásalo al celular e instálalo (permite «instalar apps de origen desconocido»).

### Opción B · GitHub (sin instalar nada)
1. Crea una cuenta gratis en https://github.com y un repositorio nuevo (privado si quieres).
2. Sube todo el contenido de esta carpeta (incluida la carpeta oculta `.github`).
3. Entra a la pestaña `Actions` → «Compilar APK» → espera unos minutos.
4. Abre la ejecución terminada y descarga el artefacto `Codigos-de-error-Samsung-APK` (zip con el .apk dentro).

## Cambiar el contenido
Edita `app/src/main/assets/index.html` (los datos están en `CATS`, `CODES` y `LED`).
