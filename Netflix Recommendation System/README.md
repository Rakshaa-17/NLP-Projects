
## 🍿 Netflix Recommendation System
This project builds a content-based movie recommendation system using NLP techniques to recommend similar titles from the Netflix catalog. By analyzing show descriptions, the system suggests titles with similar themes, genres, and storylines — enhancing user discovery and engagement.

### 🎯 Objective
- Recommend Netflix movies/shows based on textual similarity
- Use natural language processing to analyze plot descriptions
- Help users find titles aligned with their viewing interests

### 🧰 Technologies Used
Programming Language:

- Python

Libraries & Tools:

- pandas, numpy – Data manipulation
- sklearn – TF-IDF vectorization and cosine similarity
- nltk – Text preprocessing (stopwords, tokenization)
- wordcloud – Visualization of common keywords
- matplotlib, seaborn – Data visualization

### 🧹 Data Preprocessing
Loaded Netflix dataset (title, type, genre, description, etc.)

- Handled missing values
- Merged relevant features (title, cast, director, genres, description)
- Cleaned text: lowercased, removed stopwords, punctuations

### 🔍 Recommendation Logic
- Converted combined text data into vectors using TF-IDF
- Measured similarity using cosine similarity
- For any selected show/movie, recommended top N similar titles

### 💡 Example 
Input: "Stranger Things"
Recommendations:

- The OA
- Dark
- Black Mirror
- The Umbrella Academy
- The Society

### 📈 Visualization
Generated a WordCloud to visualize the most frequent words in Netflix content descriptions

### 👩‍💻 Author
Developed by [Raksha](https://github.com/Rakshaa-17)

Let's connect [LinkedIn](https://www.linkedin.com/in/rakshamalela/)
