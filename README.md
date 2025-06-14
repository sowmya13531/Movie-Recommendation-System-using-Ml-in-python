# 🎬 Movie Recommendation System using Machine Learning

This project is a content-based Movie Recommendation System built using Python. It suggests similar movies based on genres, keywords, cast, director, and tagline using NLP techniques.

---

## 📌 Features
- Content-based filtering
- Cosine similarity for recommendations
- TF-IDF Vectorization for text features
- Easy-to-use search for movie titles
- Outputs top similar movie recommendations

---

## 📁 Dataset
The dataset contains movie metadata including:
- Genres
- Keywords
- Tagline
- Cast
- Director

🗂 Source: Kaggle
🛠 Missing values are handled by replacing them with empty strings.

---

## 🧠 Technologies Used
- Python 🐍
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Difflib (for close match movie name search)

---

## 💡 How It Works

1. **Data Cleaning**  
   Missing values are filled with empty strings.

2. **Text Feature Engineering**  
   Selected columns are combined into a single string.

3. **Vectorization**  
   TF-IDF is applied to convert text to numeric form.

4. **Similarity Matching**  
   Cosine similarity is calculated between all movie vectors.

5. **Recommendation Output**  
   Based on user input, close movie name matches are searched and similar movies are suggested.

---

## 📸 Screenshots
### 🔍 Input Example  
![User Input](https://github.com/sowmya13531/Movie-Recommendation-System-using-Ml-in-python/blob/main/input2.png?raw=true)

For the above Input image, user entered the movie name 'interstellar'. After performing Difflib, Vectorization, Cosine similarity it will generate the recommendations as shown below.(No.of movies Recommendations depends on i value)

### 📋 Recommendations Output  
![Recommendations](https://github.com/sowmya13531/Movie-Recommendation-System-using-Ml-in-python/blob/main/output.png?raw=true)

---

## 🚀 How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/sowmya13531/Movie-Recommendation-System-using-ML-in-python.git
