# COMP-3610-Assignment2
816042173

---

## Project Structure

```
├── A2.ipynb           # Main notebook
├── requirements.txt         # Pinned dependencies
├── README.md                # This file
└── data/
    └── raw/
        ├── yellow_tripdata_2024-01.parquet   # Trip data (auto-downloaded)
        └── taxi_zone_lookup.csv              # Zone/borough lookup (auto-downloaded)
```

---

## Setup

### 1. Install dependencies

```bash
pip install -r requirements.txt
```


### 2. Run the notebook

```bash
jupyter notebook A2.ipynb
```

---

## Data Sources

| File | Source | Description |
|------|--------|-------------|
| `yellow_tripdata_2024-01.parquet` | [TLC Trip Data](https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2024-01.parquet) | NYC Yellow Taxi trips, January 2024 |
| `taxi_zone_lookup.csv` | [TLC Zone Lookup](https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv) | Maps LocationID to Borough |

---
