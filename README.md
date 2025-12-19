A data analytics case study using clustering to explore regional demand patterns in the global video game market.

# Video Game Sales Analytics

Portfolio-ready analytics project that explores **global video game sales** and uses **K-means clustering** and **PCA** to identify regional market patterns.

## Objective
Identify clusters of games based on regional sales performance (NA, EU, JP, Other) and interpret what those clusters imply for market strategy.

## What’s inside
- `notebooks/video_game_sales_clustering.ipynb` — end-to-end analysis (cleaning → clustering → PCA viz → cluster profiles)
- `requirements.txt` — Python dependencies
- `data/README.md` — where to place the dataset

## How to run
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Place `vgsales.csv` in `data/` (or update `CSV_PATH` in the notebook), then open the notebook and run all cells.

## Skills demonstrated
Python, pandas, scikit-learn, clustering, PCA visualization, analytical storytelling
