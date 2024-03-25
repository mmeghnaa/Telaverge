Telaverge- Coding Project

DESCRIPTION OF THE CODE

1. Tweet Retrieval and MongoDB Insertion: Data scraping and fetching of the  tweets related to various keywords using the Nitter scraper. Inserts the fetched tweets into a MongoDB database along with engagement metrics and a timestamp. MongoDB is used since it is a distributed database, and since data from social media are unstructured, MongoDB is the best for this purpose.

2. Database Connection and Sample Document Display: Connects to the MongoDB database to fetch and display sample documents from the collection 'Telaverge'. The sample documents are shown to cross check with the actual mongodb database.

3. Sentiment Analysis, Scoring, and Smart Querying: Performs sentiment analysis using NLTK's SentimentIntensityAnalyzer. Defines a scoring algorithm to calculate relevance scores based on engagement metrics, sentiment scores, and user preferences. Implements smart querying to check for recent updates based on keywords and timestamp in the MongoDB collection. The scoring algorithm is found using the polarity scores which comprises of the positive, negative, neutral and compound scores. The user has the option to choose the number of tweets whose sentiment analysis the user wants on.

4. User Interface and Experience: Provides a user interface for entering keywords of interest and viewing real-time updates. Calculates relevance scores for user-defined keywords and displays the scores along with relevant updates. This interface gives the option to choose among the 3 options
    i. Enter keywords of interest - shows the user the information related to their entered keyword
    ii. View real-time updates- Checks whether the tweets fetched are recent and fresh or not.
    iii. Exit - Exits the user interface

6. Data Visualization: Uses matplotlib to plot sentiment scores of tweets as a bar graph. The bar graph shows scores for each fetched tweets. Also includes a pie chart for comparing engagement metrics (likes) with sentiment scores.

7. Disclaimer: Prints a disclaimer regarding the interpretation of sentiment based on compound polarity scores. It is a description about the bar graphs showing the sentiment scores of the corresponding tweets.
   
Overall, the code combines Data/Web scraping (twitter, now known as X), sentiment analysis, database operations, user interaction, and data visualization to provide insights into real-time social media updates and sentiment analysis results.
