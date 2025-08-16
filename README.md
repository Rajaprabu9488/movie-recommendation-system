# 🎬 Movie Recommendation System

A machine learning-based movie recommendation system that suggests movies to users based on clustering techniques. This project uses **Scikit-learn** and the **K-Means clustering algorithm** to group similar movies and recommend them effectively.

---

## 🚀 Features
- **Content-based recommendations** using movie features.
- **K-Means clustering** for grouping similar movies.
- Implemented using **Python** and **Scikit-learn**.
- Easy to customize for different datasets.

---

## 🛠 Tech Stack
- **Python 3.10.8**
- **Jupyter Notebook** – for interactive development
- **Libraries**:
  - `scikit-learn` – for K-Means clustering
  - `pandas` – for data manipulation
  - `numpy` – for numerical operations
  - `matplotlib / seaborn` – for visualization 

---

## 📂 Project Structure
movie-recommendation-system/
│
├── dataset/
│ └── movies.csv # Movie dataset
├── movie_recommender.py # Main Python script
└── README.md # Project documentation

---

## 📊 Dataset
- The dataset should include movie details such as:
  - **tmdb_id**
  - **title**
  - **cast**
  - **crew**

---

## 🔍 How It Works
1. Load and preprocess the dataset.
2. Convert textual features into numerical vectors using **TF-IDF**.
3. Apply **K-Means clustering** to group similar movies.
4. For a given movie, find the cluster it belongs to and recommend other movies from the same cluster.

---

## ▶️ Installation & Usage
### 1. Clone the repository:
```bash
git clone https://github.com/Rajaprabu9488/movie-recommendation-system.git
cd movie-recommendation-system

### **2. Run the recommendation script:**
```bash
python movie_recommender.py

### Example Output:
```bash
your movie is founded : karate kid: legends
recommended for u:
1   snow white
2   taandob
3   kiff lore of the ring light
4   3ão: an endless story
5   utopia
6   candle in the tomb: the worm valley
7   crazy lizard
8   possessions
9   diablo
10   mikaela
11   laila
12   predator: killer of killers
13   kayara
14   hunt the wicked
15   fear below
16   mikaela
17   the ugly stepsister
18   párvulos: children of the apocalypse
19   life after fighting

