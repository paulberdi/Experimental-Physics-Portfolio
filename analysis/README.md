# Analysis

This directory is reserved for reproducible analysis code associated with the experiments documented in `papers/`.

Each experiment can have its own subdirectory, for example:

```text
analysis/
└── experiment-name/
    ├── README.md
    └── analysis.py
```

Scripts should read experimental measurements from `data/` and generate derived quantities, plots or tables without modifying the original raw data.
