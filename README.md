# bigbox · corpo — Presentaciones

Repositorio público de presentaciones del equipo de Marketing B2B de Bigbox Corpo.

**Landing:** https://marketingb2b-bigbox.github.io/bigbox-presentaciones/

## Estructura

```
bigbox-presentaciones/
├── index.html                    ← landing con el listado de decks
└── {slug}/
    └── index.html                ← cada deck en su propia subcarpeta
```

URL de cada deck: `https://marketingb2b-bigbox.github.io/bigbox-presentaciones/{slug}/`

## Decks publicados

| Slug | Deck | Fecha |
|---|---|---|
| [`encuestas-satisfaccion`](https://marketingb2b-bigbox.github.io/bigbox-presentaciones/encuestas-satisfaccion/) | Automatización de Encuestas de Satisfacción | 2026-04 |

## Cómo agregar un nuevo deck

1. Crear carpeta `{slug}/` con `index.html` dentro
2. Agregar una card al `index.html` de la raíz (landing)
3. `git add . && git commit -m "Add: {slug}" && git push`
4. Deploy automático en ~60s

---

Mantenido por [@marketingb2b-Bigbox](https://github.com/marketingb2b-Bigbox)
