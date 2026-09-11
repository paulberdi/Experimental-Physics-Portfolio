# Temperature Sensor Calibration: PT100 and Gas Manometer

Experimental calibration of two temperature-dependent systems: a **PT100 resistance temperature detector** and an **air-filled bulb connected to a mercury U-tube manometer**.

The experiment was carried out for *Fundamentos de Termodinámica Aplicada (ICF 130)* at Universidad Técnica Federico Santa María. Temperature was measured using a thermocouple as reference while the PT100 resistance and the mercury-column levels were recorded over a broad temperature range.

## Objectives

- Calibrate a PT100 by determining the relationship between electrical resistance and temperature.
- Determine the PT100 temperature coefficient from the experimental linear fit.
- Measure the pressure change of confined air using a mercury manometer.
- Compare the experimental pressure-temperature relationship with the prediction of an ideal gas under an isochoric assumption.
- Quantify measurement uncertainties and propagate them to derived quantities.

## Experimental setup

Two measurements were performed in parallel:

1. **PT100 calibration** — the PT100 and reference thermocouple were immersed in thermal baths while the sensor resistance was measured with a multimeter.
2. **Gas manometer** — an air-filled bulb was connected to a mercury U-tube. The bulb was immersed in the same thermal baths and the heights of both mercury columns were measured.

The manometer pressure was calculated from

$$
P_{gas}=P_{atm}+\rho g\Delta h,
$$

with

$$
\Delta h=h_{right}-h_{left}.
$$

For the PT100, the linear approximation was

$$
R(T)=R_0[1+\alpha(T-T_0)].
$$

## Data analysis

The complete analysis was implemented in Python using **NumPy**, **SciPy** and **Matplotlib**. The script:

- calculates $\Delta h$ and absolute gas pressure;
- propagates the instrumental uncertainty of both mercury-height measurements;
- performs independent linear regressions for $R(T)$, $\Delta h(T)$ and $P(T)$;
- estimates the PT100 temperature coefficient $\alpha$;
- generates plots with experimental uncertainty bars;
- compares the experimental $P(T)$ trend with an ideal-gas isochoric prediction.

## Main results

### PT100

$$
R(T)=(0.3546\pm0.0043)T+(98.2905\pm0.3192)\ \Omega
$$

$$
R^2=0.99095
$$

and

$$
\alpha=(3.61\pm0.05)\times10^{-3}\ ^\circ\mathrm{C}^{-1}.
$$

The PT100 showed a strongly linear response throughout the measured range.

### Mercury manometer

$$
\Delta h(T)=(0.1177\pm0.0032)T-(4.9160\pm0.2343)\ \mathrm{cm}
$$

with

$$
R^2=0.95724.
$$

The propagated uncertainty in the height difference was

$$
\sigma_{\Delta h}=0.0707\ \mathrm{cm}.
$$

### Gas pressure

$$
P(T)=(0.1569\pm0.0042)T+(94.7687\pm0.3125)\ \mathrm{kPa}
$$

with

$$
R^2=0.95724.
$$

The propagated pressure uncertainty was approximately

$$
\sigma_P=0.0943\ \mathrm{kPa}.
$$

The experimental pressure slope was lower than the ideal isochoric prediction. The report discusses three main experimental effects: the system was not perfectly isochoric because the gas displaced the mercury, part of the gas occupied tubing outside the thermal bath (dead volume), and the mercury itself was not maintained at a uniform constant temperature.

## Repository contents

```text
calibracion-sensores-temperatura/
├── README.md
├── data/
│   └── experimental_data.csv
└── src/
    └── analysis.py
```

- [`data/experimental_data.csv`](./data/experimental_data.csv) contains the experimental measurements and calculated pressure values in a portable text format.
- [`src/analysis.py`](./src/analysis.py) reproduces the regressions, uncertainty propagation and plots used in the experiment.

## Authors

**Paul Berdichewsky** · **Benjamín Arancibia**  
Universidad Técnica Federico Santa María — Santiago, Chile
