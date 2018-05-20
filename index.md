
[About Me](https://vermaph.github.io/)     Skills    Professional Experience     Projects<br />

## Hello - नमस्ते - Hola - 你好!! 

I am Piyush, a data analytics professional. Currently I am finishing my masters in Business Analytics from [Carl H Lindner School of Business](http://business.uc.edu/) at the University  of Cincinnati, Ohio. At UC I have taken courses in Machine Learning, Statistical Modelling, Probability Models, Statistical Methods and Optimization among many others.

Before enrolling in my masters in 2017, I have worked as a Data Analyst for a Sydney based management consulting firm called [Quantium Analytics](https://www.quantium.com/) from 2014 to 2017. I worked on generating competitive intelligence insights for an insurance client and supported a supermarket client in revamping their $500 million loyalty rewards program. This experience had been crucial in launching my career into data science. I have worked in India and Australia and I am currently in USA for my higher studies. 

I have completed my undergraduate and postgraduate degrees in engineering from [Indian Institute of Technology (IIT) - Kharagpur](http://www.iitkgp.ac.in/) in 2014. 


## Skills:

* **Machine Learning:** Regression, Classification, Text-Mining, Recommender System  <br />
* **Algorithms:** Linear Regression, Logistic Regression, K Nearest Neighbour, Discriminant Analysis, Decision Tree, Random Forest, Support Vector Machine, K-Means Clustering, Hierarchical Clsutering, Dimensionality Reduction Algorithms, XGBoost  <br />
* **Programming Languages:** R, Python, SQL, Teradata, C++  <br />
* **Libraries:** ggplt, tidyr, dplyr, caret, glmnet, numpy, scikit, pandas, matplotlib  <br />
* **Softwares:** Git, Jupyter Notebook, Arena for simulation, FICO Xpress, Microsoft Office, Excel, Powerpoint, Word  <br />
* **Operating System:** Windows, Linux  <br />

## Professional Experience:

After graduating from IIT Kharagpur in 2014, I worked in Quantium Analytics between 2014 and 2017. I worked in 2 different teams: *Competitive Intelligence* arm of insurance team and *Loyalty Analytics* arm of retail team.<br /> 

* *Analyst, Retail, Dec 2015 - April 2017*<br />
  *R, Teradata SQL, Excel, VBA*<br /><br />
Worked closely with the General Manager of the Loyalty Rewards Program of one of the Australian supermarket giant. Supported client in  understanding the health of rewards program by building couple of reporting layers centered around:<br />
  - high-level KPIs reflecting the business trend and their comparison with past quarters and years<br />
  - deep-dive analysis on how customers earn reward points through different channels<br />
  - churn of customers between different segments<br />
  - showing the gaps in rewards program and its reach to customers<br />
  - improving the customer value model<br />
  - building a classification model in R to predict the redemption of rewards coupon by a customer in the near future
  - moving to Sydney-Australia as a *Subject Matter Expert* (2016)<br />
  - leading a team of microstrategy software developers and client's Business Intelligence team to deploy the above Quantium Solution in-house<br />
        **Results**:<br />
  - revamp of $500 million loyalty rewards program by the business<br />
  - introduction of a base rewards earn rate of 5% for every customer on every transaction<br />
  - scanning of loyalty cards from active customers increased by ~5%. Which meant more transactions can be linked to customer's shopping behavior. 


* *Analyst, Insurance, July 2014 - Dec 2015*<br />
  *R, SQL, Excel, VBA*<br /><br />
Generated competitive intelligence insights for an insurance client, focusing on comprehensive car insurance. Insights enabled client to understand their online premium quotes' competitiveness among their competitors for different customer segments. I used Lasso regression to identify the factors determining the competitors' premiums. The data used for the analysis was collected by scraping multiple competitors' website for a variety of customer segments. Apart from working on the regular deliverables, I also improved the process by: 
  - Adding a layer of quality check to spot online premium discounts. For this I integrated the SQL tables with the excel. This simple idea tracked the premium for the same quote every week and if any competitor offered a new online discount, it would track it and made sure the analyst didn't miss it in the analysis.  

  
  ## Projects:
  
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
