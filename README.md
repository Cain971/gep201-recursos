# GEP201 — Recursos de clase

Recursos web (HTML autocontenidos) de apoyo a las sesiones de **GEP201 – Gestión Financiera del Estado** (PUCP). Material dirigido a estudiantes: **no contiene rúbricas, criterios de calificación ni notas docentes** — eso vive en el repo privado del curso (`gep201-curso`, carpeta `clases/`).

## Publicación

Repo público → GitHub Pages: **https://cain971.github.io/gep201-recursos/**

Cada archivo del repo queda accesible en esa URL por su ruta. Los cambios requieren `commit` + **push**; Pages reconstruye en ~1–2 min.

## Organización

Por unidad del sílabo (espeja `clases/` del repo del curso):

```
index.html                              → landing con enlaces a todos los recursos
unidad-1/
  triangulo-estrategico.html            → Clase 3 · triángulo estratégico de Moore
unidad-2/ …                             → (por agregar)
```

## Convención

- Un archivo `.html` por recurso, **autocontenido** (CSS y JS embebidos; sin dependencias externas salvo Google Fonts, con fallback del sistema).
- Tipografía del curso: Playfair Display, IBM Plex Mono, Source Serif 4.
- Al agregar un recurso: crear el `.html` en la carpeta de su unidad y añadir su tarjeta en `index.html`.
- La fuente de diseño pedagógico de cada recurso es el `.md` correspondiente en `gep201-curso/clases/unidad-X/`; ese `.md` enlaza a la URL publicada aquí.

## Relación con los otros repos de GEP201

| Repo | Contenido | Despliegue |
|---|---|---|
| `gep201-curso` (privado) | Contenido pedagógico, bibliografía, sílabos, notas docentes | — |
| `gep201` (público) | Sistema de evaluación y sorteo | https://cain971.github.io/gep201/ |
| `gep201-recursos` (público, este) | Recursos web para estudiantes | https://cain971.github.io/gep201-recursos/ |
