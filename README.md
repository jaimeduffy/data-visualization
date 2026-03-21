# Visualización de Datos - PEC 2

Página web estática desarrollada como parte de la asignatura de *Visualización de Datos* del **Máster en Ciencia de Datos de la UOC**.

🔗 Visualización publicada en: https://jaimeduffy.github.io/data-visualization/

## Técnicas exploradas

1. **Gráfico de Burbujas (Bubble Chart)** — Riqueza vs. Salud en el mundo (Gapminder, 142 países, 2007)
2. **Gráfico de Gofre (Waffle Chart)** — Mix de generación eléctrica en España 2023 (REE)
3. **Gráfico de Marimekko (Marimekko Chart)** — Generación eléctrica por fuente en países de la UE 2023 (Eurostat)

## Fuentes de datos

| Gráfico | Fuente | Enlace |
|---------|--------|--------|
| Bubble Chart | Gapminder.org (CC-BY) | https://www.gapminder.org/data/ |
| Waffle Chart | Red Eléctrica de España (REE) | https://www.ree.es/es/datos/publicaciones/series-estadisticas-nacionales |
| Marimekko Chart | Eurostat (nrg_ind_peh) | https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Electricity_and_heat_statistics |

## Regenerar los gráficos

```bash
pip install matplotlib pandas pywaffle gapminder
cd src
jupyter notebook plot_generation.ipynb
```

Ejecutar todas las celdas genera las imágenes en `images/`.

## Herramientas utilizadas

- Python (matplotlib, pywaffle)
- Paleta de colores: [Coolors](https://coolors.co/264653-2a9d8f-e9c46a-f4a261-e76f51)