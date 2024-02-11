# Abusive-Sentiment-Detector-in-Turkish-Social-Media-Text


Reddit API

Installation:

To run this data scraper program, you need to visit the Reddit apps site and create an app. 
After entering the necessary inputs, you can run the program using the key and secret key provided to you. 
For the required library, you can download the Reddit API-specific praw library with the command "pip install praw".

Usage:

You can access all the comments posted under a desired post by pasting the link of the post into the 'ur' variable and using the script created within a for loop.

-------------------------------------------------------------------------------------------------------------------

Training Models

Installation:

To use this detector, you need to install all the imported libraries using 'pip install'. 
Additionally, since our dataset is in Excel format, you can retrieve it using the pandas library.

Usage:

The training of each algorithm is done in separate code sections. 
If desired, you can modify the parameters of the classifiers and conduct your own training. 
You can run the 'detect_abusive_sentiment' function using your desired classifier by writing the sentence or word whose sentiment level you wish to see into the 'new_text' variable. 
Since each classifier has different accuracy values, the sentiment level can vary from one classifier to another. 
When you run the program, it will tell you the sentiment level. 
The saved models are available in the project in the joblib format and can be used for other projects if desired.
