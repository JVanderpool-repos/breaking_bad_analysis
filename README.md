# Breaking Bad Data Analysis

This project analyzes the IMDb ratings and viewership of all episodes of Breaking Bad using a dataset from [Kaggle](https://www.kaggle.com/datasets/varpit94/breaking-bad-tv-show-all-seasons-episodes-data).

## Project Overview
- **Data Cleaning:** Standardized column names, converted date columns, and filled missing values in viewership.
- **Feature Engineering:** Created combined 'Season Episode' and extracted season numbers for better analysis and visualization.
- **Analysis:**
  - Plotted IMDb ratings by episode and by season.
  - Plotted viewership trends across episodes.
- **Findings:**
  - IMDb ratings generally increased in later seasons, with several episodes rated exceptionally high.
  - Viewership peaked in the final season, indicating growing popularity.

## How to Run
1. Clone the repository.
2. Create a virtual environment:
   ```sh
   python -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows:
     ```sh
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source venv/bin/activate
     ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Open `breaking_bad.ipynb` in Jupyter or VS Code and run the cells.

## Potential Future Iterations
- **Character Analysis:** Analyze which characters appear in the highest-rated episodes.
- **Writer/Director Impact:** Explore if certain writers or directors are associated with higher ratings.
- **Sentiment Analysis:** Perform sentiment analysis on episode summaries (if available) to correlate with ratings.
- **Time Series Forecasting:** Predict future ratings or viewership trends using time series models.

## License
This project is for educational purposes only. Data is sourced from Kaggle.
