<br />


### [About Me](./index.html)&nbsp; &nbsp; &nbsp;[Skills](./skills.html)&nbsp; &nbsp; &nbsp;[Professional Experience](./experience.html)&nbsp; &nbsp; &nbsp;[Projects](./projects.html)<br />


**[Customer Segmentation for a retail supermarket](https://github.com/vermaph/Codes/tree/master/Pet%20Projects/Supermarket%20dashboard)**<br />
  *Recency Frequency Monetary model*, *k-medoids*<br />
  Used Partition Around Medoids realisation of [k-medoids](https://en.wikipedia.org/wiki/K-medoids) to perform clustering of the customers (households) of a US based supermarket. The data had 3 parts: transaction data (at the product level), demographic data (of the customers) and product details data. For this project, following were the steps taken:<br />

    - Cleaning of bad data using SQL
    - [Tableau visualization](https://public.tableau.com/profile/piyush.verma#!/vizhome/AnalysisofaSupermarketChain/Final) for having a high level understanding on the sources of revenues by customer type, departments and product categories
    - Creating a clean view in SQL with new KPIs for Basket Value (=Total Yearly Sales/Total Yearly Visits), Recency, Frequency, and Monetary for each household
    - Clustering in R by calcualting the dissimialrities using the gower distance

  I extended the analysis to fit a machine learning model in an effort to predict the yearly spend of a household using the recency, frequency, monetary, basket value and household-demographics as predictors but the data/features seemed to be insufficient for a good fit.

  **[Predicting text using N-Grams](https://vermaph.shinyapps.io/Nextword/)**<br />
  *N-Grams, Text Mining, R Shiny, R*<br />
  Built an interactive R Shiny web application where a user can enter a string of text and the application would predict the next word. The algorithm used here is Katz Back-Off which uses the conditional probability of a N-Gram. This was done as a capstone project for a 10 course [Data Science Specialization certificate](https://www.coursera.org/account/accomplishments/specialization/6UFAFQ6NL8TA) from John Hopkins University in Coursera.
  
  **[Classification of dysfunctional stores]()**<br />
  *K-means clustering, Hypothesis Testing, HR Analytics*<br />
  Worked on a case study project with a local retail client in Cincinnati. The aim of the project was to identify potential stores which may go dysfuntional becaue of employee activities in the near future. The data used for the analysis was at the store level having attributes related to employees. The recommendations give nto the client were well received and were in-line with the expectations. 
