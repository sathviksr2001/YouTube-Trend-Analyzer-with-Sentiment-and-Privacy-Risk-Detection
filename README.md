
# 📺 YouTube Trend Analyzer with Sentiment and Privacy Risk Detection

A comprehensive tool that analyzes trending YouTube videos by integrating sentiment analysis and privacy risk detection. This project aims to provide insights into the emotional tone of video content and assess potential privacy concerns associated with video metadata.

---

## 🚀 Features

- **Trending Video Analysis**: Fetches and displays trending YouTube videos for a specified region.
- **Sentiment Analysis**: Analyzes video titles and descriptions to determine the overall sentiment (Positive, Neutral, Negative).
- **Privacy Risk Detection**: Evaluates video metadata to identify potential privacy risks based on predefined criteria.
- **Interactive Dashboard**: Visualizes data through charts and tables for easy interpretation.

---

## 🧰 Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - NLP: `nltk`, `textblob`
  - Web Framework: `Flask` or `Streamlit`
- **APIs**:
  - YouTube Data API v3

---
## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/youtube-trend-analyzer.git
   cd youtube-trend-analyzer
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Set up YouTube Data API**:
   - Obtain an API key from the [Google Developers Console](https://console.developers.google.com/).
   - Create a `.env` file in the project root and add:
     ```
     YOUTUBE_API_KEY=your_api_key_here
     ```

4. **Run the application**:
   ```bash
   python app.py
   ```

---

## 📊 Usage

- Navigate to `http://localhost:5000/` in your browser.
- Select a region to fetch trending videos.
- View the sentiment analysis and privacy risk assessment for each video.
- Utilize interactive charts to explore data insights.

---

## 📈 Future Enhancements

- Incorporate comment analysis for a more comprehensive sentiment evaluation.
- Implement user authentication for personalized experiences.
- Expand privacy risk criteria based on evolving standards.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

Developed by **Sathvik S.R.**

For any inquiries or feedback, please contact: [SATHVIK S.R](mailto:sathviks.r2001@gmail.com)

---
