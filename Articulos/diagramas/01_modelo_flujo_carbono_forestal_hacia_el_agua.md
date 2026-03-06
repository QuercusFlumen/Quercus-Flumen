# Modelo de flujo del carbono forestal hacia el agua

Este diagrama representa de forma simplificada cómo el carbono fijado por el ecosistema forestal puede terminar incorporado al sistema acuático en forma de **materia orgánica disuelta (DOM)**.

---

## Diagrama del flujo

```mermaid
flowchart TD

A[Atmósfera<br>CO2] --> B[Vegetación forestal<br>fotosíntesis]

B --> C[Biomasa vegetal]
C --> D[Hojas]
C --> E[Ramas y restos finos]
C --> F[Tejidos leñosos]

D --> G[Caída de hojarasca]
E --> G
F --> H[Descomposición lenta]

G --> I[Capa de hojarasca]
I --> J[Hidratación y lixiviación]
I --> K[Descomposición microbiana]

H --> K

J --> L[Compuestos orgánicos solubles]
K --> M[Transformación de materia orgánica]

L --> N[Suelo forestal]
M --> N

N --> O[Drenaje y flujo subsuperficial]
N --> P[Escorrentía superficial]

O --> Q[Sistema acuático]
P --> Q

Q --> R[Materia orgánica disuelta<br>DOM]

R --> S[Procesos químicos]
R --> T[Procesos biológicos]
R --> U[Propiedades ópticas del agua]

S --> V[Equilibrio del sistema acuático]
T --> V
U --> V
