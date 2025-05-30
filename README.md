📊 # 1. Financial Analysis Data 
This project combines descriptive and statistical analysis of financial datasets — including financial news headlines and historical stock prices — to uncover insights using Python. The notebook performs data loading, cleaning, exploratory data analysis (EDA), sentiment analysis, technical indicators, and rich visualizations.

📁 Overview
This Jupyter Notebook suite covers two major areas of financial data analysis:

Financial News Analysis:
Analyzes a dataset of financial news headlines to explore publishing trends, headline statistics, and perform sentiment classification.

Stock Market Statistical Analysis:
Conducts descriptive statistics and technical analysis on historical stock price data from major tech companies including AAPL, GOOG, AMZN, META, MSFT, NVDA, and TSLA.

✨ Features
📰 Financial News Analysis
Load and preview financial news headlines (raw_analyst_ratings.csv)

Calculate headline length statistics (mean, median, min, max, etc.)

Analyze article publication trends (by date, day of the week)

Perform sentiment analysis using TextBlob

Visualize:

Sentiment distribution

Article frequency

Headline statistics

📈 Stock Market Analysis
Load historical price data from Yahoo Finance

Clean missing values and preprocess datasets

Compute key statistics: mean, standard deviation, min, max, quartiles

Create rich visualizations with Matplotlib and Plotly

Apply technical indicators using TA-Lib

Integrate basic sentiment analysis for qualitative insights

🧰 Dependencies
Ensure the following Python packages are installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn textblob plotly yfinance
Optional:
TA-Lib: For technical analysis

⚠️ Note: Installing TA-Lib may require additional system-specific setup. Refer to TA-Lib Installation Guide.

📂 Dataset Descriptions
1. News Headlines Dataset
Located at: ../data/raw/raw_analyst_ratings.csv
Columns:

Unnamed: 0: Index

headline: News title

url: Article link

publisher: Source

date: Publication datetime

stock: Ticker symbol

2. Stock Market Data
Fetched from Yahoo Finance using tickers like AAPL, GOOG, etc.
Columns include:

Open, High, Low, Close, Adj Close, Volume

Dividend & Split metadata (if available)

📊 Example Outputs
📌 Headline Stats:

Mean Length: 73.12 characters

Max Length: 512 characters

📌 Top Publication Day:

March 12, 2020: 1766 articles

📌 Sentiment Breakdown:

Classified as Positive, Negative, or Neutral using polarity scores

📌 Stock Data Insights:

Summary tables of daily price stats

Technical indicators (RSI, MACD, etc.)

Time series charts of trends

▶️ Usage
bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/your-username/financial-analysis-suite.git
cd financial-analysis-suite

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open Jupyter Lab or Notebook
jupyter lab
🧪 Customization
To analyze more stocks or new headlines:

Add new tickers in the stock data loader section.

Replace the input CSV for headlines with any similarly structured dataset.

The pipeline will automatically adapt for:

Descriptive statistics

Sentiment analysis

Visualizations

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to improve or add.

📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and distribute with proper attribution.

📬 Contact
For feedback or questions, please open an issue or contact the maintainer.
You can also reach out via gworku3654@gmail.com
