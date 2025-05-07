## Project Structure

```
project/
├── README.md
├── .Rproj
├── data/
│   ├── raw/               # Original untouched data
│   ├── interim/           # Cleaned or lightly processed data
│   └── processed/         # Final datasets ready for analysis/modeling
├── notebooks/             # Ad hoc explorations, EDA, notes
├── scripts/
│   ├── data_cleaning/     # Scripts for transforming raw → interim
│   ├── processing/        # Scripts for transforming interim → processed
│   └── analysis/          # Scripts for modeling, stats, visualizations
├── outputs/
│   ├── figures/           # Final plots
│   ├── tables/            # CSVs, XLSXs for reports
│   └── reports/           # PDF/HTML reports or slides
├── models/                # Saved models (if applicable)
└── utils/                 # Reusable functions or helpers
```