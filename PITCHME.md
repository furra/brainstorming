@title[Introduction]
<h2>Movie Analytics</h2>

<img src="images/film-reel.jpeg" alt="" style="
    height: 300px;
">

Felipe Urra - M.Sc. Computer Science
University of Western Ontario

---
@title[The problem]
<h3>The Problem</h3>

The global film industry is huge. 

Some statistics:

* USA is the third largest market in the world (behind China and India)
* About 5800 cinemas in the US as of 2016 
* Global box office is forecast to generate 50 billion dollars in 2020

Source:
https://www.statista.com/topics/964/film/

---
@title[The problem]
To predict revenue could be very substantial for movie studios.

Decisions:

* Budget
* Marketing
* Crew

---
@title[The data]
<h3>The data</h3>
![](images/kaggle_dataset.png)
-TMDB

---
@title[The data]
![](images/movies_metadata.png) 

---
@title[The data]
![](images/credits_data.png) 

---
@title[The data problem?]
<h3>Data problems</h3>
Missing values:

* revenue: ~7k of 45k
* budget: 2k of 7k

---
@title[Scraping]
![](images/box_office_mojo.png) 

---
@title[Join data and Encoding]

* One hot encoding
* Memory issues

Too many features:

* cast: 6524
* directors: 4752
* languages: 42
* collection: 655
* writers: 5133
* genres: 20
* producers: 3858
* spoken languages: 94

---
@title[Basic analysis]
![](images/popularity_revenue.png) 
---
@title[Basic analysis]
![](images/runtime_revenue.png)
---
@title[Basic analysis]
![](images/budget_revenue.png)
---
@title[Basic analysis]
![](images/coefficients.png) 
---
@title[Model analysis]
![](images/coefficients.png) 

Mean Square Error = 8110663175083914.0
---
@title[Model analysis]
![](images/coefficients_genres.png)

Mean Square Error = 7620100426286874.0
---
@title[Model analysis]
![](images/coefficients_genres_collections.png) 

Mean Square Error = 4685249279116433.0
---
@title[Upcoming tasks]
<h3>Upcoming tasks</h3>

* Define set of features
* Use test and validation data
* Use Linear Regression
---
@title[Pending tasks]
<h3>Pending tasks</h3>

*Memory issues