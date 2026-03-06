# Sistema natural vs sistema controlado

Este diagrama compara dos tipos de sistemas acuáticos:

- sistemas naturales influenciados por ecosistemas forestales  
- sistemas acuáticos controlados o artificiales  

El objetivo es visualizar las diferencias fundamentales en su dinámica.

---

## Diagrama comparativo

```mermaid
flowchart LR

subgraph NATURAL[Sistema acuático natural]

A1[Ecosistema forestal]
A2[Entrada continua de materia vegetal]
A3[Lixiviación natural]
A4[Materia orgánica disuelta<br>DOM]
A5[Alta diversidad microbiana]
A6[Procesos fotoquímicos]
A7[Interacciones químicas]
A8[Flujo continuo de agua]
A9[Exportación de materia]
A10[Equilibrio dinámico]

A1 --> A2
A2 --> A3
A3 --> A4
A4 --> A5
A4 --> A6
A4 --> A7
A5 --> A10
A6 --> A10
A7 --> A10
A8 --> A9
A9 --> A10

end

subgraph CONTROLADO[Sistema acuático controlado]

B1[Entrada puntual de material]
B2[Materia orgánica limitada]
B3[Menor diversidad microbiana]
B4[Flujo de agua reducido]
B5[Acumulación de compuestos]
B6[Procesos simplificados]
B7[Equilibrio más sensible]

B1 --> B2
B2 --> B3
B2 --> B5
B3 --> B6
B4 --> B5
B6 --> B7
B5 --> B7

end
