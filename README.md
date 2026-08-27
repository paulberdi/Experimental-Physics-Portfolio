# Experimental Physics Projects

A growing portfolio of experimental-physics laboratory work developed during my studies at Universidad Técnica Federico Santa María (UTFSM).

This repository keeps the **original academic reports** separate from the **experimental data**, **analysis code** and **figures** used to support them. The goal is to turn each experiment into a reproducible technical project rather than keeping the repository as a collection of PDFs.

## Current reports

| Project | Document |
|---|---|
| Análisis de un movimiento en caída libre | [`paper`](./papers/analisis-de-un-movimiento-en-caida-libre.pdf) |
| Lanzamiento parabólico: contrastes entre teoría, medición experimental y modelado digital | [`paper`](./papers/lanzamiento-parabolico-contrastes-entre-teoria-medicion-experimental-y-modelado-digital.pdf) |
| Movimiento aleatorio en dos dimensiones: análisis del desplazamiento cuadrático medio y clasificación del régimen dinámico | [`paper`](./papers/movimiento-aleatorio-en-dos-dimensiones-analisis-del-desplazamiento-cuadratico-medio-y-clasificacion-del-regimen-dinamico.pdf) |
| Estudio experimental de la resistencia del aire en el movimiento de un carro sobre riel de aire | [`paper`](./papers/estudio-experimental-de-la-resistencia-del-aire-en-el-movimiento-de-un-carro-sobre-riel-de-aire.pdf) |
| Análisis experimental del comportamiento dinámico de sistemas oscilatorios amortiguados y acoplados | [`paper`](./papers/analisis-experimental-del-comportamiento-dinamico-de-sistemas-oscilatorios-amortiguados-y-acoplados.pdf) |
| Caída libre en medios viscosos | [`paper`](./papers/caida-libre-en-medios-viscosos.pdf) |

## Repository structure

```text
Proyectos/
├── README.md
├── papers/
│   ├── analisis-de-un-movimiento-en-caida-libre.pdf
│   ├── lanzamiento-parabolico-contrastes-entre-teoria-medicion-experimental-y-modelado-digital.pdf
│   ├── movimiento-aleatorio-en-dos-dimensiones-analisis-del-desplazamiento-cuadratico-medio-y-clasificacion-del-regimen-dinamico.pdf
│   ├── estudio-experimental-de-la-resistencia-del-aire-en-el-movimiento-de-un-carro-sobre-riel-de-aire.pdf
│   ├── analisis-experimental-del-comportamiento-dinamico-de-sistemas-oscilatorios-amortiguados-y-acoplados.pdf
│   └── caida-libre-en-medios-viscosos.pdf
├── data/
│   └── README.md
├── analysis/
│   └── README.md
└── figures/
    └── README.md
```

## Reproducibility plan

For each experiment, the repository will preserve:

- **Raw data** exactly as measured.
- **Processed data** generated from documented analysis steps.
- **Analysis scripts** used for calculations, regressions, uncertainty analysis and visualization.
- **Figures** selected for presentation and comparison with physical models.
- **Original report** as the final academic document submitted for the experiment.

This separation makes it possible to reproduce the analysis without altering the source measurements.

## Related project

A separate repository documents the design, simulation, implementation and experimental validation of an active three-band analog equalizer:

[`analog-3-band-equalizer`](https://github.com/paulberdi/analog-3-band-equalizer)

## Authors

**Paul Berdichewsky** · **Rafael Williams**  
Civil Engineering in Physics students  
Universidad Técnica Federico Santa María - Santiago, Chile
