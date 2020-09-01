# Global Happiness, an Analytical Analysis
## Captain Data Crunch LLC.
Craig Nowakowski, Raymond Garskovas, Allyson Chau and Varun Kaushik
![Captain](https://i2.wp.com/boingboing.net/wp-content/uploads/2015/07/captaincrunch.jpg?w=1600&ssl=1)

### Project Proposal
For our project proposal we will be analyzing country income level and their respective happiness. We plan on building a database which has country economic data as well as how the country has scored in the UN’s global happiness survey. Our data sources will include: the world happiness index and global economic data.

### Background
The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012 and has continued annually since then. Today, the report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.

Happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The scores are from nationally representative samples for the years 2013-2016 and use the Gallup weights to make the estimates representative. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others.

![Happiness](https://www.tusharvakil.com/wp-content/uploads/2019/09/Finding-Happiness.jpg)

### Project Report:

# Extracting Data: The following data sources were used to generate "Happiness Data":   

* https://www.kaggle.com/unsdsn/world-happiness
* https://www.kaggle.com/worldbank/world-development-indicators
* https://www.prosperity.com/about/resources

The Kaggle data sources contained data in CSV format, while Prosperity contained data in XLSX format. These datasets were chosen because they not only contained sufficient data as related to happiness (economic, health/safety, business environment, infrastructure etc.) for >150 countries, but also presented the data relatively cleanly. This was critical as the duration of the project was < 1 week; therefore, the team needed credible data that can be relatively quickly transformed for further analysis.    

# Transforming Data: The following shows how the data was cleaned up/

First off, the Prosperity dataset (Excel File) was saved as a CSV, and then all the datasets were read into Jupyter Notebook. 
Secondly, as all the tables had several columns, the team created an 

* The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc).
* The type of final production database to load the data into (relational or non-relational).
* The final tables or collections that will be used in the production database.

# Loading Data: The following summarizes the finished table and its rationale
 
At the end of the week, your team will submit a Final Report that describes the following:
1. 	Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).
2. 	Transform: what data cleaning or transformation was required.
3. 	Load: the final database, tables/collections, and why this was chosen.
