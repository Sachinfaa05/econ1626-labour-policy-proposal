# Australia GDP Per Capita Projection

This project visualises Australian GDP per capita from 1981 onwards and lets you stress-test alternative growth and population assumptions out to 2065. Everything runs in the browser: open `population.html` to explore the chart, adjust the controls, and compare your custom projection with the baseline scenario.

## Features
- Historical GDP per capita series derived from quarterly ABS releases.
- Baseline projection (2.0% GDP, 1.1% population) plus an adjustable scenario you can tweak in 0.1 percentage point steps.
- Clear separation between historic, baseline, and adjusted forecast lines so changes are easy to interpret.

## Data
Historical inputs come from the Australian Bureau of Statistics (ABS) via the ABS Data API:

- **Population**: Estimated Resident Population (ERP); Australia — Table code **A2133251W**.
- **GDP**: Gross domestic product, chain volume measures, seasonally adjusted — Table code **A2304402X**.

Values are prepared quarterly and stored in `data.js` for the browser chart.

## Usage
1. Download the repository or clone it locally.
2. Open `population.html` in any modern browser (no build step required).
3. Use the GDP and population growth controls to test alternative projection assumptions and compare with the baseline.

## Attribution
Created by Chris Berg, 2025 — [website](https://chrisberg.org/) · [GitHub project](https://github.com/chrisberg000/economic-growth-projection)
