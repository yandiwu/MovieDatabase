# Movie Database 
An analysis of IMDb Top 400 movies. A Tableau dashboard with summary of the results can be found [here]<https://public.tableau.com/app/profile/yandi.wu/viz/factsheet_16746166550030/Dashboard1?publish=yes>, and the raw file is also available. 

## Dataset 

For the database, created on Azure Data Studio using Microsoft SQL 2019 server, I used the [following kaggle dataset](https://www.kaggle.com/datasets/omarhanyy/imdb-top-1000), which I downloaded as a CSV and then converted into a database: 

I chose this dataset because it had the crucial information I was looking for: title, year, IMDb rating, cast (directors and actors), duration, and metascore, to name a few. I ended up adding two pieces of information I was interested in analyzing: country of origin and language of the initial release. Attaining this bit of information required extensive Wikipedia searching and a certain degree of decision making, which is detailed in the movies.ipynb Python notebook file. 

Unfortunately, although the source claims to have IMDb top 1000 movies, when I opened the source, I noticed that only 398 movies were listed, possibly due to some accidents in updating the CSV file. Hence the tile "Top 400" movies on IMDb. As a result, I needed to clean the data and preprocess it before making my queries by modifying the database. The [final CSV file](https://github.com/yandiwu/moviedatabase/blob/main/IMDBtop400.csv) that I obtained after adding two columns is available in the repository.





