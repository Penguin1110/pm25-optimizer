# Kaohsiung PM2.5 Imputation Optimizer

Interactive browser-based optimizer for evaluating PM2.5 imputation methods
across Kaohsiung monitoring stations.

## Open

Open `work/pm25_optimizer.html` in a browser. The page contains the required
data inline and uses Leaflet from a CDN for the map.

## Rebuild

The generated HTML is built from:

- `work/stations.json`
- `work/correlations.json`
- `work/pm25_timeseries.json`

Run:

```powershell
python build_optimizer.py
```

The command regenerates `work/pm25_optimizer.html`.
