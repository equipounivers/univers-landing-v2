# Univers Landing v2

Landing page oficial de **Univers** — ecosistema de agentes de IA para escalar equipos de ventas y soporte.

## Stack

- **HTML estático** + **Tailwind CSS** (CDN)
- **Google Fonts**: Sora (headlines) + Hanken Grotesk (body)
- **GSAP** + **ScrollTrigger** (animaciones premium)
- **Locomotive Scroll** (smooth scroll)
- **Canvas sprites** (animaciones de robot)

Sin build step, sin dependencias de Node, todo en CDN.

## Estructura

```
.
├── index.html              # Landing principal
├── privacidad.html          # Política de Privacidad
├── terminos.html            # Términos y Condiciones
├── cookies.html             # Política de Cookies
├── seguridad.html           # Política de Seguridad
├── sprites/                 # Imágenes y sprites (logos, mockups, fondos)
├── iconos/                  # SVGs para el marquee (integraciones)
├── netlify.toml             # Configuración de Netlify
├── copywrite.md             # Copy original
├── copywrite-ultimate.md    # Copy optimizado para CRO (versión aplicada)
└── limpieza/                # Archivos experimentales (borrar manualmente)
```

## Deploy en Netlify

### Setup inicial

1. **Crear cuenta en [netlify.com](https://netlify.com)** (gratis)
2. **New site from Git** → conectar con GitHub
3. **Seleccionar repo**: `equipounivers/univers-landing-v2`
4. **Build settings**:
   - Build command: *(dejar vacío)*
   - Publish directory: `/` (raíz)
5. **Deploy site** → te da una URL temporal tipo `univers-landing.netlify.app`

### Dominio custom (univers.ai)

1. En Netlify: **Site settings → Domain management → Add custom domain**
2. Ingresar `univers.ai`
3. Configurar DNS en tu registrador:
   - Para apex (`univers.ai`): `A` records a `75.2.60.5` (Netlify load balancer)
   - Para `www`: `CNAME` a `[tu-sitio].netlify.app`
4. Netlify provisiona **SSL automático** (Let's Encrypt)

### Deploy continuo

Una vez configurado, **cada `git push` a `main` se deploya automáticamente**.

## Edits locales

1. Clonar el repo
2. Abrir `index.html` en cualquier navegador (no necesita servidor)
3. Hacer cambios
4. Hard refresh (`Ctrl + Shift + R`) para limpiar caché

## Stack técnico del frontend

| Recurso | Uso |
|---|---|
| Tailwind CSS (CDN) | Estilos utility-first |
| Google Fonts | Sora + Hanken Grotesk |
| GSAP + ScrollTrigger | Animaciones de scroll |
| Locomotive Scroll | Smooth scroll |
| Canvas API | Sprites del robot (sin librerías externas) |
| Material Symbols | Iconos |

## Páginas legales

Las 4 páginas (`privacidad.html`, `terminos.html`, `cookies.html`, `seguridad.html`) comparten el diseño visual de la landing:

- Glassmorphism en nav
- Card blanca con TOC sobre fondo púrpura con dot grid
- Footer con links cruzados a las 4 páginas

> ⚠️ **Importante**: Aunque el template está bien redactado, **recomendamos revisión legal profesional** antes de salir a producción. Las leyes varían por país.

## Seguridad

- HTTPS automático (Netlify + Let's Encrypt)
- Headers de seguridad configurados en `netlify.toml`
- Reporte de vulnerabilidades: `security@univers.ai`

## Contacto

- **General**: hola@univers.ai
- **Privacidad**: privacidad@univers.ai
- **Seguridad**: security@univers.ai
- **Legal**: legal@univers.ai
