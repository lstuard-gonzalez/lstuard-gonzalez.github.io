# lstuard-gonzalez.github.io

Sitio de soporte (gratis, en GitHub Pages) para la app **yt2tok**.

Sirve para dos cosas del login de TikTok:

1. **Verificar el dominio** ante TikTok Developers.
2. **Recibir el regreso del login** en `/tiktok/callback` y mostrar el código
   para pegarlo en la app.

## Estructura
- `index.html` — portada simple.
- `tiktok/callback/index.html` — muestra el `code` que devuelve TikTok.
- `tiktokXXXXXXXX.txt` — (lo agregas tú) archivo de verificación que te da TikTok.
- `.well-known/assetlinks.json` — (opcional, más adelante) para reapertura
  automática de la app por App Links.

## Cómo publicarlo
1. Crea en GitHub un repositorio **público** llamado exactamente
   `lstuard-gonzalez.github.io`.
2. Sube estos archivos.
3. En el repo: **Settings → Pages → Build and deployment → Source: Deploy from a
   branch → Branch: main / root → Save**.
4. En 1–2 minutos queda vivo en `https://lstuard-gonzalez.github.io`.