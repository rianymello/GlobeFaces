# GlobeFaces

[English Version](./README_EN.md) | [Versión en Español](./README_ES.md)

**GlobeFaces** é um dataset e modelo de reconhecimento facial com foco em representatividade global, interseccionalidade (raça, gênero, idade e características faciais menos visadas), e redução de viés algorítmico.

## Objetivo

Desenvolver um *modelo e conjunto de dados* de reconhecimento facial que corrija limitações de diversidade encontradas em modelos como o FairFace, com foco em:

- **Representatividade interseccional**:
  - Ampliar a categorização racial para contemplar variações regionais (ex: indígenas brasileiros, norte-africanos, miscigenados).
  - Representar **características faciais pouco modeladas** (ex: deficiências, marcas de nascença, deformidades, uso de turbantes/lenços/óculos).

- **Mitigação de viés algorítmico**:
  - Usar métricas robustas de fairness (como *Equalized Odds*, *Disparate Impact*) para avaliar o modelo.
  - Criar um pipeline que permita comparar resultados entre diferentes subgrupos.

- **Ferramentas abertas para a comunidade**:
  - Fornecer código, documentação e métricas em um repositório GitHub.
  - Oferecer APIs e interfaces simples para pesquisadores/as e desenvolvedores/as testarem e contribuírem.

## Estrutura do projeto

Atualmente, o projeto contém as seguintes pastas principais:

- `images/`: imagens utilizadas no dataset
- `labels/`: arquivos com as anotações e categorias das imagens

## Licença

- Código-fonte: MIT License (veja arquivo LICENSE)
- Dataset: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) (veja LICENSE-DATASET.md)

## Bases de dados utilizadas como referência

- FairFace  

---
