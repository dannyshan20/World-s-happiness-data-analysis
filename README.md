# World-s-happiness-data-analysis
This project is about analyzing the word's happiness data for the years from 2015 to 2021 using python. The dataset comprises of different features basead on which the happiness is calcuated. Here is an example of 10 happiest countries in year 2021. THe dataset was taken from the survey by Gallup World Survey.

![GitHub Logo](/Figures/Happy_2021.png)


Below I will explain the analysis in following way
* Data Anlaysis
* Results and Visualizations
* Technogology Used
* How to Run


## 1. Data Analysis

The data set was taken from kaggle (https://www.kaggle.com/mathurinache/world-happiness-report?select=2020.csv) which was orginally taken from Gallup World Survey. There were mutliple parameters on which the happiness score is calculated. Here is the list of attributes/paramters used to calculate happiness score.

 - Data Columns Description
    - Ladder Score : Ladder score is the score on the happiness ladder for each of the country.
    - GDP per capita: This attributes represents, as names suggests, the GDP per capita in each country which will be used to calcuate the happiness ladder score
    - Healthy Life Expectancy: This attributes represents the life expectancy,on average, for each country which participated in the survey. This attribute is highly important to the happiness score
    - Social support: This attributes represents the social support provided by the respective governments to the people of their country
    - Freedom to make life choices: This attributes provides the ratio of people in a country to make life choice. The values varies between 0.0 to 1.0
    - Generosity: The generoisty represents the the ability to donate amongs the people of a country. The
    - Corruption Perception: The corruption in a country also plays important role in calculating the socre of happiness for a country. The more the corruption, the less happy the country

There are few data files

- Data Files explaination
    - 2015.csv: This file has the data for the year 2015 collected by Gallup World Survey in csv format
    - 2016.csv : Happiness Data for year 2016 in csv format
    - 2017.csv : Happiness Data for year 2017 in csv format
    - 2018.csv : Happiness Data for year 2018 in csv format
    - world-happiness-report-2021.csv : World's Happiness Data report for the year 2021



For the **pre-processing** part, we selected few columns to display in the plot along with happiness score. The dataset for each year had to be sorted based on the "lader score" attribute so we can display top countries based on the ladder score. 

## 2. Results and Visualizations

There were few analysis performed to visually see the list of the most happy and unhappy countries in year 2021 along with comparison of other countries' averages over the past 5 years.

Here is the visualization for the top 10 unhappy countries for the year 2021.

![GitHub Logo](/Figures/UnHappy_2021.png)

You can see other information like Logged GDP Per Capita and Healthy Life Expectancy along with the Ladder score.

Below is the comparison of The top 10 happiest countreis in copmarison with the averages of happiness score over past 5 years. 

![GitHub Logo](/Figures/Comparison_Happy_2021.png)

## 3. Technology Used


- [Jupyter Notebook](https://jupyter.org/)
- [Anaconda](https://www.anaconda.com/)
- Python 3.x


## 4. How to run

1. To reproduce the results and to run the code, you would need to install anaconda for python 3.x (https://docs.anaconda.com/anaconda/install/) if you haven't already.
2. After installing anaconda, you can open jupyter notebook and open the notebook form the location you have saved the project. 
3. You may need to install librarys attached in requirements.txt file using the command pip install -r requirements.txt.
This project has been tested and working on windows and linux

## Authors

[Danny Shan](https://github.com/dannyshan20) - Learning Analytics MS student at Teachers College, Columbia University

