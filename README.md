# Experimental Physics Projects

A growing portfolio of experimental-physics laboratory work developed during my studies at Universidad Técnica Federico Santa María (UTFSM).

This repository keeps the **final academic reports** in `papers/` and organizes the supporting material for each experiment inside `projects/`. Each project folder can contain experimental data, analysis files, figures, Tracker projects and supplementary documents without mixing material from different reports.

## Current reports

| Project | Paper | Supporting files |
|---|---|---|
| Análisis de un movimiento en caída libre | [`paper`](./papers/analisis-de-un-movimiento-en-caida-libre.pdf) | [`project`](./projects/analisis-de-un-movimiento-en-caida-libre/) |
| Lanzamiento parabólico: contrastes entre teoría, medición experimental y modelado digital | [`paper`](./papers/lanzamiento-parabolico-contrastes-entre-teoria-medicion-experimental-y-modelado-digital.pdf) | [`project`](./projects/lanzamiento-parabolico/) |
| Movimiento aleatorio en dos dimensiones: análisis del desplazamiento cuadrático medio y clasificación del régimen dinámico | [`paper`](./papers/movimiento-aleatorio-en-dos-dimensiones-analisis-del-desplazamiento-cuadratico-medio-y-clasificacion-del-regimen-dinamico.pdf) | [`project`](./projects/movimiento-aleatorio/) |
| Estudio experimental de la resistencia del aire en el movimiento de un carro sobre riel de aire | [`paper`](./papers/estudio-experimental-de-la-resistencia-del-aire-en-el-movimiento-de-un-carro-sobre-riel-de-aire.pdf) | [`project`](./projects/resistencia-del-aire/) |
| Análisis experimental del comportamiento dinámico de sistemas oscilatorios amortiguados y acoplados | [`paper`](./papers/analisis-experimental-del-comportamiento-dinamico-de-sistemas-oscilatorios-amortiguados-y-acoplados.pdf) | supporting files pending |
| Caída libre en medios viscosos | [`paper`](./papers/caida-libre-en-medios-viscosos.pdf) | supporting files pending |

## Repository structure

```text
Proyectos/
├── README.md
├── papers/
│   └── final academic reports
└── projects/
    ├── README.md
    ├── analisis-de-un-movimiento-en-caida-libre/
    │   ├── README.md
    │   ├── data/
    │   ├── docs/
    │   └── figures/
    ├── lanzamiento-parabolico/
    │   ├── README.md
    │   ├── data/
    │   ├── tracker/
    │   └── figures/
    ├── movimiento-aleatorio/
    │   ├── README.md
    │   ├── data/
    │   ├── figures/
    │   └── runs/
    └── resistencia-del-aire/
        ├── README.md
        ├── data/
        │   ├── raw/
        │   └── processed/
        └── analysis/
```

## Organization principles

- **Final papers** remain unchanged in `papers/`.
- **Raw measurements** are kept separate from processed results when that distinction is available.
- **Analysis code** stays with the experiment that generated it.
- **Figures and setup images** are grouped with their corresponding project.
- **Tracker and instrument-specific files** retain useful original names when changing them could break their relationship with source recordings.
- Duplicate copies are consolidated when they contain the same data.

This organization is being expanded as the remaining experimental documentation is added.

## Related project

A separate repository documents the design, simulation, implementation and experimental validation of an active three-band analog equalizer:

[`analog-3-band-equalizer`](https://github.com/paulberdi/analog-3-band-equalizer)

## Authors

**Paul Berdichewsky** · **Rafael Williams**  
Civil Engineering in Physics students  
Universidad Técnica Federico Santa María - Santiago, Chile
