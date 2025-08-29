# 📚 AI-Powered Book Recommendation System

**An intelligent book discovery platform combining semantic search, emotion analysis, and interactive visualizations to help readers find their perfect next read.**

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge)](https://huggingface.co/)
[![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge)](https://langchain.com/)

## 🌟 Features

### 🧠 **Semantic Search**
- **Vector-based recommendations** using sentence transformers and ChromaDB
- **Natural language queries** - describe what you want to read in plain English
- **Intelligent similarity matching** beyond simple keyword searches

### 💭 **Emotion Analysis**
- **7 emotion categories** analyzed per book: joy, sadness, anger, fear, surprise, disgust, neutral
- **Emotion-based filtering** - find books that match your mood
- **Sentiment visualization** with interactive charts and heatmaps

### 📊 **Interactive Analytics**
- **Real-time data insights** with Plotly visualizations
- **Category distribution** and rating analysis
- **Feature correlation heatmaps**
- **Statistical summaries** of the entire dataset

### 🔍 **Smart Filtering**
- Filter by **genre, rating, page count**
- **Random book discovery** for serendipitous finds
- **Multi-criteria search** combining semantic and traditional filters

## 🛠️ Technology Stack

- **Frontend**: Streamlit (Interactive web app)
- **Machine Learning**: 
  - Hugging Face Transformers (Emotion analysis)
  - Sentence Transformers (Semantic embeddings)
  - BART model for zero-shot classification
- **Vector Database**: ChromaDB for similarity search
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly, Seaborn, Matplotlib
- **NLP Pipeline**: LangChain for document processing

## 📦 Dataset

- **7,000+ books** with comprehensive metadata
- **Rich descriptions** for semantic analysis
- **Emotion scores** computed using DistilRoBERTa model
- **Categories**: Fiction, Non-fiction, Children's books, and more
- **Ratings, page counts, publication years** for comprehensive filtering

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/book-recommendation-system.git
cd book-recommendation-system
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
streamlit run book_app.py
```

### 4. Open in Browser
Visit `http://localhost:8501` to start discovering books!

## 📊 Data Processing Pipeline

1. **Data Cleaning**: Missing value imputation, feature engineering
2. **Category Classification**: BART-based genre prediction for unlabeled books
3. **Emotion Analysis**: Sentence-level emotion scoring using DistilRoBERTa
4. **Vector Embeddings**: Semantic representations using MiniLM
5. **Search Index**: ChromaDB vector database for fast similarity search

## 🎯 Use Cases

- **Personal Reading**: Find books matching your mood or interests
- **Book Clubs**: Discover discussion-worthy titles with specific themes
- **Educators**: Locate books with appropriate emotional content for students
- **Researchers**: Analyze emotional patterns in literature across genres
- **Developers**: Learn semantic search and emotion analysis implementation

## 📈 Key Insights

- **Fiction vs Non-fiction** distribution analysis
- **Emotion patterns** across different book categories
- **Rating correlations** with book features and emotions
- **Length preferences** by genre and rating

## 🔧 Configuration

The app automatically detects available data files:
- `books_with_emotions.csv` (complete dataset with emotion analysis)
- `books_with_categories.csv` (with genre classification)  
- `books_cleaned.csv` (basic cleaned dataset)

## 🌐 Deployment

### Streamlit Community Cloud (Recommended)
1. Push to GitHub
2. Visit [share.streamlit.io](https://share.streamlit.io)
3. Connect repository and deploy

### Alternative Platforms
- **Render**: Full-stack deployment with custom domains
- **Railway**: Auto-deployment with GitHub integration
- **Heroku**: Classic cloud platform (requires Procfile)

## 📚 Project Structure

```
book-recommendation-system/
├── book_app.py              # Main Streamlit application
├── data_processing.py       # Complete data pipeline
├── requirements.txt         # Python dependencies
├── books_with_emotions.csv  # Processed dataset
├── chroma_db/              # Vector database (if available)
├── README.md               # Project documentation
└── notebooks/              # Jupyter analysis notebooks
```

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Additional emotion models or sentiment analysis
- More sophisticated recommendation algorithms
- UI/UX enhancements
- Performance optimizations
- New visualization types

## 📄 License

MIT License - feel free to use this project for learning or commercial purposes.

## 🙏 Acknowledgments

- **Dataset**: 7K Books with Metadata by Dylan Castillo on Kaggle
- **Hugging Face**: For pre-trained transformer models
- **Streamlit**: For the amazing web app framework
- **LangChain**: For document processing utilities

## 📞 Contact

- GitHub: [@](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com
- `

---

**⭐ Star this repository if you found it helpful!**

**🔗 [Live Demo](https://your-app-name.streamlit.app/)** | **📖 [Documentation](https://github.com/yourusername/book-recommendation-system/wiki)** | **🐛 [Report Bug](https://github.com/yourusername/book-recommendation-system/issues)**
