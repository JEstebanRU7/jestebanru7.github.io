# Web del desarrollador — https://jestebanru7.github.io

Página de contacto de la ficha de Google Play ("Sitio web") y sitio de
`app-ads.txt`. Se publica con GitHub Pages desde un repositorio público llamado
exactamente `jestebanru7.github.io` (sitio de usuario: sirve la RAÍZ del dominio;
el repo `privacy` sirve `/privacy/`, que es la política de privacidad).

Archivos (subir TODOS a la raíz de ese repo, sin carpetas):

| Archivo | Para qué |
|---|---|
| `index.html` | Portada: app, Google Play, canal de YouTube, contacto, enlace a la política. Español/inglés (elige según el idioma del navegador). |
| `icon.webp`, `banner.webp`, `favicon.png`, `apple-touch-icon.png` | Imágenes de la portada (salen de `store/googleplay-icon-512.png` y `store/googleplay-feature-1024x500.png`). |
| `app-ads.txt` | AdMob lo busca en `https://jestebanru7.github.io/app-ads.txt` para confirmar que los anuncios son legítimos (editor `pub-3023936509946450`). |

Pasos:
1. Repo `jestebanru7.github.io` → Add file → Upload files → arrastrar los 6 archivos → Commit changes.
2. (Si hiciera falta) pestaña Settings DEL REPO → Pages → Deploy from a branch, `main`, `/ (root)`.
3. Play Console → Ficha de Play Store → Datos de contacto → Sitio web: `https://jestebanru7.github.io`.
4. AdMob → Apps → app-ads.txt → "Comprobar si hay actualizaciones" (tarda hasta 24 h).

El botón de Google Play enlaza a la ficha pública
(`play.google.com/store/apps/details?id=com.jestebanru.germanwithesteban`); mientras
la app solo esté en prueba cerrada, a quien no sea tester le dirá que no la encuentra.
