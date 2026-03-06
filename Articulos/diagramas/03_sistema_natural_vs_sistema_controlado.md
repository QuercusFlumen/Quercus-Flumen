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

Interpretación del modelo
Sistemas naturales
Los ecosistemas acuáticos naturales funcionan como sistemas abiertos.
Están caracterizados por:
entrada continua de materia orgánica
gran diversidad biológica
múltiples procesos químicos y biológicos
intercambio constante de agua y materia
Estas condiciones permiten que el sistema alcance un equilibrio dinámico relativamente estable.
Sistemas controlados
Los sistemas acuáticos controlados presentan características diferentes.
Entre ellas:
entradas de materia más limitadas o puntuales
menor diversidad biológica
menor renovación del sistema
acumulación potencial de compuestos
Estas condiciones pueden hacer que el sistema sea más sensible a perturbaciones.
Diferencia fundamental
La diferencia clave entre ambos sistemas es la forma en que circula la materia y la energía.
En sistemas naturales:
los procesos están distribuidos en el espacio
existen múltiples vías de transformación
la materia puede entrar y salir del sistema
En sistemas controlados:
los procesos están concentrados en un volumen limitado
los flujos son más restringidos
la acumulación de compuestos puede ser mayor
Valor del modelo
Este diagrama permite visualizar una idea central:
los sistemas controlados no replican la naturaleza.
solo representan modelos simplificados de procesos naturales.
Comprender esta diferencia es fundamental para interpretar el comportamiento de sistemas acuáticos artificiales.
Relación con la serie de artículos
Este modelo conecta especialmente con los artículos del Tomo IV:
10_reproducir_sistemas_naturales_en_entornos_controlados.md
11_hojas_en_sistemas_acuaticos_beneficios_y_limitaciones.md
12_hacia_un_modelo_de_equilibrio_organico_en_el_agua.md
