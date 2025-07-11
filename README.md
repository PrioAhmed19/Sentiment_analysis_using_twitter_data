
# Sentiment Analysis of Twitter Data

This repository contains a Jupyter Notebook for performing sentiment analysis on Twitter data. The analysis includes data preprocessing, exploratory data analysis (EDA) using word frequencies and word clouds, and potentially sentiment classification.

## Project Structure

- `Sentiment_Analysis.ipynb`: The main Jupyter Notebook containing the sentiment analysis code.
- `dataset/`: (Expected) Directory for raw data. The notebook downloads `twitter_sentiment_analysis.zip` into this directory.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (install using `pip`):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - re
  - nltk
  - wordcloud

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis.git
   cd sentiment-analysis
   ```
2. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn nltk wordcloud
   ```
   *Note: You might need to download NLTK stopwords. Run the following in a Python environment or a Jupyter cell if you encounter an error:*
   ```python
   import nltk
   nltk.download('stopwords')
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Sentiment_Analysis.ipynb
   ```
2. Run all cells in the notebook. The notebook will:
   - Download the dataset (`twitter_sentiment_analysis.zip`).
   - Unzip the dataset to extract `twitter_training.csv` and `twitter_validation.csv`.
   - Perform data loading, preprocessing (lowercase conversion, regex for special characters).
   - Generate word frequency bar plots for different sentiment types.
   - Generate word clouds for positive, negative, neutral, and irrelevant sentiments.

## Data

The notebook uses two datasets:
- `twitter_training.csv`: Training data for sentiment analysis.
- `twitter_validation.csv`: Validation data for sentiment analysis.

These datasets are downloaded from a Dropbox link specified within the notebook.

## Analysis Highlights

- **Data Preprocessing**: Includes converting text to lowercase and removing special characters using regular expressions.
- **Exploratory Data Analysis (EDA)**: Visualizations of word frequencies and word clouds provide insights into the most common terms associated with different sentiment categories (Positive, Negative, Neutral, Irrelevant).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
If you need any help dont hesistate to contact at : refatahmed@iut-dhaka.edu


