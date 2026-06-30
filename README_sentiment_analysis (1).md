# Social Media Sentiment Analysis

A sentiment analysis project that analyzes social media posts to determine emotional tone and public opinion, using rule-based methods (TextBlob, VADER) and machine learning models (Logistic Regression, Naive Bayes, SVM).

## 🎯 Project Overview

This project performs sentiment analysis on social media data using multiple approaches:

- **Rule-based methods**: TextBlob and VADER
- **Machine learning models**: Logistic Regression, Naive Bayes, and SVM
- **Comprehensive analysis**: Text preprocessing, feature extraction, and model comparison

## 📊 Key Features

- **Multi-method Analysis**: Compare different sentiment analysis approaches
- **Interactive Dashboard**: Streamlit web app for exploring results
- **Exploratory Data Analysis**: Jupyter notebook covering data cleaning, feature extraction, and visualization
- **Configurable Pipeline**: Centralized settings via `config.py`

## 🛠️ Technologies Used

- **Python**: Main programming language
- **NLTK, TextBlob, VADER**: Sentiment analysis libraries
- **scikit-learn**: Machine learning models
- **Pandas & NumPy**: Data manipulation and analysis
- **Streamlit**: Interactive web dashboard
- **Jupyter Notebook**: Exploratory analysis

## 📁 Project Structure

```
Sentiment-analysis-on-social-media/
│
├── streamlit_app.py          # Interactive web dashboard (main entry point)
├── data_exploration.ipynb    # Exploratory data analysis & model comparison
├── config.py                 # Configuration settings
├── setup.py                  # Package setup
├── requirements.txt          # Python dependencies
├── LICENSE
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

```bash
git clone https://github.com/varmakbm9-gif/Sentiment-analysis-on-social-media.git
cd Sentiment-analysis-on-social-media
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### Usage

**Run the interactive dashboard:**
```bash
streamlit run streamlit_app.py
```

**Explore the analysis step-by-step:**
```bash
jupyter notebook data_exploration.ipynb
```

## 📈 Sample Results

- **Logistic Regression**: 85% accuracy
- **Naive Bayes**: 82% accuracy
- **SVM**: 83% accuracy
- **TextBlob**: 75% accuracy
- **VADER**: 72% accuracy

## 🚀 Future Enhancements

- [ ] Real-time analysis via Twitter/Reddit APIs
- [ ] Deep learning model (BERT/RoBERTa)
- [ ] Multi-language support
- [ ] Cloud deployment (AWS/GCP)

## 📚 Learning Outcomes

This project demonstrates proficiency in:

- NLP techniques and text preprocessing
- Machine learning model training and evaluation
- Building interactive dashboards with Streamlit
- Clean, modular Python code structure

⭐ **Star this repository if you found it helpful!**
