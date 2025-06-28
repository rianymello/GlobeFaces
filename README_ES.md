# GlobeFaces

[Versión en Español](./README_ES.md) | [Portuguese Version](./README.md) | [English Version](./README_EN.md)

**GlobeFaces** es un dataset y modelo de reconocimiento facial enfocado en representatividad global, interseccionalidad (raza, género, edad y características faciales poco representadas) y reducción del sesgo algorítmico.

## Objetivo

Desarrollar un *modelo y conjunto de datos* de reconocimiento facial que corrija limitaciones de diversidad encontradas en modelos como FairFace, con enfoque en:

- **Representatividad interseccional**:
  - Ampliar la categorización racial para contemplar variaciones regionales (ej: indígenas brasileños, norteafricanos, mestizos).
  - Representar **características faciales poco modeladas** (ej: discapacidades, marcas de nacimiento, deformidades, uso de turbantes/pañuelos/gafas).

- **Mitigación del sesgo algorítmico**:
  - Usar métricas robustas de fairness (como *Equalized Odds*, *Disparate Impact*) para evaluar el modelo.
  - Crear un pipeline que permita comparar resultados entre diferentes subgrupos.

- **Herramientas abiertas para la comunidad**:
  - Proveer código, documentación y métricas en un repositorio GitHub.
  - Ofrecer APIs e interfaces simples para que investigadores y desarrolladores puedan probar y contribuir.

## Estructura del proyecto

Actualmente, el proyecto contiene las siguientes carpetas principales:

- `images/`: imágenes utilizadas en el dataset
- `labels/`: archivos con anotaciones y categorías de las imágenes

## Licencia

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) 

## Bases de datos utilizadas como referencia

- FairFace  

---
