# Experimental Physics Projects

A growing portfolio of experimental-physics laboratory work developed during my studies at Universidad Técnica Federico Santa María (UTFSM).

This repository is organized to keep the **original academic reports** separate from the **experimental data**, **analysis code** and **figures** used to support them. The goal is to turn each experiment into a reproducible technical project rather than keeping the repository as a collection of PDFs.

## Current reports

| Report | Document |
|---|---|
| Free fall in viscous media | [`papers/free-fall-viscous-media.pdf`](./papers/free-fall-viscous-media.pdf) |
| FIS200 - Report 01 | [`papers/fis200-report-01.pdf`](./papers/fis200-report-01.pdf) |
| FIS200 - Report 02 | [`papers/fis200-report-02.pdf`](./papers/fis200-report-02.pdf) |
| FIS200 - Report 03 | [`papers/fis200-report-03.pdf`](./papers/fis200-report-03.pdf) |
| FIS200 - Report 04 | [`papers/fis200-report-04.pdf`](./papers/fis200-report-04.pdf) |
| FIS200 - Report 06 | [`papers/fis200-report-06.pdf`](./papers/fis200-report-06.pdf) |

The free-fall report is explicitly identified by its original title. The remaining reports are currently indexed by their original FIS200 report numbers; their descriptive project titles will be added when their supporting material is incorporated.

## Repository structure

```text
Proyectos/
├── README.md
├── papers/
│   ├── free-fall-viscous-media.pdf
│   ├── fis200-report-01.pdf
│   ├── fis200-report-02.pdf
│   ├── fis200-report-03.pdf
│   ├── fis200-report-04.pdf
│   └── fis200-report-06.pdf
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

## Author

**Paul Berdichewsky**  **Rafael Williams**
Civil Engineering in Physics student  
Universidad Técnica Federico Santa María - Santiago, Chile
