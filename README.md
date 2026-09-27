# 🎬 Netflix Data Analysis | Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset to understand the content available on Netflix, identify trends, and uncover insights related to content types, ratings, genres, countries, and movie durations.

The project also uses statistical hypothesis testing to investigate relationships between content types and ratings, as well as differences in movie durations across ratings.

## 🎯 Objectives

* Analyze the distribution of Movies and TV Shows.
* Identify trends in content releases and additions over time.
* Explore content ratings and their distribution.
* Analyze movie durations and TV Show seasons.
* Identify the most common countries, genres, directors, and actors.
* Perform statistical hypothesis testing to validate relationships and differences.

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

The dataset contains **8,807 records and 12 original columns**.

Key features include:

* `show_id` – Unique identifier for each title.
* `type` – Movie or TV Show.
* `title` – Name of the content.
* `director` – Director of the title.
* `cast` – Actors and performers.
* `country` – Country of production.
* `date_added` – Date the title was added to Netflix.
* `release_year` – Year of release.
* `rating` – Content rating.
* `duration` – Movie runtime or number of TV Show seasons.
* `listed_in` – Genres or categories.
* `description` – Summary of the title.

## 🛠️ Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **SciPy** – Hypothesis testing

## 🔍 Project Workflow

1. Data loading and inspection
2. Data cleaning and handling missing values
3. Feature engineering and preprocessing
4. Exploratory Data Analysis
5. Data visualization
6. Statistical hypothesis testing
7. Interpretation of results and conclusions

## 📊 Key Analysis & Findings

* **Content Type:** Movies account for approximately 69.6% of titles, while TV Shows account for 30.4%.
* **Content Growth:** Content releases and additions increased substantially after 2015.
* **Ratings:** TV-MA is the most frequent content rating, followed by TV-14.
* **Movie Duration:** Most movies have runtimes of approximately 80–120 minutes.
* **TV Show Seasons:** One-season TV Shows are the most common.
* **Countries:** The United States has the highest number of titles in the dataset.
* **Genres:** International Movies, Dramas, and Comedies are among the most frequent categories.

## 🧪 Hypothesis Testing

### 1. Chi-Square Test of Independence

**Objective:** To examine whether content type (Movie or TV Show) is associated with content rating.

* Chi-square statistic: 1046.18
* p-value: 2.10 × 10⁻²¹⁵
* Significance level: 0.05

**Conclusion:** The null hypothesis was rejected. A statistically significant association was observed between content type and rating.

### 2. Kruskal-Wallis Test

**Objective:** To examine whether movie duration distributions differ across content ratings.

* Test statistic: 965.85
* p-value: 3.77 × 10⁻¹⁹⁸
* Significance level: 0.05

**Conclusion:** The null hypothesis was rejected. Movie duration distributions differ significantly across ratings.

### 3. Pairwise Mann-Whitney U Tests

Pairwise comparisons were performed between ratings, with Holm correction applied to adjust for multiple testing.

* Total comparisons: 91
* Statistically significant comparisons: 43
* Non-significant comparisons: 48

## 📈 Visualizations

The project includes visualizations such as:

* Movies vs. TV Shows distribution
* Content releases by year
* Rating distribution
* Ratings by content type
* Movie duration distribution
* TV Show seasons distribution
* Top countries by title count
* Top genres
* Top directors and actors
* Content additions by year
* Movies vs. TV Shows added over time
* Movie duration comparisons across ratings

## 💡 Conclusion

This analysis provides insights into Netflix's content catalog, including the distribution of Movies and TV Shows, popular ratings and genres, country-wise contributions, and content trends over time.

Statistical testing identified an association between content type and rating, along with differences in movie duration distributions across ratings.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Upload the Netflix dataset.
4. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## 👩‍💻 Author

**Sanskruti Pawar**

 Aspiring Data Analyst
