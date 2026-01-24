# Crisutf URL Shortener

Un acortador de enlaces minimalista, rápido y elegante, controlado totalmente por un archivo JSON. Sin bases de datos, sin backend complejo.

## Características

- 🚀 **Ultrarrápido**: Redirección instantánea desde el cliente.
- 🎨 **Diseño Premium**: Estilo "Midnight Blue" minimalista (Apple Dark Mode).
- ⚙️ **Configuración Fácil**: Solo edita `links.json`.
- 📱 **Responsive**: Se ve genial en móviles y escritorio.

## Cómo Usar

### 1. Agregar Enlaces
Edita el archivo `links.json` para agregar tus atajos:

```json
{
  "google": "https://www.google.com",
  "portfolio": "https://crisutf.pages.dev",
  "redes": "https://instagram.com/tu_usuario"
}
```

### 2. Crear Enlaces Cortos
Para usar un enlace corto, simplemente añade `?d=NOMBRE` a tu URL base.

**Ejemplo:**
Si tu sitio está en `crisutf.pages.dev`, entonces:
- `crisutf.pages.dev/?d=google` -> Te lleva a Google.
- `crisutf.pages.dev/?d=portfolio` -> Te lleva a tu portafolio.

### 3. Página de Inicio
Si alguien entra sin un código (solo `crisutf.pages.dev`), verá una elegante página de bienvenida.

## Instalación

Simplemente sube estos archivos a cualquier hosting estático:
- GitHub Pages
- Cloudflare Pages
- Vercel
- Netlify

No se requiere configuración de servidor.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
