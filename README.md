# YouTube Trending Videos — EDA

Exploratory Data Analysis of the Kaggle **YouTube Trending** dataset.

## Project Structure
```
youtube_eda_project/
├─ data/                 # put CSV/JSON from Kaggle here (ignored by Git)
├─ youtube_eda.ipynb     # main notebook
├─ requirements.txt
└─ .gitignore
```

## How to Run (VS Code)
1. Open this folder in VS Code.  
2. Create and select a virtual environment (recommended):
```
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```
3. Download files from Kaggle (e.g., `USvideos.csv` and `US_category_id.json`) into the `data/` folder.  
4. Open `youtube_eda.ipynb`, set `COUNTRY = "US"` and run all cells (top → bottom).

## Notes
- The notebook maps `category_id` to category titles using the country JSON file.
- Engagement metrics included: `like_ratio`, `comment_rate`, `tags_count`.
- Visualizations: category views, views vs likes, top videos, publish hour/weekday, like ratio by category.