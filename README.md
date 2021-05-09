# INFO 201 Course Project

This repo will contain the code and data for a course project
for the _Technical Foundations of Informatics_ course at the UW iSchool.

---

# World Health & Happiness

Authors: Drake Watson <br>

---

## Problem Domain

The problem domain for this project will be the health and happiness of countries. Using data about a countries demographics, health statistics, and happiness rating, we would like to evaluate what qualities and characteristics of a country indicate that it is a happy and healthy one, or an unhappy and unhealthy one. There is an abundance of data being collected about the countries of the world that many people are attempting to use to quantify the success and health of a country, and we are hoping to merge some of that data together to get some insight on how that data relates to each other. To better compare countries, data is calculated into indices on a 1-100 scale (climate index, crime index, etc.) so that there is a quantifiable way to evaluate countries against one another. Obviously this method is just a rough estimation, and the domain we are working with will be a rough estimation itself as the issue of happiness and health is a very vague and nuanced one, but we still hope to use these data sets to gain some valuable insight into the well-being of the world. <br>

We are hoping to uncover nuanced trends or relations that might give us a better idea about what makes a country happy and healthy. <br>

_Existing Projects/Analysis_ <br>

- [Happiness and Life Satisfaction: Exploratory Data Analysis on World Happiness Report](https://towardsdatascience.com/happiness-and-life-satisfaction-ecdc7d0ab9a5#:~:text=Exploratory%20Data%20Analysis%20on%20World%20Happiness%20Report.&text=Is%20it%20to%20achieve%20happiness%20in%20some%20way%3F&text=The%202020%20report%20ranked%20156,on%20a%20Cantril%20ladder%20survey.)

- [Cities and Happiness: A Global Ranking and Analysis](https://worldhappiness.report/ed/2020/cities-and-happiness-a-global-ranking-and-analysis/)

---

## Analysis Questions

- How has the entire worlds average happiness score trended as other big world events have occurred such as the Obama presidency, Trump presidency, BLM protests, Brexit, etc.? It would be interesting to show the trend line of the average world happiness score over the 2010's with the big world events sort of bookmarked on the bottom of the graph.

- Compare health vs happiness for first world or “advanced” countries and third world countries. First world sees itself as "better" but on average do we actually have better health outcomes or happier citizens? We could evaluate this question if we were able to filter the countries by first/third world categorization, and evaluate their average happiness ratings.

- How does the trend of a certain health statistic relate to the trend of a country's happiness score? Is this different for different countries? Compare trend lines of health statistics such as domestic abuse with the trend line of happiness.

- Do certain health stats indicate a happier country more than others? This could give insight into cultural values/priorities, and we could explore this by evaluating an average health stat of all countries in a given year vs the average happiness of those countries in a given year, and then see how that relation varies for different health stats.

- How does general demographic information about a country relate to it's happiness score? Do certain demographic subgroups have a higher happiness on average? It would be interesting to see if smaller countries or larger countries have starkly different happiness ratings, or if there's no relationship at all.

- What is the average health care quality for a country in each continent and how do they compare with each other? This is important to know in order to identify which factors really affect the highest levels of healthcare. By looking at the best countries and continents with healthcare, others can model their healthcare around a similar model. We would be able to compare continents' average health care quality with the health care index from the countries 2020 data set.

- What happiness indicators have more of an effect on overall happiness? This should be done to ensure that the data we use to solve our other questions is relevant to figuring out the correlation between health and happiness. To solve this question, we can cross-reference the various happiness indicators with the overall happiness report to figure out patterns within the datasets.

---

## Data Sets

- [World Health Statistics 2020|Complete|Geo-Analysis](https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=eliminateViolenceAgainstWomen.csv)

  - The _World Health Statistics 2020_ data set provides us with various health statistics (maternal mortality, communicable diseases, substance abuses, traffic injuries, etc.) from most of the countries (those that are recognized by the World Health Organization) across the world from 2011-2020. The data set is split up into 39 different csv files that detail different health statistics and include columns that go into more detail about each individual stat. The data provided does not only cover basic topics such as life expectancy and disease mortality rates, but also more nuanced issues such as alcohol abuse and domestic violence rates that has been provided by the World Health Organization. We would like to use this dataset to compare with demographic information and happiness rating's of countries to try and uncover any sort of relationship or trends that might be surprising or unexpected. <br>


- [World Happiness Report](https://www.kaggle.com/unsdsn/world-happiness)

  - The _World Happiness Report_ data set provides us with "happiness ratings" of countries from 2015-2019. The happiness metric is based upon data from the Gallup World Poll and has been presented by the United Nations since 2012. The scores provided are based on answers to the main life evaluation question asked in the Gallup World Poll. This question, known as the _Cantril ladder_, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The data set also contains columns following the happiness score that estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others. This dataset can be used to try and evaluate what it is that makes a country happy and it will allow us to search for commonalities between happier countries (or less happy countries). We would like to cross reference this table with more specific health data to see if there is any sort of relationship between more nuanced issues of a country and its overall well-being. <br>


- [Countries Dataset 2020](https://www.kaggle.com/dumbgeek/countries-dataset-2020?select=Quality+of+life+index+by+countries+2020.csv)

  - The _Countries Dataset 2020_ file gives some general demographic information about the countries around the world. This sort of information (population, cost of living, etc.) can be used to cross reference against happiness and health to try and uncover any characteristics or sub-groups of countries that might indicate how healthy and happy that country is. Most of the data in this file is collected from 2015-2019, so we will have to take into account which year the data is referring to when we are comparing it against data from other csv files. <br>


- [Human Happiness Indicators: Quantifying What Factors Influences a Person's Happiness](https://www.kaggle.com/loveall/human-happiness-indicators)

  -  The _Human Happiness Indicators_ dataset provides us with different indicators that contribute to happiness (such as marriage status, education, and age) and attempts to quantify and classify human happiness. Data are taken of the average person from various different regions of the world, across multiple decades and compiled into respective happiness scores and classifications. We downloaded this dataset from Kaggle which came from a public repository on Github. This dataset can help us answer questions about which factors contribute to happiness and if different regions have indicators that are more important to happiness in those regions than in others. There are some issues with column descriptions and source information, and those things should be taken into consideration when working with this data set.
