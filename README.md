# The English question: Young are less proud to be English

![](https://ichef.bbci.co.uk/news/624/cpsprodpb/15178/production/_101829368_optimised-county_identity_map-nc.png)

In June 2018 the data unit was part of a BBC-wide project based on a major survey of Englishess: **The English Question**. We reported [young people are far less likely to feel proud to be English than older generations](https://www.bbc.co.uk/news/uk-england-44142843), created a briefing pack about the data, which was used in part for Mark Easton's piece [The English question: What is the nation's identity?](https://www.bbc.co.uk/news/uk-44306737), and **Dan Wainwright** created an in-story **chatbot** about devoloved powers in England for the piece [Will England ever get its own Parliament?](https://www.bbc.co.uk/news/uk-politics-44208859#responsive-iframe-cmu-bot-main). 

Dan also took part in around a dozen two-ways (interviews with presenters) as part of BBC radio coverage during the week.

## Get the data

* [YouGov poll results](https://d25d2506sfb94s.cloudfront.net/cumulus_uploads/document/7lnxwjw12j/BBC_EnglishIdentity_March18_Results_for_website.pdf) (PDF)

### Code and cleaning

* [R Markdown files used to prepare the data for analysis, including transposition and subsetting, and cleaning of free text responses regarding rivalries, can be found in the cleaningEnglish folder](https://github.com/BBC-Data-Unit/englishness/tree/master/cleaningEnglish). We are unfortunately unable to share the YouGov spreadsheets which this was used with.

## Interviews and quotes

* Video interviews were conducted with people in different parts of the country, asking 'Do you feel English?' and other questions
* John Denham, director of the Centre for English Identity and Politics, University of Winchester

## Visualisation and interactivity

![](https://raw.githubusercontent.com/BBC-Data-Unit/englishness/master/The%20English%20question%20%20Young%20are%20less%20proud%20to%20be%20English%20%20%20BBC%20News.png)

* Widget: Enter your postcode or council name to see how people feel in your part of England
* Map: Identity strengthens further from London
* Multiple bar chart: views on England's past and future, by vote in EU referendum 
* Multiple bar chart: proud or embarrassed to identify as English, by age group
* Multiple bar chart: qualities that respondents believe make a person English, or do not make a person English
* Bar chart: percentage of respondents identifying characteristics as fairly or very strongly associated with Englishness

For the piece [Will England ever get its own Parliament?](https://www.bbc.co.uk/news/uk-politics-44208859#responsive-iframe-cmu-bot-main):

* In-story **chatbot** about devoloved powers in England.

## About the data

The opinion poll was conducted by YouGov who questioned 20,081 people. The poll has a margin of error of plus or minus 1%.

The council level estimates shown in the search widget are based on the poll and a statistical procedure called [multilevel regression and post-stratification or MRP](https://yougov.co.uk/news/2017/05/31/how-yougov-model-2017-general-election-works/). The technique produces estimates for small areas based on a limited amount of data. It uses the people from each local authority to predict that area's results, but to ensure that this small amount of data is representative of the wider population the estimates are balanced out using comparable data from the poll from the rest of the country and the census on the demographic make-up of the local authority in question. As with all models the figures are subject to uncertainty. The analysis was run by Dr Kevin Cunningham working with Dr Ian Warren of @ElectionData. [More details on MRP are available from YouGov](https://yougov.co.uk/news/2017/05/31/how-yougov-model-2017-general-election-works/).
