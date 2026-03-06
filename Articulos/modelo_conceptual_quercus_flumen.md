# Modelo conceptual del sistema Quercus Flumen

Este diagrama resume el modelo conceptual desarrollado a lo largo de la serie:

**Materia orgánica disuelta, agua forestal y estabilidad en sistemas acuáticos**

El modelo representa la interacción entre los principales componentes que estructuran los sistemas acuáticos influenciados por ecosistemas forestales.

---

## Diagrama del sistema

```mermaid
flowchart TD

A[ECOSISTEMA FORESTAL]

A --> B[Materia vegetal<br>hojas, ramas, hojarasca]

B --> C[Lixiviación vegetal]

C --> D[Materia orgánica disuelta<br>DOM]

D --> E[Química del agua]

D --> F[Actividad microbiana]

F --> G[Transformación biológica<br>de la DOM]

G --> D

E --> H[Interacciones químicas]

H --> I[Complejación de metales]

H --> J[Propiedades ópticas del agua]

H --> K[Regulación del pH]

D --> L[Procesos fotoquímicos]

L --> M[Transformación molecular]

M --> D

E --> N[Equilibrio químico del sistema]

F --> N

D --> N

N --> O[Estabilidad dinámica<br>del sistema acuático]
