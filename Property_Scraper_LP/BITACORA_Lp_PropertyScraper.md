# BITÁCORA — Landing Page Property Scraper

> **Proyecto:** Landing page para la extensión Property Scraper
> **Fecha de inicio:** 2026-09-08
> **Estado actual:** Completada, pendiente deploy a GitHub Pages
> **Stack:** HTML, CSS, JavaScript vanilla
> **Hosting:** GitHub Pages (pendiente)
> **URL:** https://arzaganahil.github.io/property-scraper-lp/
> **Color corporativo:** #E8505B (rosa/coral del logo)

---

## 1. Objetivo

Página web para promocionar la extensión Property Scraper y dirigir descargas desde Chrome Web Store y Edge Add-ons.

## 2. Estructura

```
Property_Scraper_LP/
├── index.html              # Página principal
├── css/
│   └── style.css           # Estilos (tema oscuro, color corporativo)
├── js/
│   └── main.js             # Animaciones (scroll reveal, nav activo)
├── assets/
│   └── img/
│       ├── icon128.png     # Logo de la extensión
│       ├── fondoHero.jpg   # Fondo del hero
│       ├── Extencion.png   # Screenshot de la extensión
│       └── asi_se_ve.png   # Captura de la extensión en uso
└── BITACORA_Lp_PropertyScraper.md
```

## 3. Secciones

1. **Nav** — Logo + links + CTA (max-width 1100px, alineado con footer)
2. **Hero** — Badge "Chrome & Edge — Gratis", título, subtítulo, 2 CTAs (Chrome/Edge), screenshot de la extensión, fondo con imagen
3. **5 portales** — Tarjetas con nombre de cada portal (Idealista, Fotocasa, Habitaclia, YaEncontré, Pisos.com)
4. **Cómo funciona** — 6 pasos con números circulares
5. **Todo lo que necesitas** — 6 tarjetas con iconos SVG lineales en color corporativo
6. **Así se ve** — Screenshot `asi_se_ve.png`
7. **Tu privacidad** — 6 tarjetas con título + descripción (iconos ✓ en coral)
8. **Download CTA** — Botones Chrome/Edge
9. **Footer** — Logo + links (Chrome, Edge, Privacidad, GitHub)

## 4. Diseño

- **Tema oscuro** (#0d1117 base)
- **Color corporativo:** #E8505B (rosa/coral del logo)
- **Tipografía:** Inter (Google Fonts)
- **Responsive:** Adaptado a móvil
- **Animaciones:** Fade-in en scroll, nav activo por sección

## 5. Archivos de assets

| Archivo | Uso |
|---------|-----|
| `icon128.png` | Logo nav y footer |
| `fondoHero.jpg` | Fondo del hero con overlay oscuro |
| `Extencion.png` | Screenshot en hero |
| `asi_se_ve.png` | Captura en sección "Así se ve" |

## 6. Deploy a GitHub Pages

1. Crear repositorio `property-scraper-lp` en GitHub
2. Subir archivos de `Property_Scraper_LP/`
3. Settings → Pages → Branch: main → Save
4. URL: https://arzaganahil.github.io/property-scraper-lp/

---

## 7. CHECKPOINT — 2026-09-08

### Completado
- ✅ Landing page creada (HTML, CSS, JS)
- ✅ Color corporativo #E8505B aplicado a todos los botones e iconos
- ✅ Logo nav y footer alineados (max-width 1100px)
- ✅ Hero alineado con logo del nav
- ✅ Imágenes: fondoHero, Extencion.png, asi_se_ve.png
- ✅ Iconos SVG lineales en sección de features
- ✅ Sección privacidad: 6 tarjetas con título + descripción
- ✅ Responsive móvil

### Pendiente
- [ ] Subir a GitHub Pages y activar
- [ ] Añadir más screenshots si es necesario

---

*Última revisión: 2026-09-08. Landing page completada, pendiente deploy.*
