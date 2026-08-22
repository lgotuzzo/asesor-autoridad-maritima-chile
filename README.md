# Asesor de la Autoridad Marítima de Chile

Skill para asistir exclusivamente a autoridades marítimas chilenas en análisis técnico-jurídicos y operacionales:

- Capitanes de Puerto.
- Gobernadores Marítimos.
- Dirección General del Territorio Marítimo y de Marina Mercante (DIRECTEMAR).
- Representación Permanente de Chile ante la Organización Marítima Internacional (OMI).

La skill organiza el análisis de normativa marítima internacional, nacional y local, con verificación de vigencia y adaptación a la jurisdicción concreta.

## Ámbitos cubiertos

- Seguridad de la navegación y protección de la vida humana en el mar.
- Búsqueda y salvamento marítimo (SAR).
- Puertos, terminales, practicaje, remolque y maniobras.
- Pesca artesanal, caletas y naves menores.
- Matrículas, permisos, certificados y despachos.
- Fiscalización, policía marítima y procedimientos administrativos.
- Contaminación acuática, MARPOL, OPRC y planes de contingencia.
- Concesiones marítimas y ocupación del borde costero.
- SOLAS, COLREG, STCW, MLC 2006 y otros instrumentos internacionales.
- Preparación de posiciones, intervenciones e instrucciones para reuniones de la OMI.

## Principios

1. Trabaja desde la perspectiva institucional de la autoridad, no del administrado.
2. Verifica textos vigentes en fuentes oficiales.
3. Distingue obligación jurídica, recomendación técnica e interpretación.
4. No extrapola resoluciones locales entre jurisdicciones.
5. No inventa facultades, artículos, plazos, medios SAR ni posiciones de Chile.
6. No sustituye el mando, la apreciación operacional ni la asesoría jurídica institucional.
7. No solicita ni reconstruye información clasificada, planes restringidos o vulnerabilidades de seguridad.

## Estructura

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── icon.svg
└── references/
    ├── fuentes-y-vigencia.md
    ├── jurisdiccion-y-normativa-local.md
    ├── operaciones-y-materias.md
    ├── productos-y-formato.md
    └── representacion-omi.md
```

## Instalación

Copiar la carpeta completa en el directorio de skills compatible con el agente utilizado. El archivo principal debe conservar el nombre `SKILL.md` y las rutas relativas de `references/`.

En ChatGPT/Codex, la skill puede invocarse por su nombre:

```text
Usa @asesor-autoridad-maritima-chile para analizar esta decisión.
```

## Ejemplos

```text
Usa @asesor-autoridad-maritima-chile para revisar si el Capitán de Puerto
puede autorizar una maniobra nocturna en este terminal y qué antecedentes
debe exigir antes de resolver.
```

```text
Usa @asesor-autoridad-maritima-chile para preparar una minuta al Gobernador
Marítimo sobre una emergencia SAR de una nave pesquera artesanal.
```

```text
Usa @asesor-autoridad-maritima-chile para preparar la matriz de posición
nacional respecto del documento MEPC [signatura], sin asumir instrucciones
que Chile no haya impartido.
```

## Fuentes oficiales prioritarias

- [LeyChile — Biblioteca del Congreso Nacional](https://www.bcn.cl/leychile/)
- [Diario Oficial de la República de Chile](https://www.diariooficial.interior.gob.cl/)
- [Marco normativo de DIRECTEMAR](https://www.directemar.cl/directemar/marco-normativo)
- [Organización Marítima Internacional](https://www.imo.org/)
- [OIT/NORMLEX](https://normlex.ilo.org/)

La skill contiene métodos de búsqueda y control de vigencia, no copias permanentes de toda la legislación. Las normas deben comprobarse nuevamente al analizar cada caso.

## Limitaciones

Este proyecto es una herramienta independiente y no oficial. No representa a la Armada de Chile, DIRECTEMAR, el Ministerio de Defensa Nacional, el Ministerio de Relaciones Exteriores ni la OMI.

No debe emplearse para ejecutar actos administrativos, impartir órdenes reales, activar emergencias o sustituir los sistemas oficiales.

## Licencia

Distribuido bajo licencia MIT. Véase [LICENSE](LICENSE).
