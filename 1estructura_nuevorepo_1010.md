
PLAN DE REORGANIZACIÓN DEL REPOSITORIO — QUERCUS FLUMEN
=======================================================

Objetivo del refactor
---------------------
1. Crear una estructura única y clara del repositorio.
2. Separar contenido público de información sensible.
3. Hacer que SCIENCE respalde a TEST y TEST justifique decisiones del producto.
4. Mantener WEB limpio: narrativa, claims e imágenes.

Estructura final recomendada
----------------------------

/
├ README.md
├ WHITEPAPER.md
├ MARCO_EXPOSICION_PUBLICA_Y_PRIVADA.md
│
├ docs/
│   ├ SCIENCE/
│   ├ TEST/
│   ├ PROTOCOLOS/
│   ├ DOSIFICACION/
│   ├ WEB/
│   └ ADRISS/
│
└ private/  (no público o repositorio privado)
    ├ datos_reales/
    ├ parametros_lote/
    ├ proceso_detallado/
    └ evidencias_fotos/

Nota:
Si el repositorio es público, la carpeta private no debería existir en él.
Lo recomendable es un repositorio privado separado.

----------------------------------------------------------------

COMMIT 1 — Crear estructura canónica
------------------------------------

Mensaje de commit:
Refactor: estructura canónica del repositorio (docs/…)

Crear archivo:
docs/README.md

Contenido:

Documentación Quercus Flumen

Este directorio organiza toda la documentación del proyecto en cinco áreas:

1) SCIENCE — Marco científico y explicaciones técnicas.
2) TEST — Base experimental pública.
3) PROTOCOLOS — Procedimientos operativos.
4) DOSIFICACION — Guías de uso.
5) WEB — Copys, narrativa y recursos visuales.
6) ADRISS — Carpeta para subvenciones y desarrollo territorial.

Regla de exposición:
Este repositorio evita publicar valores exactos replicables.
Ver documento: MARCO_EXPOSICION_PUBLICA_Y_PRIVADA.md

Crear carpetas:

docs/SCIENCE/
docs/TEST/
docs/PROTOCOLOS/
docs/DOSIFICACION/
docs/WEB/
docs/ADRISS/

----------------------------------------------------------------

COMMIT 2 — Unificar Experimentación
-----------------------------------

Mensaje:
Move: Experimentación → docs/TEST (unificación)

Reglas:

Todo lo experimental → docs/TEST
Explicación científica → docs/SCIENCE
Proceso productivo → docs/PROTOCOLOS
Uso del producto → docs/DOSIFICACION

Crear archivo:
docs/TEST/README.md

Contenido:

TEST (Testaje Público)

Esta carpeta recoge la base experimental del proyecto en términos públicos.
No se publican parámetros exactos replicables.

Se explica:
- qué variable se probó
- qué se observó
- qué conclusión operativa se tomó

Índice:

Agua base
Temperatura de extracción
Estado de la hoja
Especies de hoja
Métodos de extracción
Reposo y estabilidad
Conclusion_color

----------------------------------------------------------------

COMMIT 3 — SCIENCE: base científica
-----------------------------------

Mensaje:
SCIENCE: base científica (color ≠ beneficio)

Archivos:

docs/SCIENCE/color_vs_beneficio.md
docs/SCIENCE/humicos_fulvicos_taninos.md
docs/SCIENCE/estabilidad_microbiologica.md
docs/SCIENCE/bibliografia.md

Archivo:
docs/SCIENCE/README.md

Contenido:

SCIENCE (Marco técnico-científico)

Objetivo:
Explicar qué es Wild y por qué funciona desde química y ecología.

Contenidos:

1. Color vs beneficio
2. Taninos y ácidos húmicos/fúlvicos
3. Complejación y baja interferencia iónica
4. Estabilidad microbiológica
5. Comparativa con extractos industriales
6. Bibliografía científica

----------------------------------------------------------------

COMMIT 4 — TEST: conclusion_color
---------------------------------

Mensaje:
TEST: conclusion_color (de más negro a más óptimo)

Archivo:
docs/TEST/conclusion_color.md

Documento narrativo técnico sobre cómo los experimentos demostraron
que mayor intensidad de color no implicaba mayor beneficio biológico.

----------------------------------------------------------------

COMMIT 5 — PROTOCOLOS
---------------------

Mensaje:
PROTOCOLOS: estabilidad y bioseguridad

Archivos:

docs/PROTOCOLOS/protocolo_estabilidad_publico.md
docs/PROTOCOLOS/haccp_resumen_publico.md
docs/PROTOCOLOS/control_lotes_publico.md

Archivo:
docs/PROTOCOLOS/README.md

Contenido:

PROTOCOLOS (Versión pública)

Describe el proceso de forma general sin revelar parámetros críticos.

Incluye:

- separación de sedimentos
- filtrado progresivo
- estabilización térmica
- control de lote
- almacenamiento

----------------------------------------------------------------

COMMIT 6 — DOSIFICACION
-----------------------

Mensaje:
DOSIFICACION: guía general + disclaimer

Archivos:

docs/DOSIFICACION/README.md
docs/DOSIFICACION/disclaimer.md
docs/DOSIFICACION/general.md

Rangos de dosificación:

0.2 ml/L — aporte muy sutil
0.5 ml/L — mínimo en biotopos amazónicos
1.5 ml/L — dosis media
3 ml/L — dosis máxima

El color no es indicador de calidad ni de eficacia.

----------------------------------------------------------------

COMMIT 7 — WEB
--------------

Mensaje:
WEB: narrativa y claims

Archivos:

docs/WEB/README.md
docs/WEB/claims_permitidos.md
docs/WEB/copy_home.md
docs/WEB/copy_producto_wild.md

Carpeta:
docs/WEB/images/

----------------------------------------------------------------

COMMIT 8 — ADRISS
-----------------

Mensaje:
ADRISS: estructura final para dossier

Contendrá documentos adaptados a desarrollo rural
y financiación tipo LEADER.

----------------------------------------------------------------

COMMIT 9 — Root
---------------

Mensaje:
Root: README + Whitepaper final

Contenido del README:

- qué es Quercus Flumen
- qué es Wild
- dónde está cada sección del repositorio
- política de exposición pública

----------------------------------------------------------------

COMMIT 10 — Seguridad
---------------------

Mensaje:
Security: bloqueo de datos internos

Archivo:
.gitignore

Contenido sugerido:

/private/
/datos/
/evidencias/
/parametros/
*.csv
*.xlsx

Esto evita subir datos sensibles del proceso.

----------------------------------------------------------------

Conclusión
----------

Esta reorganización separa claramente:

- ciencia
- experimentación
- proceso
- marketing

Permite mantener transparencia científica sin revelar
el know‑how del proceso productivo.
