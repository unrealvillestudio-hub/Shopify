# Humanize Layer — UNRLVL F2.5
## Guía de referencia para assets web

Todo output del ecosistema UNRLVL debe sentirse hecho por humanos para humanos.
Esta guía resume los principios aplicados automáticamente por WebLab v2.0.

---

## Copy (web & blog)

**Voz auténtica:**
- Ritmo variable: frases cortas y largas alternadas, nunca cadencia uniforme
- Contracciones y coloquialismos naturales del mercado objetivo
- Primera persona cuando sea posible
- Puntuación expresiva: puntos suspensivos para pausa, em-dash para énfasis

**Prohibido:**
- "En conclusión", "Es importante destacar", "Ciertamente"
- Adjetivos vacíos: innovador, revolucionario, transformador, sinérgico
- Párrafos perfectamente simétricos en longitud
- Listas de exactamente 3 puntos idénticos en longitud

---

## Imágenes y avatares

- Piel con textura real, asimetría facial sutil, flyaways en cabello
- Micro-expresiones, no sonrisa congelada de stock
- Ropa con arrugas naturales de movimiento
- **Prohibido:** piel plástica, simetría perfecta, poses de stock

---

## Web assets

- Fotografía candid sobre staged
- Headlines conversacionales, no corporativos
- Párrafos máx 3-4 líneas
- Microcopy de UI con personalidad (no "Submit" / "Learn More")
- **Prohibido:** fotos de stock con sonrisa perfecta, copy en tercera persona impersonal

---

## Overrides por marca

Cada marca puede tener instrucciones adicionales en `humanizeConfig.ts`.
Las instrucciones de esta guía son el fallback DEFAULT.

| Marca | Override |
|-------|---------|
| Neurone Cosmética | Tono científico-accesible + compliance estricto + Spanglish Miami |
| Vizos Salón | Autoridad cálida + referencias a experiencia real de salón |
| Diamond Details | Lenguaje de taller premium + el auto como identidad del cliente |

---

*Fuente de verdad: `src/config/humanizeConfig.ts` en cada Lab app*
*DB_VARIABLES v6.4 — pestaña HUMANIZE*
