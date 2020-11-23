COMP6200 Data Science Portfolio 
===

Name: Karthik Varm Keerthipati \
Student Id: 46272496 \
Contact: karthikvarma.keerthipati@students.mq.edu.au

Portfolio-1:

1. Analysis of CSV data for cycling 
2. Combined the two data sets Strava and Cheetah using join method.
3. Removed rides with no measured power (where device_watts is False).
4. By looking at the variables time, distance, average speed, average power, TSS stating whether normally distributed or skewed.
5. Exploring the relationships between the variables and corrolating with each other to find the relationships.
6. Exploring the values of NP for races vs the overall set of rides to see and finding whether races are more challenging than rides in        general.
7. Creating a summary of rides over the year and generating a plot which summarises the number of km ridden each month over the period of      the data.Overlaying the above plot with the sum of the Training Stress Score and the average of the Average Speed to generate an overall    summary of activity.

Portfolio-2:

1. Analysing COVID-19 data
2. Exploring the data by grouping the countries having regions as states and dropping the columns for lat and long.
3. Selecting the data for one country and plotting it to see the exponential rise.
4. Selecting the data for countries such as Australia, China, USA, UK, Italy and India. Plot their data on the same graph to see the            comparison between countries.
5. Choosing the data for different countries aligned from the time that they have 100 confirmed cases.
6. Taking the population data set and normalising the data with population to measure the number of cases per million people in the            population of a country.
7. Predicting a model using LinearRegression.

Portfolio-3:

1. Analysing the books data having summaries and genres.
2. Filtering the data so that only the target genre labels are included and we assign each text to just one of the genre labels.
3. Cleaned the data by removing stopwords, whitespaces, numerics and special characters.
4. Splitting the data into train and test sets.
5. Modelling the data and using pipeline to implement the TFIDF transformer and Count vectorizer to check the importance of words.
6. We are taking multiple models and comparing those based on the accuracy scores.
7. The models are KNeighborsClassifier, MultinomialNB, LogisticRegression, SGDClassifier which will be used to predict the genres.
8. The LogisticRegression and SGDClassifier has the highest accuracy compared to the other.