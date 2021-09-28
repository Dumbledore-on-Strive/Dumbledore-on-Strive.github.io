### AI Engineering | Build Week 1

# Goodreads Webscraping

Enjoy the journey and you'll see the magic :sparkles:

![](https://miro.medium.com/max/1024/1*N1k6cmyD9h99w4S-CEaKXw.png)

```python
def __init__:
   print('Hello Boss')
```

<p>&nbsp;</p>

## Check it out live

- [Click here](https://share.streamlit.io/dumbledore-on-strive/goodreads-app)

<p>&nbsp;</p>

## How to Run

1. Clone the repository:

```
$ git clone https://github.com/Dumbledore-on-Strive/goodreads-app.git
$ cd goodreads-app
```

2. Install dependencies:

```
$ pip install -r requirements.txt
```

3. Start the application:

```
streamlit run streamlit_app.py
```

If you need extra help with Streamlit, got to the [documentation](https://docs.streamlit.io)

<p>&nbsp;</p>

## The Team

- [Agathyia Raja](https://github.com/AgathiyaRaja)
- [Camelia Ignat](https://github.com/avocami)
- [Fabio Fistarol](https://github.com/fistadev)
- [Nurlan Sarkhanov](https://github.com/nsarkhanov)

<p>&nbsp;</p>

## The Task

Create your own database with the scraped information from [goodreads.com](https://www.goodreads.com/), to process and analyse them, also with a bit of Data Visualization and finally make the result public!

<p>&nbsp;</p>

During the first build week on Strive School, our task is to work as a team and to have the opportunity to put together what you have learned so far and build something for real.

All instructions were posted on [Notion.](https://www.notion.so/Data-Visualization-e226cc8314324939a56ac84a1f457cbd)

Check out our presentation on [Google Drive!](https://docs.google.com/presentation/d/1iQ-gyhHxwDRoJAeOyrHYcgPsisamqPO92RU8n9Fr9Dc/edit#slide=id.gd265604c1e_1_2)

<p>&nbsp;</p>

- [Web Scraping & Analysis](https://www.notion.so/Web-Scraping-Analysis-6c2e9f1388064c8ab9e42fdf80a237db)

Data scraped:

    * url - str
    * title - str
    * author - str
    * num_reviews - int
    * num_ratings - int
    * avg_rating - float
    * num_pages - int
    * original_publish_year - int
    * series - bool
    * genres - str
    * awards - str
    * places str

<p>&nbsp;</p>

- [Data Visualization](https://www.notion.so/Data-Visualization-e226cc8314324939a56ac84a1f457cbd)

Data visualisation:

    * scatterplot showing the correlation between the number of pages and the number of ratings
    * average rating distribution
    * ratings wrt the years
    * minmax normalized rating distribution
    * mean normalized rating distribution
    * both the minmax normalized rating distribution and mean normalized rating distribution together
    * awards distribution
    * minmax normalized rating distribution in function of the number of awards won by the book

Data to be calculated:

    * correlation coefficient of the num_pages and num_ratings columns
    * best fit for distribution graphs(normal, chi-squared etc) using Scipy-Stats
    * the probability that a book that is part of a series has won an award using the Bayes Theorem

<p>&nbsp;</p>

- [Code optimization ](https://www.notion.so/Optimize-your-code-3817259c56f3467696cdf28af734275c)

Optimization:

    * For this task the team spent time editing the code to make it more efficient, fast and pythonic, as well as transforming the Dataframes and Visualisations into a website using Streamlit.

<p>&nbsp;</p>

- [Publish](https://www.notion.so/Publish-98a388d301ff490fa0fcda40deef3a3b)

Services:

    * Front end: Streamlit
    * Version Control: GitHub
    * Server: Heroku
    * Devops: Heroku

<p>&nbsp;</p>

- [Presentation](https://www.notion.so/Present-641432ba3db74b47b063d8b7b0a93e03)

<p>&nbsp;</p>

### You can see this page live

[Go here](https://dumbledore-on-strive.github.io/)
