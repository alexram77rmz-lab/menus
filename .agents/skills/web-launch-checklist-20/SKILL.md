---
name: web-launch-checklist-20
description: >-
  Pre-launch 20-point audit and execution skill for modern web applications, landing pages,
  and digital menus. Enforces smooth scrolling, micro-interactions, hover states, mobile responsiveness,
  mobile bottom navigation, custom favicon, back-to-top button, loading screens, entrance animations,
  repeated CTAs, functional forms, input validation, toast feedback, dark mode, language switchers,
  social links, testimonials, image optimization, and live deployment tracking.
---

# 🚀 20-Point Vibe-Coding Pre-Launch Skill

Inspired by modern high-converting UI/UX principles, this skill establishes the mandatory 20 items to audit and apply to any web project before publishing to production.

---

## The 20 Pre-Launch Commandments

| # | Item | Implementation Requirement |
|---|------|----------------------------|
| 1 | **Animaciones suaves al hacer scroll** | Smooth scroll physics (GSAP ScrollTrigger, Lenis, or CSS `scroll-behavior: smooth` with subtle parallax offsets). |
| 2 | **Microinteracciones con botones** | `active:scale(0.96)`, tactile CSS transitions (`transition: transform 0.15s ease`), button ripple or glowing borders. |
| 3 | **Estados HOVER en elementos interactivos** | Elevación sutil (`translateY(-4px)`), resplandor perimetral neón/dorado y cursor pointer. |
| 4 | **Mobile Responsiveness Total** | Viewport audit: cero scroll horizontal indeseado, `max-width: 100vw`, paddings táctiles mínimos de 44px para dedos. |
| 5 | **Navegación Móvil Ergonómica** | Sticky bottom navigation bar o drawer accesible directamente con el dedo pulgar sin estirar la mano. |
| 6 | **Favicon Personalizado y Touch Icons** | `<link rel="icon">` en SVG o PNG y `<meta name="theme-color">` coherente con la paleta de la marca. |
| 7 | **Botón "Volver Arriba" (Back-to-Top)** | Botón flotante que aparece suavemente (`opacity / translateY`) al rebasar 400px de scroll y sube con animación suave. |
| 8 | **Loading Screen / Skeleton Shimmer** | Pantalla de precarga o esqueletos visuales durante la carga de assets pesados para eliminar el salto de layout (CLS). |
| 9 | **Transiciones entre Secciones** | Suavizado entre categorías, filtros o pestañas con `transition: opacity 0.3s ease, transform 0.3s ease`. |
| 10 | **Animación de Entrada del Hero** | Stagger reveal en el encabezado (título, subtítulo, botones) al cargar la página para impacto visual inmediato. |
| 11 | **CTAs Repetidos Estratégicamente** | Llamado a la acción claro en el Hero (above the fold), a la mitad del contenido, y en el footer o comanda. |
| 12 | **Formulario de Contacto / Comanda Funcional** | Inputs reales conectados a WhatsApp API o backend sin recargar la página. |
| 13 | **Validación en Tiempo Real** | Comprobación de campos obligatorios (número de mesa, teléfono, nombre) antes del envío con bordes rojos y alertas legibles. |
| 14 | **Mensajes de Éxito y Error (Toasts)** | Sistema de notificación emergente no bloqueante (Toast verde para éxito, rojo para error, ámbar para aviso). |
| 15 | **Modo Oscuro Impecable (Dark Mode)** | Paleta de negros mate (#08080a / #111116), texto de alto contraste (#ffffff / #94a3b8) y acentos controlados. |
| 16 | **Selector de Idioma / Moneda** | Switcher bilingüe rápido (ES / EN) especialmente crítico para restaurantes turísticos y comercio. |
| 17 | **Botones de Redes Sociales (RRSS)** | Enlaces directos a Instagram, WhatsApp y Google Maps / TikTok en posiciones accesibles. |
| 18 | **Sección de Testimonios / Social Proof** | Reseñas verificadas con estrellas, avatares y citas reales que disipan dudas del comprador. |
| 19 | **Optimización y Carga Diferida (Lazy Loading)** | Atributos `loading="lazy"`, `decoding="async"`, y dimensiones explícitas en etiquetas `<img>`. |
| 20 | **Despliegue en 1 Clic y Tracker de Visitas** | Publicación continua (GitHub Pages / Vercel) y badge de analítica o visitas en vivo en footer. |

---

## Guía de Verificación Rápida

Al auditar cualquier archivo HTML/JS:
1. Revisa que el `<head>` tenga favicon, theme-color y fuentes.
2. Comprueba que el scroll en móvil no se trabe en contenedores 3D o sliders.
3. Asegura que cada acción del usuario tenga respuesta inmediata (feedback háptico/toast).
4. Verifica que no existan enlaces muertos o botones decorativos sin evento de clic.
