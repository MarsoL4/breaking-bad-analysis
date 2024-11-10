
# Breaking Bad Episodes Analysis

This project presents an exploratory data analysis (EDA) and clustering of episodes from the popular TV series **Breaking Bad**. By analyzing variables such as IMDb ratings and U.S. viewership, the goal is to uncover patterns and group episodes with similar characteristics.

## Project Objectives
- Conduct a comprehensive exploratory analysis on Breaking Bad episodes.
- Apply an unsupervised learning model (K-Means clustering) to group episodes.
- Interpret clusters to provide insights into audience reception and episode popularity.

## Data Description
The dataset contains information on:
- **Season and Episode**: Season and episode numbers.
- **Title**: Title of each episode.
- **Duration**: Episode duration in minutes.
- **IMDb Rating**: User ratings from IMDb.
- **U.S. Viewers (in millions)**: Audience size in the United States.

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**: Initial data exploration to understand the structure and key statistics of the dataset.
2. **Data Cleaning**: Handling missing values and standardizing the data for analysis.
3. **Visualization**: Graphical representations, including bar charts, scatter plots, and histograms, to illustrate data distributions and relationships.
4. **Clustering**: Application of K-Means clustering on IMDb ratings and viewership to group similar episodes.

## Technologies Used
- **Python**: Main programming language.
- **pandas**: Data manipulation and analysis.
- **matplotlib** and **seaborn**: Data visualization.
- **scikit-learn**: Data preprocessing and K-Means clustering.

## Running the Project
To run this project locally:
1. Ensure that you have Python and Jupyter Notebook installed.
2. Clone the repository and navigate to the project folder.
3. Open the Jupyter Notebook file (`Enhanced_AnaliseExploratoria_BreakingBad.ipynb`) and run the cells sequentially.

Alternatively, you can use [Google Colab](https://colab.research.google.com/) to execute the notebook directly in your browser.

## Results and Insights
The clustering analysis reveals three main groups of episodes:
- **Cluster 0**: Episodes with moderate ratings and viewership.
- **Cluster 1**: Highly-rated episodes with high audience engagement, often major plot events.
- **Cluster 2**: Episodes with lower ratings and viewership.

These insights provide an understanding of what drives audience interest and episode popularity in Breaking Bad.

---

Feel free to explore the notebook and modify the analysis to discover additional insights!
