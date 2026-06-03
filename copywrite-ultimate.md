# COPYWRITE ULTIMATE — Univers Landing

---

## Datos Generales

- **Brand**: Univers
- **Product**: Ecosistema de agentes de IA multicanal y automatización para PyMEs.
- **Tagline**: "Tu equipo de soporte y ventas, potenciado por IA 24/7."
- **Audience**: Dueños de PyMEs, emprendedores y equipos de ventas que pierden clientes por respuestas tardías en WhatsApp/Instagram o están ahogados en tareas repetitivas.
- **Tono**: Profesional pero cercano, empático con el caos operativo, directo y con urgencia constructiva. (Se mantiene el voseo profesional para cercanía: "tu negocio", "programás").
- **Color de marca**: Púrpura (#5d5fef) + Rosa claro (#edb1ff)

---

## NAVEGACIÓN

### Nav Fija (estática)
```
Univers | Agentes | Precios | Casos de Éxito | Docs | [Agendar Demo]
```
- Logo U + "UNIVERS" tracking 0.25em
- Links: uppercase, tracking wider, bold
- CTA: rounded-full con glow animado

### Nav Flotante (aparece al scroll)
```
[U] | Agentes | Precios | Casos de Éxito | [Agendar Demo]
```
- Compacta, glassmorphism, rounded-full
- Logo solo (sin texto "UNIVERS")
- Misma CTA pero más pequeña

### Mobile Drawer
- Full-screen overlay oscuro
- Links uppercase con borde inferior
- Botón cerrar (✕) arriba derecha

---

## HERO SECTION

### Headline (3 opciones — elegir la que mejor resuene con el tráfico principal)

**Opción 1 (Enfoque en el dolor principal):**
```
DEJA DE PERDER VENTAS POR RESPONDER TARDE.
```

**Opción 2 (Enfoque en la solución multicanal):**
```
TU ATENCIÓN AL CLIENTE Y VENTAS, AUTOMATIZADAS 24/7.
```

**Opción 3 (Enfoque en la tecnología/confianza):**
```
AGENTES DE IA QUE SÍ ENTIENDEN TU NEGOCIO. SIN ALUCINACIONES.
```

- Font: Sora, 160px desktop / 15vw mobile
- Weight: Extrabold
- Tracking: -0.04em (tight)
- Color: white con glow animado
- Efecto: blur-word reveal animado

### Subtítulo / Descriptor
```
Conectamos WhatsApp, Instagram, Facebook y Telegram con un agente de IA entrenado exclusivamente con tus datos. Responde, agenda y vende en segundos, con la precisión de un sistema robusto y la empatía de tu mejor empleado.
```
- Font: Hanken Grotesk, 1.5rem
- Color: white/90
- Width: max-w-xl
- Align: center desktop / left mobile

### CTAs del Hero
```
[Ver cómo funciona]        [Agendar mi Demo Gratuita]
```
- Secondary: border-2 white/30, backdrop-blur
- Primary: `bg-primary-container` rounded-full, px-10 py-4, shadow, glow pulsante

### Visual del Hero
- Sprite animado del robot (canvas, 36 frames, loop: animate → 5s pause → repeat)
- Contenedor: 500px mobile / 750px desktop altura
- Glow effect púrpura en el robot
- Mockup blanco superpuesto a la derecha mostrando un chat de WhatsApp siendo respondido instantáneamente

---

## TRANSITION SECTION

### Copy
```
Cada minuto que tu equipo pasa respondiendo las mismas preguntas...
ESTÁS PERDIENDO VENTAS Y DEJANDO CLIENTES PARA LA COMPETENCIA.
```
- Primera línea: white/60, 1.25rem
- Segunda línea: white, 3.5rem, uppercase
- Palabra "perdiendo" en rojo con pulse animation + text-shadow glow

---

## THE CAPSULE — CAOS (Sección Problema)

### Badge
```
Para negocios que crecen, pero su atención al cliente no...
```

### Headline
```
TU OPERACIÓN ESTÁ COLAPSANDO SIN AUTOMATIZACIÓN
```
- Font: Sora, black, uppercase
- Tamaño: 7xl desktop / 4xl mobile

### Stats Card
```
42%
de tus clientes abandonan el chat si no hay respuesta en los primeros 2 minutos.
```
- Número: 4xl, red-500, animate-pulse, glow
- Texto: muted, font-medium

### Visual: Video smartphone
- Overflow hidden, rounded-4xl, shadow-xl
- Video: notificaciones de WhatsApp e Instagram explotando en la pantalla
- Badge animado: "⚠️ 99+ mensajes sin responder"

---

## THE CAPSULE — PAZ (Sección Solución)

### Badge
```
Mensajes contestados, citas agendadas, mente tranquila.
```
- bg-green-500/10, text-green-400, border-green-500/20

### Headline
```
0 MENSAJES SIN RESPONDER. 100% CONFIABLE.
```
- Font: Sora, black, uppercase, 7xl

### Stats Card
```
Cero Alucinaciones
Gracias a nuestra tecnología RAG y base de datos SQL, el agente solo usa la información real de tu negocio.
```
- Número/Texto destacado: green-400, bold

### CTA
```
[Quiero esta tranquilidad para mi negocio →]
```
- bg-primary-container, rounded-full, px-10 py-5

### Visual: Video robot trabajando
- Sprite animado "working" en la esquina inferior
- Video con checks verdes apareciendo sobre mensajes de chat

---

## SERVICIOS (4 Cards)

### Badge
```
Nuestro Expertise
```

### Headline
```
TODO LO QUE NECESITAS PARA ESCALAR SIN CONTRATAR MÁS PERSONAL
```

### Card 1 — Agentes Multicanal 24/7
- Icono: support_agent (Material Symbols)
- Título: "Agentes Multicanal 24/7"
- Subtítulo: "Atención que no duerme."
- Descripción: "Soporte en WhatsApp, Instagram, Facebook y Telegram que resuelve dudas, filtra leads y deriva a humanos solo cuando es estrictamente necesario."
- Fondo: púrpura (#5d5fef)
- Hover: border white + scale + shadow

### Card 2 — Agentes de Citas y Agendas
- Icono: event_available
- Título: "Agentes de Citas y Agendas"
- Subtítulo: "Tu calendario, en piloto automático."
- Descripción: "Sincronización total para agendar, reprogramar y enviar recordatorios de reuniones sin que tú muevas un dedo."

### Card 3 — Automatizaciones a Medida
- Icono: settings_suggest
- Título: "Automatizaciones a Medida"
- Subtítulo: "Adiós a las tareas repetitivas."
- Descripción: "Diseñamos flujos de trabajo que conectan tus herramientas actuales (CRM, hojas de cálculo) con el poder de la IA."

### Card 4 — Consultoría Estratégica Honesta
- Icono: psychology
- Título: "Consultoría Estratégica Honesta"
- Subtítulo: "Claridad antes que tecnología."
- Descripción: "Analizamos tu modelo de negocio para decirte exactamente *donde* la IA te ahorrara dinero, y donde no la necesitas."

### Sprite flotante
- Robot "peeking" animado sobre la sección (192×192)
- Ciclo: animate 6 frames → pause 5s → repeat

---

## MARQUEE DE INTEGRACIONES

### Título
```
Se conecta con las herramientas que ya usás
```

### Iconos (animación marquee, loop infinito, grayscale a color al hover)
- WhatsApp, Instagram, Facebook, Telegram, Chatwoot, n8n, Baserow, Supabase
- Tamaño: h-10 (40px)
- Gap: 16px móvil / 24px desktop
- Velocidad: 20s linear infinite

---

## PASOS DEL PROCESO (4 pasos)

### Grid 4 columnas

**01 — Auditoría de Flujo**
> Mapeamos el "ADN" de tu marca y tus conversaciones actuales para identificar cuellos de botella.

**02 — Entrenamiento con Tus Datos**
> Alimentamos al agente con tu base de conocimientos, precios y catálogos. Nada genérico.

**03 — Despliegue Multicanal**
> Conectamos la IA a tu WhatsApp, redes y web en días, no en meses.

**04 — Optimización Continua**
> Monitoreamos las conversaciones para refinar el tono y aumentar tu tasa de conversión mes a mes.

- Números: 5xl, black/20 (muy sutil)
- Títulos: bold
- Descripciones: text-sm, black/60

---

## EDITORIAL SECTION

### Headline
```
NO ES UN BOT QUE PROGRAMÁS. ES UN COMPAÑERO QUE ENTRENÁS.
```

### Body copy
```
En la era de la IA, la ventaja competitiva no es tener la tecnología, sino saber integrarla a tu cultura. Univers no solo automatiza respuestas; aprende de tus mejores vendedores, replica tu tono de voz y, gracias a nuestra arquitectura robusta (RAG + SQL), garantiza que cada respuesta sea precisa y segura.
```

### Logo block
- Fondo negro, rounded-r-xl
- Logo "LOGO SIN LETRAS.png" centrado
- Offset negativo a la izquierda (-10%)

### CTA
```
[Ver cómo se entrena a tu agente →]
```

### Visual
- Imagen mockup editorial mostrando el panel de control o un chat fluido (rounded-5xl, shadow-3xl)
- Gradiente púrpura difuso detrás (blur-2xl)
- aspect-square

---

## SECCIÓN PRECIOS — Inversión en Crecimiento

### Plan Básico — $299/mes
- Para: Emprendedores y PyMEs en crecimiento
- Incluye:
  - ✓ 1 Agente de IA Multicanal
  - ✓ 1,000 conversaciones/mes
  - ✓ Integración WhatsApp e Instagram
  - ✓ Base de conocimientos personalizada
- CTA: [Elegir Plan Básico] (border outline)

### Plan Profesional — $599/mes ★ POPULAR
- Para: Equipos de ventas activos que necesitan escalar
- Incluye:
  - ✓ 3 Agentes Especializados (Ventas, Soporte, Citas)
  - ✓ 5,000 conversaciones/mes
  - ✓ Sincronización con CRM y Calendarios
  - ✓ Tecnología RAG avanzada (Cero alucinaciones)
  - ✓ Soporte Prioritario
- CTA: [Elegir Plan Profesional] (filled bg-primary-container, glow)
- Badge: "Más elegido" flotante arriba

### Plan Enterprise — A Medida
- Para: Operaciones que requieren escala masiva y seguridad dedicada
- Incluye:
  - ✓ Agentes Ilimitados
  - ✓ Infraestructura VPS dedicada
  - ✓ SLA de disponibilidad y Seguridad de datos
  - ✓ Consultoría de procesos avanzada
- CTA: [Contactar a Ventas] (border outline)

---

## SOCIAL PROOF

### Stats
```
+120h/mes
ahorradas en tareas administrativas por cada agente implementado.
```

### Logos (grayscale, opacity 50%, hover a color)
- Chatwoot, n8n, Contabo, Baserow, Supabase

### Testimonio Destacado
```
"Antes perdíamos ventas los fines de semana. Con Univers, el agente agenda citas en WhatsApp como si fuera nuestra mejor recepcionista, pero sin cometer errores con los horarios. La implementación fue rapidísima."
— Nombre, Cargo, Empresa (Agregar foto real)
```

### CTA
```
[Obtener Acceso a la Demo Beta]
```
- bg-white, text-background, rounded-full, px-8, shadow-lg

---

## FAQ — Preguntas Frecuentes

### Badge
(nada — solo headline)

### Headline
```
RESOLVEMOS TUS DUDAS
```

### Pregunta 1 (abierta por defecto)
```
¿Es difícil de configurar? ¿Necesito saber de programación?
```
> Para nada. Nuestro equipo se encarga de toda la implementación técnica. Vos solo nos compartís la información de tu negocio (PDFs, webs, manuales) y nosotros entrenamos y desplegamos el agente por vos.

### Pregunta 2
```
¿El agente suena como un robot o inventa cosas?
```
> Utilizamos modelos de lenguaje avanzados afinados con tu estilo de comunicación. Además, nuestra tecnología RAG (Retrieval-Augmented Generation) obliga al agente a responder *solo* con la información real de tu base de datos, eliminando las "alucinaciones" típicas de otras IAs.

### Pregunta 3
```
¿En qué canales puede atender mi negocio?
```
> Actualmente integramos WhatsApp, Instagram, Facebook y Telegram de forma nativa, unificando toda la atención en un solo cerebro digital.

### Pregunta 4
```
¿Puedo probarlo antes de comprometerme?
```
> Sí. Ofrecemos una consultoría inicial gratuita para evaluar tu caso, y una prueba de concepto de 14 días con las funcionalidades del plan Profesional. Sin necesidad de tarjeta de crédito.

### Diseño FAQ
- Border: outline/10
- Rounded: 2xl
- Summary: bold, cursor-pointer, bg-white
- Body: text-sm, text-on-surface-variant
- Arrow: rotate 180° cuando está open

---

## MODAL — Agendar Demo

### Título
```
Agendá tu Demo Personalizada
```

### Descripción
```
Completá el formulario y te mostraremos en vivo cómo un agente de IA entrenado con *tus* datos puede transformar la atención de tu negocio.
```

### Campos del formulario
1. Nombre completo (text, required)
2. Email corporativo (email, required)
3. Nombre de tu Empresa (text, required)
4. ¿Cuál es tu mayor dolor hoy? (select: "Responder tarde", "Tareas repetitivas", "No sé por dónde empezar", required)

### Submit
```
[Enviar solicitud de Demo]
```

### Estado éxito
```
¡Solicitud enviada!
Gracias por tu interés. Nuestro equipo te contactará en las próximas 24 horas hábiles para coordinar la demostración.
```

---

## FOOTER

```
© 2024 Univers. Todos los derechos reservados.
[Política de Privacidad] | [Términos y Condiciones]
```
- Iconos de redes sociales (minimalistas)

---

## ELEMENTOS ANIMADOS (Mantener especificaciones técnicas)

| Elemento | Animación |
|---|---|
| Hero headline | blurReveal — blur 20px → 0, 1.2s |
| Números (42%, etc.) | pulse + text-shadow glow |
| Badge "99+ mensajes" | bounce animation |
| Sprite astronaut (hero) | animate 36 frames → 5s pause → loop |
| CTA buttons | glow pulsante 3s |
| Nav flotante | slideDown 0.5s cubic-bezier |
| Scroll reveal | opacity 0 → 1 (fade-up) |
| Marquee integraciones | translateX(0) → translateX(-50%) 20s linear infinite |

---

## FUENTE TIPOGRÁFICA

| Uso | Font | Weight |
|---|---|---|
| Headlines | Sora | 800 (black) |
| Body | Hanken Grotesk | 400 / 600 |
| Mono / Labels | Material Symbols Outlined | 400 |

---

## PALETA DE COLORES (CSS variables)

```css
--bg:           oklch(98% 0.004 240)
--surface:       oklch(100% 0 0)
--fg:            oklch(20% 0.02 240)
--muted:         oklch(50% 0.018 240)
--border:        oklch(90% 0.006 240)
--accent:        oklch(56% 0.12 170)

primary-container:  #5d5fef
primary:           #c1c1ff
on-primary:         #1200a9

error:             #ffb4ab
error-container:   #93000a

surface-container-low:   #191c1f
surface-container-high:  #282a2e
surface-container:       #1d2023

tertiary:         #edb1ff
```

---

## BACKGROUND DEL BODY

```css
background-color: #6a4c93;  /* púrpura medio */
background-image:
  radial-gradient(circle, rgba(255,255,255,0.20) 1.2px, transparent 1.2px),  /* dot grid */
  linear-gradient(180deg, #1a1c5e 0%, #6a4c93 50%, #9b8ec4 100%);  /* indigo → púrpura → lavanda */
background-size: 24px 24px, 100% 100%;
background-attachment: fixed, fixed;
```

---

## CTA PRINCIPALES

| Ubicación | Texto | Estilo |
|---|---|---|
| Nav | Agendar Demo | bg-primary-container, rounded-full, glow |
| Hero | Agendar mi Demo Gratuita | filled primary, glow pulsante |
| Hero | Ver cómo funciona | ghost (border only) |
| Paz | Quiero esta tranquilidad para mi negocio → | filled primary |
| Editorial | Ver cómo se entrena a tu agente → | filled primary |
| Social proof | Obtener Acceso a la Demo Beta | bg-white, text dark |
| Modal submit | Enviar solicitud de Demo | bg-primary-container |

---

## NOTAS DE VOZ Y TONO

- **Voseo profesional**: "tu negocio", "vos", "programás" — cercanía sin perder formalidad
- **Urgencia constructiva**: El problema (caos) y la solución (paz) contrasted strong
- **Tecnología RAG como diferenciador**: "Cero Alucinaciones" como beneficio claro
- **No hay lorem ipsum**: Todo el copy es real y específico del producto
- **Copy directo**: Sin redundancias, sin jerga innecesaria
- **CTA con dirección**: "→" indica acción, no solo botón

---

## PLACEHOLDERS PARA REEMPLAZAR

| Placeholder | Descripción |
|---|---|
| `<!-- REPLACE: Tu isotype real -->` | Logo PNG en nav |
| `<!-- REPLACE: Imagen smartphone con notificaciones -->` | Video CAOS |
| `<!-- REPLACE: Imagen del robot/IA en paz -->` | Video PAZ |
| `<!-- REPLACE: Isotype small -->` | Logo editorial section |
| `<!-- REPLACE: Imagen editorial mockup -->` | Imagen editorial |
| `<!-- REPLACE: Logos de integraciones como imágenes -->` | Logos social proof |

---

## METADATA SEO

```html
<title>Univers - Agentes de IA para Ventas</title>
<meta name="description" content="Univers es un ecosistema de agentes de IA diseñados para escalar tu equipo de ventas sin límites. Automatización omnicanal 24/7 para WhatsApp, Instagram y Facebook.">
<meta property="og:title" content="Univers — Agentes de IA para Ventas">
<meta property="og:description" content="Univers es un ecosistema de agentes de IA diseñados para escalar tu equipo de ventas sin límites.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://univers.ai">
<meta property="og:image" content="sprites/Logo univers sin fondo.png">
<link rel="canonical" href="https://univers.ai/">
```

---

*Documento copywrite ultimate — Versión 2.0 — Junio 2026*
*Actualización con enfoque CRO, RAG como diferenciador, y voseo profesional*