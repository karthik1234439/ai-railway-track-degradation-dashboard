# AI-Based Railway Track Degradation Prediction Dashboard

A single-page web dashboard for monitoring railway track degradation risk using AI-style predictive indicators. The dashboard uses a synthetic dataset to model segment health, risk scoring, and recommended maintenance actions.

## Features

- KPI overview for total monitored segments, critical risks, average risk level, and inspections due soon
- Regional and severity filtering
- Degradation forecast visualization
- Risk distribution donut chart
- Track segment watchlist table
- AI recommendation panel highlighting high-priority issues

## Files

- `index.html` — app layout
- `styles.css` — dashboard styling
- `app.js` — synthetic risk model and visualization logic

## Run locally

Because this project is a static frontend, you can run it with any local web server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

The dashboard is intentionally data-driven and self-contained, so it can be opened immediately without a backend or external database.
