## 📊 Laftel Playstore Review Analysis

A data-driven project focused on collecting and analyzing user reviews of the Laftel app from the Google Play Store.

### 🔍 Features
- **Automated Review Crawling** using `google-play-scraper`
- **Text Preprocessing & Tokenization** powered by `KoNLPy`
- **Quantitative Metrics**:
  - Total review count
  - Rating distribution
  - Temporal review patterns
- **Sentiment Analysis**:
  - Classifies reviews into Positive / Neutral / Negative
  - Custom dictionary integration
- **Visualizations** using `Seaborn`, `WordCloud`, and `Plotly`

### ⚙️ Tech Stack
- Language: Python  
- Environment: Jupyter Notebook  
- Libraries:  
  `selenium`, `beautifulsoup4`, `jpype1==1.4.1`, `konlpy==0.6.0`,  
  `google-play-scraper`, `seaborn`, `plotly`, `tqdm`, `wordcloud`, `pillow`

### 📝 How to Use
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
2. Run `android-playstore-crawling.ipynb` for crawling & analysis
3. View sentiment and frequency-based charts in the output cells
