# 🎬 Netflix Movies & TV Shows Clustering using Unsupervised Machine Learning

## 📌 Project Overview

With the rapid growth of streaming platforms, Netflix has accumulated thousands of movies and TV shows across different genres, languages, and countries. Organizing this vast content library and providing personalized recommendations is a major challenge.

This project applies **Unsupervised Machine Learning** techniques to cluster similar Netflix titles based on their textual information. By leveraging Natural Language Processing (NLP), feature engineering, dimensionality reduction, and clustering algorithms, the project discovers hidden patterns in the Netflix catalog that can be used for recommendation systems and content categorization.

---

## 🎯 Problem Statement

The objective of this project is to cluster similar Netflix Movies and TV Shows based on their metadata and descriptions without using predefined labels.

The project aims to:

- Discover hidden patterns within Netflix content.
- Group similar titles together.
- Improve recommendation systems.
- Help users discover similar content efficiently.
- Demonstrate the application of NLP with Unsupervised Machine Learning.

---

## 💼 Business Context

Netflix hosts thousands of titles from different countries and genres. As the platform continues to grow, recommending relevant content becomes increasingly challenging.

Clustering helps Netflix:

- Improve personalized recommendations.
- Group similar content automatically.
- Enhance user engagement.
- Reduce content discovery time.
- Support marketing and content acquisition strategies.

---

## 📂 Dataset Information

The dataset contains information about Netflix Movies and TV Shows, including:

- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genres
- Description

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

---

## 📊 Project Workflow

### 1. Data Loading

- Import required libraries
- Load Netflix dataset
- Understand dataset structure

### 2. Data Cleaning

- Handle missing values
- Remove duplicate records
- Format columns
- Prepare clean dataset

### 3. Exploratory Data Analysis (EDA)

- Distribution of Movies vs TV Shows
- Country-wise content analysis
- Release year trends
- Ratings analysis
- Genre analysis
- Word Cloud visualization

### 4. Feature Engineering

Created a combined textual feature using:

- Description
- Genres
- Director
- Cast
- Rating

Text preprocessing included:

- Lowercase conversion
- Stopword removal
- Punctuation removal
- Stemming

---

### 5. Text Vectorization

Converted text into numerical vectors using:

- TF-IDF Vectorizer

---

### 6. Dimensionality Reduction

Applied:

- Principal Component Analysis (PCA)

to reduce high-dimensional TF-IDF features while preserving maximum information.

---

### 7. Finding Optimal Number of Clusters

Used:

- Elbow Method
- Silhouette Score

to determine the optimal number of clusters.

---

### 8. Model Building

Implemented:

- K-Means Clustering
- Agglomerative Hierarchical Clustering

Cluster quality was analyzed using:

- Silhouette Score
- Cluster Visualization

---

### 9. Recommendation System

Developed a simple content-based recommendation system using:

- Cosine Similarity

to recommend similar Netflix titles.

---

## 📈 Key Insights

- Movies dominate the Netflix catalog.
- The United States contributes the largest amount of content.
- International Movies and Dramas are among the most popular genres.
- Most content has been released after 2015.
- Textual features effectively capture similarities between titles.
- Clustering enables meaningful grouping without labeled data.

---

## 🚀 Business Applications

This project can be applied in:

- Netflix Recommendation Systems
- Personalized Content Suggestions
- Customer Segmentation
- Content Organization
- Similar Movie Discovery
- Marketing Campaigns
- Viewer Retention
- Streaming Platform Analytics

---

## 📚 Machine Learning Techniques Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Principal Component Analysis (PCA)
- K-Means Clustering
- Hierarchical Clustering
- Cosine Similarity

---

## 📁 Repository Structure

```
Netflix-Movies-TV-Shows-Clustering/
│
├── Netflix_Movies_and_TV_Shows_Clustering.ipynb
├── README.md
├── dataset.csv
└── images/
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Netflix-Movies-TV-Shows-Clustering.git
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📌 Future Improvements

- Deploy as a web application.
- Use advanced sentence embeddings such as BERT or Sentence Transformers.
- Build a complete recommendation engine.
- Integrate real-time Netflix data.
- Experiment with DBSCAN and Spectral Clustering.

---

## 👨‍💻 Author

**Dibyajyoti Roy**

Aspiring Data Scientist | Machine Learning Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!
