# CornellMachineLearning
Final Project for Cornell Machine Learning (BANA 6270)

Machine Learning Final Project
 Team 6
 
 I. Problem Statement

 Threads has always been outcompeted by Twitter. Since Twitter has become X and
 there has been a decrease in usage, we believe that there is an opportunity in the market for
 Threads to better compete with X. We need to look for areas of the app that are the most
 mentioned in a negative way. These areas should be the main areas of focus for future
 improvements because they provide the most room for improvement, and affect the largest
 number of users.

 
 II. Solution Development
 
 Wemplan to develop a neural sequence model for sentiment analysis. This model will use
 sentiment analysis to categorize the Threads reviews into positive/negative and by popular
 categories. Once the model is developed, we then plan to test the model. We will take a random
 sample of the data and classify the reviews by hand. We will then compare the human
 determined outputs to the model determined outputs for the random sample. We will use what
 we have learned to identify a model accuracy score and enhance the model if necessary.
 Once we are satisfied with the model, we will use it to feed into our App Attribute Review
 Breakdown (Dashboard). We will create a Power BI dashboard that displays standard metrics
 that summarize the data, as well as deep dive sections into the sentiment analysis we have
 conducted.
 The main dataset we plan to use is Threads, An Instagram App Reviews. This dataset
 only has four columns: source of download (App Store or Google Play), review description
 (entered by the user), review rating (1-5 entered by the user), and date the review was entered.
 Webelieve that this dataset will be sufficient to conduct our analysis. We may consider bringing
 in additional datasets down the line if necessary, such as additional Threads App reviews or
 even Twitter/X app reviews.

 
 III. Ways of Working
 
 Wehave assigned a point person to the tasks that we will need to complete. However,
 we plan to work on all of the tasks as a group and have regular check-ins to discuss progress,
 next steps, and make adjustments to workload as needed. Patrick and Estelle will be on point
 for developing the Model. This includes developing a Python Neural Sequence Model for
 Sentiment Analysis, debugging, and modifying to refine accuracy, as well as defining the
 bucketing categories and score scaling. Jean will test the accuracy with support from the rest of
 the team to hand classify reviews. Anne will create the dashboard with support and input from
 the rest of the team. The team will define action items and recommendations from the outputs.

 
 IV. Potential Problems
 
 Wehave identified two problems that we may require help or guidance with as we
 complete our project. First, the dataset we plan to use is only for the month of July 2023. We
 have concerns that it will not have a wide enough range of data, nor will we be able to conduct
 any trend analysis. However, we plan to combat this issue by focusing on a repeatable process
 to examine sentiment analysis that can be applied once we have more data. Our stretch goal is
 to use a web scraping tool to pull more recent data and add that to our dashboard. Second, we
 plan to test bucketing and sentiment score accuracy on a random sample of the dataset
 (approx. 100 reviews). If we were to deploy this into production we would want to use a larger
 random sample to guarantee accuracy of sentiment score and bucketin
