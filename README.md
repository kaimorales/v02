# Vo2

**Research-grade N-of-1 wearable health data analysis**  

Vo2, a research-grade N-of-1 wearable health analysis system designed for people to run real experiments on themselves.

Most health research is broad, relying on large sample sizes, population averages, and randomized protocols that do not always reflect what works for a specific individual. Vo2 flips that model.

Vo2 converts long-term WHOOP, Oura, and Garmin data into statistically valid personal studies using changepoint detection, multiple-testing-corrected correlation analysis, and a RAG-based AI assistant grounded in peer-reviewed medical literature. This allows users to identify what actually changes their physiology, not the average person’s.


## What It Does

- **Changepoint Detection** (PELT algorithm via ruptures) -- identifies when your metrics meaningfully shifted
- **Correlation Analysis** with Benjamini-Hochberg FDR correction -- real statistical rigor, not just p-hacking
- **AI Research Assistant** -- RAG pipeline with 18 embedded PubMed papers on HRV, sleep architecture, overtraining, and recovery
- **CSV Upload + Column Mapping** -- bring your own WHOOP/Oura/Garmin data
- **Publication-Quality Visualizations** -- Plotly plots with confidence intervals, changepoint markers, significance annotations

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 16, TypeScript, Tailwind CSS, Shadcn/ui |
| Visualizations | Plotly.js (scientific plots), Recharts |
| Backend | Python FastAPI |
| Statistics | ruptures, scipy, statsmodels, pingouin, scikit-learn |
| RAG Pipeline | sentence-transformers (all-MiniLM-L6-v2), ChromaDB, Anthropic Claude |
| Research DB | curated PubMed papers on sports science, HRV, sleep, and overtraining |

## Code

- Full code has been made private. This repo is just to host a demo video.

## Authors

- Kai Morales, Daniel Nguyen, Lalit More



