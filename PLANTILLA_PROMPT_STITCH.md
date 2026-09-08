# Plantilla de Prompt para Google Stitch — BluePeak Digital

Copia todo el bloque de abajo, reemplaza los textos entre `[CORCHETES]` con la información del cliente/negocio, borra las líneas que no apliquen, y pega el resultado completo en Google Stitch.

---

```
Diseña una landing page [moderna y dinámica / corporativa y seria — elige una] para "[NOMBRE DEL NEGOCIO]", un negocio de [GIRO DEL NEGOCIO, ej. "plomería y electricidad", "consultorio dental", "taller mecánico"] que opera en [ZONA/CIUDAD, ej. "Puebla y Cholula, México"].

CONTEXTO DEL NEGOCIO
[NOMBRE DEL NEGOCIO] atiende a [PERFIL DE CLIENTE, ej. "dueños de casa y negocios locales que necesitan un servicio confiable y rápido"]. El problema principal que resuelve es: [PROBLEMA/DOLOR DEL CLIENTE, ej. "la gente no encuentra el negocio en internet y se va con la competencia"].

Los servicios o productos principales son:
1. [SERVICIO 1] — [breve descripción y beneficio]
2. [SERVICIO 2] — [breve descripción y beneficio]
3. [SERVICIO 3] — [breve descripción y beneficio]

Diferenciador clave: [QUÉ HACE DIFERENTE A ESTE NEGOCIO de la competencia].

CANAL DE CONTACTO
Todo el contacto del sitio es exclusivamente por [WhatsApp / teléfono / formulario — elige uno o combina]. Número: [+52 XXX XXX XXXX]. Todos los botones de contacto deben enlazar a https://wa.me/[NÚMERO SIN ESPACIOS NI SIGNOS] con un mensaje predefinido según el contexto (ej. "Hola, quiero información sobre [SERVICIO]").
[Si NO se usa WhatsApp: indicar aquí "NO incluir botones de WhatsApp, usar botón de llamada a [TELÉFONO] y/o formulario de contacto".]

IDENTIDAD DE MARCA
- Logo: [describir el logo — colores, forma, isotipo. Adjuntar la imagen del logo como referencia de estilo en Stitch].
- Personalidad de marca: [3-5 adjetivos, ej. "confiable, moderna, cercana, profesional"].
- Estilo visual: [ej. "premium y minimalista" / "cálido y accesible" / "técnico e industrial"] — lenguaje directo en español [de México / neutro], sin jerga complicada.

PALETA DE COLORES
- Primario: [HEX] — [uso: headers, botones principales, texto de marca]
- Secundario / acento: [HEX] — [uso: CTAs, iconos, elementos interactivos]
- Color funcional de conversión (si aplica WhatsApp): Verde WhatsApp #22C55E — reservado solo para botones de WhatsApp.
- Fondo base: [HEX, ej. blanco o gris muy claro] — tarjetas en blanco puro con sombras suaves.
- Texto: [HEX oscuro de alto contraste].

TIPOGRAFÍA
- Encabezados: [FUENTE, ej. "Inter ExtraBold / Plus Jakarta Sans"], pesos 700-800.
- Cuerpo de texto: [FUENTE, ej. "Inter Regular"], line-height generoso (1.5-1.6).
- Etiquetas/badges: uppercase, bold, tracking amplio.

ESTRUCTURA DE SECCIONES
1. HEADER — Logo + menú (Inicio, Servicios, [Nosotros/Casos de Éxito], Precios, Contacto) + botón CTA visible.
2. HERO — Titular con gancho de dolor + solución. Subtítulo explicando la propuesta de valor. CTA primario (acción principal) y CTA secundario (scroll a más info). Elemento visual: [foto/mockup/ilustración relevante al negocio].
3. PROBLEMA/DOLOR (opcional, recomendado) — 3 tarjetas cortas con los dolores principales del cliente objetivo.
4. SERVICIOS — [N] tarjetas con ícono, descripción breve y beneficio cuantificable si es posible (ej. "+30% más citas agendadas").
5. CÓMO FUNCIONA — Proceso en 3-4 pasos numerados de principio a fin del servicio.
6. CASO DE ÉXITO / PORTAFOLIO — Si hay trabajos previos reales, mostrarlos con foto/resultado concreto. Si NO hay casos aún, omitir esta sección por completo (NO dejar un espacio vacío o de relleno genérico).
7. PRECIOS — [Plan único / Varios planes / Modelo híbrido con pago inicial + mensualidad]. Ser transparente, sin letras chiquitas.
8. TESTIMONIOS — Solo si son reales y verificables. Si no hay testimonios reales todavía, omitir esta sección (NO inventar clientes ni citas falsas).
9. PREGUNTAS FRECUENTES — 4-6 preguntas reales que los clientes suelen hacer antes de contratar.
10. CTA FINAL — Banner de alto contraste con la llamada a la acción principal repetida.
11. FOOTER — Logo, descripción corta, zona de cobertura, datos de contacto, redes sociales, aviso de privacidad.

REQUISITOS TÉCNICOS (OBLIGATORIO — no omitir)
- El diseño debe verse y funcionar perfecto TANTO en celular COMO en computadora de escritorio: usar breakpoints responsivos (mobile-first, con versión de escritorio centrada/ampliada, navegación de escritorio horizontal en vez de menú hamburguesa, tarjetas en grid de 2-3 columnas en pantallas grandes).
- Absolutamente TODOS los botones y enlaces deben tener una acción real (enlace de WhatsApp, ancla a sección, mailto, tel) — cero botones o íconos decorativos sin función.
- Botón flotante de contacto fijo visible en todas las secciones (si aplica WhatsApp).
- Botones con alto contraste y tamaño táctil mínimo de 44-48px de alto.
- Usar solo imágenes reales del negocio si están disponibles; si no, usar fotografía genérica de stock libre de derechos (no imágenes con marcas de agua ni de origen dudoso).
- Iconografía consistente en un solo estilo, esquinas redondeadas suaves.
- Ningún texto de relleno tipo "lorem ipsum" ni secciones a medio terminar.
```

---

## Notas de uso (no forman parte del prompt — son para ti)

- **Antes de pegar en Stitch:** llena todos los `[CORCHETES]`. Entre más específico seas (nombre real, colores en HEX, número de WhatsApp real, servicios reales), mejor sale el resultado — evita dejar placeholders genéricos.
- **Casos de Éxito / Testimonios:** solo inclúyelos si el cliente ya tiene trabajos reales o reseñas reales. Dejarle a Stitch inventar contenido falso (testimonios, cifras, nombres de clientes) genera un sitio poco creíble y puede meter al cliente en problemas legales por publicidad engañosa.
- **Después de que Stitch genere el código:** pásamelo (el HTML y el DESIGN.md si lo da) y yo hago la revisión técnica completa — corrijo botones que no funcionen, ajusto la paleta a los valores exactos del manual de marca del cliente si lo tiene, pruebo en móvil y escritorio, y lo publico en GitHub + Vercel igual que hicimos con Servicio Eléctrico Espinosa y contigo mismo.
- **Si el cliente tiene su propio manual de marca (PDF, moodboard, guía de estilo):** dímelo antes de generar el prompt — extraigo los colores oficiales, tipografía y reglas de logo para meterlos directo en la sección de IDENTIDAD DE MARCA / PALETA DE COLORES / TIPOGRAFÍA en vez de dejarlo genérico.
