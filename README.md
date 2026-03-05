# UNRLVL-Shopify

Repositorio de custodia para todos los assets web del ecosistema UNRLVL Studio.
Gestiona secciones Liquid, páginas HTML, posts de blog y templates de email
para las tiendas Shopify y sitios WordPress de las marcas del ecosistema.

---

## Estructura

```
UNRLVL-Shopify/
├── _shared/                    ← Recursos transversales (Humanize layer, guías)
├── _template/                  ← Estructura base para nuevas marcas
│   ├── sections/               ← Secciones Liquid / HTML por página
│   ├── pages/                  ← Páginas completas
│   ├── blog/                   ← Posts de blog
│   └── emails/                 ← Templates de email
├── neurone-cosmetica/          ← Neurone Cosmética (activo)
│   ├── changelog.md
│   ├── sections/
│   ├── pages/
│   ├── blog/
│   └── emails/
└── [marca]/                    ← Nuevas marcas se añaden aquí
```

---

## Output modes

Cada archivo puede existir en tres formatos:

| Extensión | Descripción | Uso |
|-----------|-------------|-----|
| `.liquid` | Sección Shopify nativa con schema JSON | Theme editor de Shopify |
| `.html`   | HTML semántico con CSS inline | Custom HTML block (Shopify/WP) |
| `.md`     | Markdown limpio | CMS headless / documentación |

---

## Convención de nombres

```
[seccion]-[variante]-[idioma].[ext]

Ejemplos:
  hero-b2c-es.liquid
  hero-b2b-en.html
  faq-profesionales-es.liquid
  email-b2b-bienvenida-es.html
```

---

## Workflow

1. **Generar** — WebLab / BlogLab genera el contenido con el output mode correcto
2. **Commit** — archivo se añade al directorio de la marca correspondiente
3. **Changelog** — se actualiza `[marca]/changelog.md` con descripción del cambio
4. **Deploy** — se sube manualmente al theme editor de Shopify o se pushea vía API

---

## Marcas activas

| Marca | Directorio | Estado |
|-------|-----------|--------|
| Neurone Cosmética | `neurone-cosmetica/` | 🟡 En desarrollo |

---

*Generado y mantenido por UNRLVL Studio — WebLab v2.0*
