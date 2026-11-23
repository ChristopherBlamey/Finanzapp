# Finanzas

App web para cargar cartolas bancarias en PDF y ver en qué se gasta. Funciona en iPhone y PC, se instala como app y trabaja sin conexión.

**Privacidad:** cada persona ve solo sus propios datos. Las cartolas se leen dentro del navegador de quien usa la app y quedan guardadas en ese equipo. El sitio solo entrega el código; no recibe ni guarda información.

## Publicar en GitHub Pages (gratis)

1. En GitHub, crea un repositorio nuevo, por ejemplo `finanzas`.
2. Sube todo el contenido de esta carpeta a la raíz del repositorio (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/` y `vendor/`).
3. En el repositorio, entra a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/finanzas/`.

En el plan gratuito de GitHub, Pages requiere un repositorio público. El código no contiene datos de nadie.

**Opcional, dominio propio** (por ejemplo `finanzas.smartap.cl`): en Settings → Pages escribe el dominio en *Custom domain*, y en tu proveedor de DNS crea un registro `CNAME` de `finanzas` apuntando a `TU-USUARIO.github.io`.

## Instalar

- **iPhone:** abre el enlace en Safari → Compartir → **Agregar a inicio**.
- **PC:** abre el enlace en Chrome o Edge → ícono **Instalar** en la barra de direcciones.

## Actualizar la app

Reemplaza `index.html` en el repositorio y cambia `VERSION` en `sw.js` (por ejemplo, `finanzas-1.0.1`). Al abrir la app con conexión, toma la versión nueva. Los datos de cada persona no se tocan.

## Pasar datos entre equipos

Ajustes → **Exportar respaldo** en un equipo, y **Importar respaldo** en el otro. La importación combina sin duplicar.
