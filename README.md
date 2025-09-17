# 📺 Netflix-Data-Analysis 
The goal of this project is to analyse netflix's movie and TV show catlog to uncover insights about release trend and IMDb rating patterns. 

This analysis helps understand how netflix content strategy evolved over time and what types of tittles are most successful. 

# 📂 Dataset 
- Source: [https://www.kaggle.com/datasets/thedevastator/netflix-imdb-scores]
- Key columns and description :
  - title: The name of the TV show or movie.
          This column contains the titles of various TV shows and movies available on Netflix. You can use this information to identify specific titles within the dataset.

  - type: Indicates whether the entry is a TV show or a movie.
          The type column categorizes each entry as either a TV show or a movie. You can filter your analysis based on these categories to focus on either TV shows or movies specifically.

  - description: A brief description of the TV show or movie.
    The description column provides a summary of each TV show or movie's plot or storyline. This information can help you get an overview of what each title is about before diving into further analysis.

  - release_year: The year in which the TV show or movie was released.
    This column indicates the release year for each title in numeric format. You can utilize this data point to examine trends over time by grouping and aggregating titles based on their release years.

  - age_certification: The age certification rating for the TV show or movie.
                      The age_certification column specifies age ratings assigned to each title, indicating whether they are suitable for general audiences (e.g., all ages) or restricted due to mature content                           (e.g., rated R). Analyzing this attribute allows you to understand what type of content Netflix offers at different age levels.

  - runtime: The length of episodes for TV shows OR duration for movies.
            The runtime column provides the length of episodes for TV shows or the duration of movies in numeric format. This information can help you identify shorter or longer titles based on their runtime and              compare them within your analysis.

  - imdb_score: The score of the TV show or movie on IMDB.
                This column displays the IMDB score assigned to each title, representing its overall quality and popularity on IMDB. Utilize this metric to evaluate and rank different titles based on their                        ratings, potentially uncovering interesting patterns or insights.

  - imdb_votes: The number of votes received by the TV show

# 📊 Key Analysis 
- Number of titles release per year
- Avg IMDb score by type
- Top 10 titles by IMDb votes helped to identify the popularity. 
- Current year release Vs previous year release
- Did current year release met the target releases.

# 📷 dashboard image 

Overview 

<img width="1329" height="754" alt="image" src="https://github.com/user-attachments/assets/28c3011b-3037-4858-bc51-e66818506a70" />

IMDb Analysis 

<img width="1349" height="750" alt="image" src="https://github.com/user-attachments/assets/a8d5f0a0-d8b8-4a4c-85d8-f45d65084ada" />

Release Trend 

<img width="1351" height="746" alt="image" src="https://github.com/user-attachments/assets/9146716c-89a8-4c09-9baa-884e0ac18011" />



