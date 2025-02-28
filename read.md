I'll include the dataset column details in the README. Here's the updated version:  

---

# Netflix Data Analysis  

## 📌 Overview  
This project is an **Exploratory Data Analysis (EDA)** of Netflix data. The goal is to analyze and visualize trends in Netflix content, including genres, ratings, release years, and other key insights.  

📌 **Live Demo**: [Click Here](https://datageniesk.github.io/Netflix-Data-Analysis-/)  
📌 **GitHub Repository**: [Click Here](https://github.com/DatagenieSK/Netflix-Data-Analysis-)  

## 📊 Features  
✔️ Data Cleaning and Preprocessing  
✔️ Visual Analysis of Netflix Content  
✔️ Insights on Genre Distribution, Release Trends, Ratings, and More  
✔️ Interactive Visualizations  

## 📂 Dataset Details  
The dataset consists of **9 columns** and **9,827 rows**:  

| Column Name         | Description                                      | Data Type  |
|---------------------|--------------------------------------------------|------------|
| **Release_Date**    | Release date of the movie/show                  | `object` (to be converted to datetime) |
| **Title**          | Name of the content                              | `object` |
| **Overview**       | Short description of the movie/show              | `object` |
| **Popularity**     | Popularity score of the content                  | `float64` |
| **Vote_Count**     | Number of votes received                         | `int64` |
| **Vote_Average**   | Average rating based on votes                    | `float64` |
| **Original_Language** | Language in which the content was originally produced | `object` |
| **Genre**          | Genre(s) of the content                          | `object` |
| **Poster_Url**     | URL of the content's poster                      | `object` |

## 🛠️ Tech Stack  
- **Python**  
  - Pandas & Numpy
  - Matplotlib & Seaborn (Data Visualization)  
- **Jupyter Notebook** for analysis  

## 📈 Key Findings  
📍 **Most Frequent Genre:** *Drama* is the most frequent genre, appearing in **more than 14%** of all movies.  
📍 **Genre with Highest Votes:** *Drama* again leads, accounting for **18.5%** of movies with the highest popularity.  
📍 **Most Popular Movie:** *Spider-Man: No Way Home* has the highest popularity rating and belongs to the *Action, Adventure, and Science Fiction* genres.  
📍 **Least Popular Movie:** *The United States vs. Billie Holiday* and *Threads* have the lowest popularity, belonging to *Music, Drama, War, Sci-Fi, and History* genres.  
📍 **Year with Most Releases:** The year **2020** recorded the highest number of movie releases.  

## 🚀 How to Run the Project  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/DatagenieSK/Netflix-Data-Analysis-.git
```  
2️⃣ Install dependencies:  
```bash
pip install pandas matplotlib seaborn
```  
3️⃣ Run the Jupyter Notebook to explore the analysis  

## 🎯 Future Improvements   
🔹 More interactive visualizations using Power BI/Tableau  

---
