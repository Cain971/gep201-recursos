# GEP201 — Materiales de clase

Presentaciones y guías de cada sesión de **GEP201 – Gestión Financiera del Estado** (PUCP), en el orden en que se dictaron. Material dirigido a estudiantes: **no contiene rúbricas, criterios de calificación ni notas docentes** — eso vive en el repo privado del curso (`gep201-curso`, carpeta `clases/`).

## Página pública

Repo público → GitHub Pages: **https://cain971.github.io/gep201-recursos/**

Cada archivo del repo queda accesible en esa URL por su ruta. Los cambios requieren `commit` + **push**; Pages reconstruye en ~1–2 min.

## Lo que tiene la página

Los enlaces abren la página publicada, no el código.

| Sesión | Fecha (2026) | Tema | Tipo | Material |
|---|---|---|---|---|
| 3 | 2 de setiembre | Triángulo estratégico | Guía | [El triángulo estratégico de la política pública](https://cain971.github.io/gep201-recursos/unidad-1/triangulo-estrategico.html) |
| 4 | 9 de setiembre | Condición de interés | Guía | [La condición de interés](https://cain971.github.io/gep201-recursos/unidad-2/condicion-de-interes.html) |
| 5 | 16 de setiembre | Modelo explicativo | Guía | [Riesgos de construir la cadena causal desde la solución](https://cain971.github.io/gep201-recursos/unidad-3/cadena-desde-la-solucion.html) |
| 5 | 16 de setiembre | Modelo explicativo | Guía | [Un asistente de evidencia, no un analista](https://cain971.github.io/gep201-recursos/unidad-3/revision-de-evidencia-con-ia.html) |
| 6 | 23 de setiembre | Sistema de presupuesto y reglas fiscales | Presentación | [Sistema de presupuesto público y reglas fiscales](https://cain971.github.io/gep201-recursos/unidad-3/deck-sistema-presupuesto-reglas-fiscales.html) |
| 6 | 23 de setiembre | Sistema de presupuesto y reglas fiscales | Guía | [1990 y las reglas fiscales](https://cain971.github.io/gep201-recursos/unidad-3/1990-y-las-reglas-fiscales.html) |
| 6 | 23 de setiembre | Sistema de presupuesto y reglas fiscales | Guía | [Qué es y de dónde viene el PPR](https://cain971.github.io/gep201-recursos/unidad-3/que-es-y-de-donde-viene-el-ppr.html) |
| 7 | 30 de setiembre | Presupuesto por resultados | Presentación | [Presupuesto por resultados: qué es y cómo se aplica](https://cain971.github.io/gep201-recursos/unidad-3/deck-introduccion-ppr.html) |
| 8 | 7 de octubre | Programas presupuestales | Presentación | [Programas presupuestales](https://cain971.github.io/gep201-recursos/unidad-4/deck-programas-presupuestales.html) |
| 9 | 21 de octubre | Modelo prescriptivo y teoría de cambio | Presentación | [De las causas a la intervención](https://cain971.github.io/gep201-recursos/unidad-4/deck-prescriptivo-teoria-cambio.html) |
| 10 | 28 de octubre | El seguimiento como motor de la reforma | Presentación | [El seguimiento como motor de la reforma](https://cain971.github.io/gep201-recursos/unidad-4/deck-seguimiento-motor-reforma.html) |
| 10 | 28 de octubre | El seguimiento como motor de la reforma | Guía | [Barber con lupa](https://cain971.github.io/gep201-recursos/unidad-4/lectura-barber-punjab.html) |
| 10 | 28 de octubre | El seguimiento como motor de la reforma | Guía | [Saber cuánto no es saber qué lo causó](https://cain971.github.io/gep201-recursos/unidad-4/evaluacion-de-impacto.html) |
| 11 | 4 de noviembre | Documental «La Señal» | Presentación | [La Señal: diseñar desde la realidad](https://cain971.github.io/gep201-recursos/unidad-4/deck-sesion-11-la-senal.html) |

## Organización del repo

La página va por sesión; los archivos, por unidad del sílabo (espeja `clases/` del repo del curso). Presentaciones y guías de una unidad viven **juntas** en su carpeta; las presentaciones llevan el prefijo `deck-`:

```
index.html        → la portada, «Materiales de clase»
unidad-1/         → sesión 3
unidad-2/         → sesión 4
unidad-3/         → sesiones 5 a 7
unidad-4/         → sesiones 8 a 11
presentaciones/   → solo redirecciones a unidad-3/ (enlaces antiguos, desde 2026-10-05)
```

Las presentaciones se proyectan desde Pages. Su borrador, si hace falta uno antes de publicar, se trabaja en `gep201-curso/clases/unidad-X/` (privado) y se publica aquí; ya no hay copia «oficial» privada.

## Convención

- Un archivo `.html` por material, **autocontenido** (CSS y JS embebidos; sin dependencias externas salvo Google Fonts, con fallback del sistema).
- Tipografía: la identidad Grilla modular (Archivo, IBM Plex Mono) en la portada y en lo hecho con el núcleo de base-visual; las guías de las sesiones 3 a 6 conservan la anterior (Playfair Display, IBM Plex Mono, Source Serif 4).
- **`index.html` no se edita a mano:** se construye desde `gep201-curso/clases/portada-recursos.plantilla.html` con `ensamblar.py construir` de base-visual (desde el 2026-11-03).
- Al agregar un material: crear el `.html` en la carpeta de su unidad, añadir su fila en esa plantilla, **en el bloque de su sesión**, con su etiqueta «Presentación» o «Guía», y sumarlo a la tabla de este README. Después, el enlace a PAIDEIA.
- La URL no se renombra: el repo sigue siendo `gep201-recursos` aunque la página se llame «Materiales de clase», porque es la dirección que ya conocen los alumnos. «Recurso» queda como nombre interno de trabajo.
- La fuente de diseño pedagógico de cada guía es el `.md` correspondiente en `gep201-curso/clases/unidad-X/`; ese `.md` enlaza a la URL publicada aquí.

## Relación con los otros repos de GEP201

| Repo | Contenido | Despliegue |
|---|---|---|
| `gep201-curso` (privado) | Contenido pedagógico, bibliografía, sílabos, notas docentes | — |
| `gep201` (público) | Sistema de evaluación y sorteo | https://cain971.github.io/gep201/ |
| `gep201-recursos` (público, este) | Materiales de clase para estudiantes | https://cain971.github.io/gep201-recursos/ |
