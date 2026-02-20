# R Data Mining - Projects & Analysis 📊

A comprehensive data engineering and statistical analysis project focused on **Bayesian classification**, **Discriminant Factor Analysis (AFD)**, and **Natural Language Processing (NLP)** using R.

## 🎯 Learning Objectives

This project explores and demonstrates several key data science competencies:
- **Statistical Modeling**: Implementing and comparing Bayesian classifiers and Discriminant Factor Analysis (AFD/LDA).
- **Natural Language Processing**: Transforming raw text into actionable data using **Word Embeddings (Word2Vec)** and **TF-IDF**.
- **Data Quality & Engineering**: Handling complex datasets with challenges like data leakage, paraphrased observations, and noise.
- **Reporting & Visualization**: Building professional, interactive reports using **R Markdown**, custom CSS, and `ggplot2`.

## ✨ Features

- **Advanced NLP Pipeline**:
  - Text preprocessing: Tokenization, cleaning (URLs, mentions, hashtags), and bigram detection.
  - Feature Engineering: Transition from sparse representations (TF-IDF) to dense vector representations (Word2Vec).
- **Machine Learning & Analysis**:
  - **Sentiment Analysis**: Multi-class classification of Twitter data with a focus on avoiding data leakage.
  - **Hierarchical Classification**: Routing predictions through multiple model levels to improve accuracy on complex label sets.
  - **Comparative Studies**: Analyzing the impact of different vectorization techniques and model architectures.

## 🛠️ Tech Stack

- **Language**: R 4.x
- **Libraries**:
  - `tidyverse`: Data manipulation and visualization.
  - `tm`: Text mining infrastructure.
  - `word2vec`: Training and applying word embeddings.
  - `MASS`: Linear Discriminant Analysis (LDA/AFD).
  - `ggplot2`: Statistical graphics.
- **Reporting**: R Markdown (HTML outputs with `flatly` theme).

## 🚀 Getting Started

### Prerequisites

- R and RStudio installed.
- Required R packages: `install.packages(c("tidyverse", "tm", "word2vec", "MASS", "ggplot2", "knitr"))`

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/wilfried-lafaye/r-data-mining.git
   cd r-data-mining
   ```

2. **Open the Project**
   Open `r-data-mining.Rproj` in RStudio.

3. **Explore the Analysis**
   Navigate to the `projects/` directory and open any `.Rmd` file. Use the **Knit** button in RStudio to generate the HTML reports.

## 📂 Projects Overview

- **Projet 1: Bayesian Classification**: detecting emotions in short texts using Bayesian principles.
- **Projet 2: Twitter Sentiment Analysis**: Advanced study using Word2Vec and AFD to classify sentiments while managing data quality issues.
- **Projet 3: Analyse des Thèses de Doctorat**: Categorizing doctoral theses by comparing Sparse (TF-IDF) and Word Embeddings approaches.
- **Projet Final: Détection de Texte IA**: Distinguishing human-written from AI-generated text for a Kaggle challenge.

## 📄 Authors & License

- **Authors**: Marie Bouetel & Wilfried LAFAYE (ESIEE Paris)
- **Year**: 2025 - 2026
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
