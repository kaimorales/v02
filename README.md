# Vo2

**Research-grade N-of-1 wearable health data analysis**  

VO2 transforms months of wearable device data (WHOOP, Oura, Garmin) into rigorous N-of-1 studies. Statistical analyses powered by research-grade methods, interpreted by an AI assistant grounded in real sports science literature via RAG.

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

