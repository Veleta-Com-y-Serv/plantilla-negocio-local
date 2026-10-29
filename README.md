# Plantilla NoExpertise · Negocio local

Web cálida para tiendas, bares y talleres, con horario, fotos y botón de llamar.

- Sectores: tienda, restaurante, taller. Estilo: calido. Plan mínimo: gratis.
- Secciones: hero, servicios, galeria, horario-ubicacion, testimonios, preguntas, contacto.
- SEO de base incluido (`src/lib/seo.ts`): canónica, og:image, JSON-LD del negocio y de las preguntas frecuentes, `robots.txt`, `sitemap.xml` y `llms.txt`; `noindex` si `seo.indexable: false`.
- Contenido editable en `site.yaml`; metadatos en `template.yaml`; reglas para el agente en `CLAUDE.md`.

```
npm ci
npm run dev      # desarrollo
npm run build    # web estática en dist/
```

Basada en [AstroWind](https://github.com/onwidget/astrowind) © onWidget, licencia MIT (`LICENSE-ASTROWIND.md`). Imágenes de relleno (`public/placeholders/`) generadas para esta plantilla, sin licencias de terceros.
