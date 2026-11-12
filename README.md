# Mohammed Muayad — Dark Signal Portfolio

A static portfolio showcasing AI engineering, data analytics and the Factory Sensor Telemetry project, published at https://mohadmuayad.github.io/.

Built with HTML, CSS and vanilla JavaScript; no build step is required.

## Local preview

From the repository root, run:

```bash
python -m http.server 8000
```

Visit `http://127.0.0.1:8000/index.html`. Alternatively, open `index.html` with VS Code Live Server. Use HTTP, not `file://`, because internal page navigation uses `fetch`.

## Site files

- `index.html` — homepage and projects
- `factory.html` — Factory Sensor Telemetry case study
- `factory/index.html` — redirect to the case study
- `404.html` — page-not-found page
- `app.js` — shared interactions and soft navigation
- `style.css` — global styling
- `notebooks/01_data_quality_analysis.html` — Data Quality and Exploratory Analysis notebook reader
- `notebooks/02_data_cleaning_validation.html` — Data Cleaning and Validation notebook reader
- `notebooks/notebook.css` — notebook styling
- `notebooks/notebook.js` — notebook interactions
- `experiment/experience.css` — shared experience styling
- `experiment/experience.js` — shared experience effects
- `experiment/disclosure-motion.js` — disclosure motion
- `experiment/industrial-intelligence.css` — shared project styling
- `experiment/site-navigation.css` — site navigation styling
- `experiment/site-navigation.js` — site navigation interactions
- `assets/` — portrait, graphics, and English / Arabic PDF reports
- `downloads/` — original notebooks and project archive
- `.nojekyll` — GitHub Pages configuration
- `robots.txt` — crawler instructions
- `sitemap.xml` — site page URLs

## Reuse

Portfolio and project images, reports and text are retained as supplied, with no new reuse license.
