### **Recommendation System Using K means Clustering Approach :**

💦 **Introduction:**
            
           On providing the name of the movie, this system recommends the similar movies
           which fall on the same genre i.e. (Primary genre, Secondary genre, Tertiary genre).

💦 **Packages:**

           💧	pandas
           💧	numpy
           💧	bs4
           💧	** For other packages... Please refer requirements.txt 😅😅**

### **Steps to run this code:**

💦 **Dataset: Scraping of data:**

            Web scraping was done in the IMDB website to scrape the movies and there 
            respective genre which will later be used for building a movie 
            recommendation system using clustering approach.

> 1. Run scrapper.py to scrape the movies, which will be stored in the Dataset.csv file in form of:

<p align="center">
  <img src="https://raw.githubusercontent.com/rravii/Movie_Recommendation_System_Using_Clustering/master/Screenshots/scraper.JPG" />
</p>

    ❄️ Pre_processing:

            💧 Run pre_processing.py file to check out how each genre is assigned numeric value.
            💧 Similar genre are assigned similar value so that it can be processed easily.

<p align="center">
  <img src="https://raw.githubusercontent.com/rravii/Movie_Recommendation_System_Using_Clustering/master/Screenshots/pre_processing.JPG" />
</p>

    ❄️ Clustering_code:

            💧 Run clustering_code, to check out how similar P_Genre, S_Genre, T_Genre is 
            assigned with same Cluster_Id:

<p align="center">
  <img src="https://raw.githubusercontent.com/rravii/Movie_Recommendation_System_Using_Clustering/master/Screenshots/clusterID.JPG" />
</p>

💦 **Main_code:**

> 2. Run main.py where clustering_code.py and pre_processing.py will be triggered.

> On providing movie name free guy, the system recommends the movies with same cluster_ID.

<p align="center">
  <img src="https://raw.githubusercontent.com/rravii/Movie_Recommendation_System_Using_Clustering/master/Screenshots/recommend.JPG" />
</p>
