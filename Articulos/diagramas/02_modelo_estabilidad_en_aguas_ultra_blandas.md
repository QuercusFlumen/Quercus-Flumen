# Modelo de estabilidad en aguas ultra blandas

Este diagrama representa los factores principales que influyen en la estabilidad química de sistemas acuáticos con **baja mineralización**.

Las aguas ultra blandas presentan una química particularmente sensible, donde pequeñas variaciones en la composición del sistema pueden producir cambios significativos.

---

## Diagrama del sistema

```mermaid
flowchart TD

A[Baja mineralización del agua]

A --> B[Baja fuerza iónica]
A --> C[Baja alcalinidad]

C --> D[Capacidad tampón limitada]

B --> E[Mayor sensibilidad química]

D --> F[Mayor variabilidad del pH]

E --> G[Sistema químico sensible]
F --> G

H[Entrada de materia orgánica<br>DOM] --> I[Compuestos orgánicos]

I --> J[Grupos funcionales orgánicos]

J --> K[Donación y aceptación de protones]
J --> L[Complejación de metales]

K --> M[Influencia sobre el pH]
L --> N[Regulación de metales]

I --> O[Fuente de carbono microbiano]

O --> P[Actividad microbiana]

P --> Q[Transformación de compuestos orgánicos]

Q --> I

G --> R[Equilibrio químico dinámico]

M --> R
N --> R
P --> R

R --> S[Estabilidad del sistema acuático]
