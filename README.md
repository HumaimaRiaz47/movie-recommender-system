# 🎬 Movie Recommender System

An intelligent content-based **Movie Recommender System** built using **Python, Machine Learning, and Streamlit**.  
It suggests movies similar to a user-selected movie based on content similarity and displays posters fetched via **The Movie Database (TMDb) API**.

---

## 📸 Project Preview

<img width="1000" height="703" alt="Screenshot 2025-11-08 000401" src="https://github.com/user-attachments/assets/7be08e6f-47ad-4497-a39a-e76a96a9e5e3" />
<img width="1000" height="703" alt="Screenshot 2025-11-08 000415" src="https://github.com/user-attachments/assets/5ad014a6-061e-4475-889b-5fe337489a04" />
<img width="1000" height="703" alt="Screenshot 2025-11-08 000444" src="https://github.com/user-attachments/assets/a693d6c5-61ed-4f7e-a870-8c315a2a206f" />
<img width="1000" height="703" alt="Screenshot 2025-11-08 000509" src="https://github.com/user-attachments/assets/879c84cb-a97b-4069-97b3-16adcd1729f7" />

---

## 🧠 Features

- 🎯 **Content-Based Recommendation:** Suggests similar movies using cosine similarity  
- 🖼️ **Real-Time Posters:** Fetches posters dynamically from TMDb API  
- ⚡ **Interactive UI:** Built using Streamlit for smooth and fast interaction  
- 🧩 **Preprocessed Data:** Uses a pickled model for quick loading and prediction

---

## 🔗 Dataset

📊 **Dataset Name:** TMDB 5000 Movie Dataset  
📁 **Source:** (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally 👇

```bash
# 1️⃣ Clone the repository
git clone https://github.com/HumaimaRiaz47/movie-recommender-system.git

# 2️⃣ Navigate to the project directory
cd movie-recommender-system

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the Streamlit app
python -m streamlit run application.py
```
--

## 🧮 How It Works

1. The dataset is preprocessed to extract important features like **genres, keywords, cast, and crew**.  
2. These features are combined and vectorized using **CountVectorizer**.  
3. **Cosine similarity** is computed to find movies with the closest feature vectors.  
4. When you select a movie, it recommends the **top 5 most similar ones** along with their posters.

---

## 🛠️ Tech Stack

| Technology       | Purpose                          |
|-----------------|----------------------------------|
| Python           | Core programming language         |
| Streamlit        | Web app framework                |
| Scikit-learn     | Vectorization & similarity computation |
| Pandas / NumPy   | Data processing                  |
| Pickle           | Model serialization              |
| Requests         | API calls to TMDb                |


---

## 👩‍💻 Author

**Humaima Riaz**  
🎓 Computer Systems Engineering Student  
💡 Passionate about AI, ML, and Full-Stack Development  
🌐 [GitHub Profile](https://github.com/HumaimaRiaz47)

---

## 🪪 License

This project is licensed under the **MIT License**.  
You are free to **use, modify, and distribute** this project with proper attribution.

