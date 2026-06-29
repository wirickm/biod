# biod-plot-demo

Hosting interactive Plotly biodistribution fit plots for PowerPoint Web Viewer embedding.

## Plot files

- **`index.html`** — 48 hour | L15 | Tumor  
  This is the published [GitHub Pages](https://wirickm.github.io/biod/) page.  
  Live URL: <https://wirickm.github.io/biod/>

- **`4_hour_A4_Liver.html`** — 4 hour | A4 | Liver

## How the HTML is generated

The HTML files are generated from Python using [Plotly](https://plotly.com/python/) (`fig.write_html()`), which embeds the interactive plot as a self-contained HTML file. Plotly is loaded from CDN (`https://cdn.plot.ly/plotly-2.35.2.min.js`).
