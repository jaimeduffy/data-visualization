# 📊 Data Visualization - PEC2

This project is a **static web page** developed as part of the *Data Visualization* course in the **Master's in Data Science at Universitat Oberta de Catalunya (UOC)**.

🔗 You can visit the visualization here:  
👉 https://TU-USUARIO.github.io/data-visualization/

## About

Three data visualization techniques explored:
1. **Bubble Chart** — Wealth vs. Health worldwide (Gapminder, 142 countries, 2007)
2. **Waffle Chart** — Spain's electricity generation mix 2023 (REE)
3. **Marimekko Chart** — Electricity generation by source in EU countries 2023 (Eurostat)

All visualizations were created with Python using `matplotlib` and `pywaffle`.

## Data Sources

| Chart | Source | URL |
|-------|--------|-----|
| Bubble | Gapminder.org (CC-BY) | https://www.gapminder.org/data/ |
| Waffle | Red Eléctrica de España (REE) | https://www.ree.es/es/datos/publicaciones/series-estadisticas-nacionales |
| Marimekko | Eurostat (nrg_ind_peh) | https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Electricity_and_heat_statistics |

## Project Structure

```
data-visualization/
├── data/                                       # Source datasets (CSV)
│   ├── generacion_electrica_espana_2023.csv
│   └── generacion_electrica_eu_2023.csv
├── images/                                     # Generated chart images (PNG)
│   ├── bubble_chart.png
│   ├── waffle_chart.png
│   └── marimekko_chart.png
├── src/                                        # Source code
│   └── plot_generation.ipynb
├── index.html                                  # GitHub Pages website
└── README.md
```

## How to regenerate the charts

```bash
pip install matplotlib pandas pywaffle gapminder
cd src
jupyter notebook plot_generation.ipynb
# Run all cells — images are saved to ../images/
```
