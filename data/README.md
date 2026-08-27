# Data

This directory is reserved for the experimental datasets associated with the reports in this repository.

Recommended organization for each experiment:

```text
data/
└── experiment-name/
    ├── raw/        # Original measurements, unchanged
    └── processed/  # Cleaned or derived datasets
```

Whenever possible, raw measurements should be preserved without modification and processing steps should be reproducible from scripts stored in `analysis/`.
