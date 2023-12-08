# World-Happiness-Reports-Analysis
Data analysis on Gallup's Poll Survey data on the World Happiness from 2015-2019

## About Dataset
The World Happiness Report is a globally acknowledged survey conducted annually by Gallup World Poll, which asks the survey-takers to assign a value to their happiness felt and to rank them accordingly. Deploying a Cantril ladder, the survey-takers imagine a ladder, with the top of the ladder being 10 and therefore the best possible life for them and the bottom being 0 and therefore the worst possible life for them. Aside from happiness, six life factors are also included in the report: GDP per capita, social support, healthy life expectancy, freedom, generosity, and corruption. Although they do not determine the happiness ranks, they are included in the report to show to which extent the factors contribute to the happiness score.

## Data Collection
The number of people and countries surveyed varies year to year, but by and large more than 100,000 people in 130 countries participate in the Gallup World Poll each year. They are based entirely on the survey scores, using the Gallup weights to make the estimates representative. 
The typical annual sample for each country is 1,000 people. If a typical country had surveys each year, the sample size would be 3,000. The rankings are from nationally representative samples of the past 3 years. Meaning if the report is from 2019, the averages of the 2016 to 2018 surveys were published to provide.
I have used the reports from 2015 to 2019.

## Source
- <a href="https://www.kaggle.com/datasets/unsdsn/world-happiness/">Kaggle</a>; opensource data provided by Gallup World Poll

## Data limitation
Surveys are bound to produce subjective values, as unsatisfied individuals are more likely to raise their voices and concerns than satisfied people are. 
Not every country is surveyed every year, hence analysis of those countries will be less accurate and less comparable over time.
The dataset does not include something like “Security/Safety”, evaluating how safe the countries are regarding crime rates, wars, civil uproars… But then again those are more likely to be dynamic factors than the six life factors. It also does not include a section for work/life-balance or stress levels.

## Data Ethics
The data is kept anonymous, privacy of respondents is ensured. There is a possibility of collection bias as, it is unknown how these surveys were effectively conducted; in person/online/per mail.

## Tools
Jupyter Notebook/Python3 libraries:
- numpy
- pandas
- json
- sklearn
- statsmodels


  libraries for visualizations:
- seaborn
- matplotlib
- folium

  ## Deliverable
  <a href="https://public.tableau.com/views/WorldHappinessReportsAnalysis2015-2019/Story1?:language=de-DE&publish=yes&:display_count=n&:origin=viz_share_link">Dashboard</a> on Tableau with results related to answering the hypothesis only, for more details please view the scripts.
