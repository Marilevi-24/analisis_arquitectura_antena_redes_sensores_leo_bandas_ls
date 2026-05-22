## FASE 1: Mapeo de Entidades (Análisis)

A partir del fragmento en LaTeX del artículo de investigación, se extraen los siguientes componentes estructurales y funcionales clave:

1. **Segmento Terrestre (Nodos de Sensores Ambientales):** Sistemas distribuidos de alta densidad ubicados en ecosistemas remotos e inhóspitos (barreras geográficas como selvas densas, océanos abiertos y regiones polares). Tienen severas restricciones de tamaño, peso y consumo energético.
2. **Segmento Espacial (Constelación LEO):** Red de satélites en órbita baja que actúa como infraestructura de red no terrestre (NTN) para mitigar la fragmentación geográfica y habilitar la conectividad IoT global (integración 5G/6G).
3. **Segmento de Enlace (Comunicaciones en Bandas L y S):**
* Enlace bidireccional caracterizado por altos desplazamientos Doppler debido al movimiento dinámico de la constelación LEO.
* Canales diferenciados por parámetros físicos según la tabla tab:comparacion_bandas: la Banda L (1–2 GHz) con penetración atmosférica excelente y bajo consumo; la Banda S (2–4 GHz) con mayor ancho de banda y sensibilidad media a la lluvia.


4. **Arquitectura de Antena:** Punto crítico de la contribución del artículo (configuraciones híbridas *phased-array* en el segmento satelital o sensor).

---

## FASE 2: Auditoría y Reporte de Hallazgos Críticos

### 1. Contraste de Coherencia

El prompt de imagen base captura de forma correcta la macro-estructura del escenario (sensores terrestres en entornos remotos enlazados a satélites LEO). Sin embargo, carece de la especificidad técnica requerida para ilustrar el verdadero núcleo científico del documento: la dualidad de bandas de frecuencia (L/S) y el desafío del desfase Doppler/haz dinámico.

### 2. Lista de Discrepancias Críticas (Elementos faltantes en el Prompt Base)

* **Diferenciación de Canales (Bandas L y S):** El prompt solicita "flechas de enlace bidireccional" genéricas. Científicamente es vital codificar visualmente la coexistencia de las bandas L y S (por ejemplo, mediante dos estilos de línea o grosores vectoriales diferentes en el enlace).
* **Representación de Haz Dinámico (*Phased-Array*):** El texto enfatiza las configuraciones híbridas *phased-array* y la mitigación del efecto Doppler. El prompt pide "curvas suaves de cobertura", pero omitir la naturaleza multi-haz o el direccionamiento dinámico de los haces satelitales resta precisión al escenario propuesto.
* **Geometría Satelital:** Representar los satélites LEO simplemente como "cubos pequeños" debilita la fidelidad de una arquitectura aeroespacial estándar IEEE, donde los paneles solares y los reflectores/matrices de antenas son elementos iconográficos clave.

### 3. Control de Estilo

* **Validación:** El prompt base cumple estrictamente con el fondo blanco, paleta de colores técnicos (#0047AB para elementos activos/enlaces y #4A4A4A para estructuras/terreno), minimalismo vectorial 2D y la **ausencia total de caracteres o texto incrustado**, delegando la semántica a una leyenda iconográfica pura.

---

## FASE 3: Explicación y Justificación de Pre-ejecución

### 1. Disposición Espacial y Composición

* **Plano Inferior (Segmento Terrestre):** Una línea de horizonte ligeramente curvada (isométrica limpia) segmentada en tres micro-ecosistemas estilizados con trazos mínimos: siluetas de abetos (selva/bosque), líneas onduladas finas (océano) y polígonos angulares (zona polar). En cada zona se anclarán pequeños nodos circulares.
* **Plano Superior (Segmento Espacial):** Un arco orbital que cruza la parte superior con un tren de 4 a 5 satélites simplificados vectorialmente (cuerpo central con dos extensiones de paneles solares laterales).
* **Zona de Enlace (Interacción):** Desde cada satélite se proyectarán conos vectoriales punteados que representen el haz de la antena satelital hacia la Tierra. Dentro de estos conos, las flechas bidireccionales se duplicarán: una línea sólida continua (Banda L) y una línea discontinua/segmentada (Banda S), ambas dirigidas hacia los sensores.

```
[Satélites LEO en Órbita Baja]
       |             \
  (Línea Continua)  (Línea Segmentada) -> Representación Dual L/S
       |             \
[Bosque]   [Océano]   [Zona Polar] -> Nodos de sensores de alta densidad

```

### 2. Justificación Técnica

* **Visualización del Vínculo Multi-banda:** Al duplicar el estilo de las flechas de enlace dentro del mismo haz, se justifica visualmente la coexistencia y comparación técnica de las bandas L y S que analiza la Tabla 1 del artículo.
* **Efecto Doppler y Dirección:** El uso de una vista isométrica con los satélites dispuestos sobre un vector de trayectoria (arco) denota intrínsecamente el dinamismo orbital que causa el desplazamiento Doppler mencionado en el texto técnico.

### 3. Advertencias para el Usuario (Puntos de Validación)

* **Complejidad de la Leyenda:** Dado que la regla prohíbe el texto incrustado para cumplir con el estándar internacional de publicación, la leyenda en la esquina inferior dependerá de una correspondencia geométrica estricta (ej. Icono Círculo = Sensor; Icono Línea Continua = Banda L; Icono Línea Segmentada = Banda S). Confirma si deseas que este código iconográfico sea modificado antes de la generación.
* **Densidad de Satélites:** El prompt original pedía de 6 a 8 satélites. En un formato de ancho de figura IEEE ($0.85\linewidth$), incluir 8 satélites detallados vectorialmente puede saturar visualmente el diagrama. Se sugiere reducir la representación explícita a un tren de 4 satélites funcionales para mantener la claridad y el minimalismo.

---

## FASE 4: Ejecución Silenciosa

Por favor, confirma si estás de acuerdo con las correcciones técnicas planteadas (reducción de densidad satelital para claridad visual, representación dual de enlaces L/S y la estructura de la leyenda visual libre de texto). Una vez otorgues tu visto bueno, procederé a realizar la llamada a la herramienta de generación para crear el diagrama técnico definitivo.