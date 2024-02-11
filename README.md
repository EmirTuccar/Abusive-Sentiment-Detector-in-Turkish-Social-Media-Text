# Abusive-Sentiment-Detector-in-Turkish-Social-Media-Text

These models were trained by using HATC dataset which made by:
"Karayiğit, Habibe, Çiğdem İnan Acı, and Ali Akdağlı. "Detecting abusive Instagram comments in Turkish using convolutional Neural network and machine learning methods." Expert Systems with Applications 174 (2021): 114802."

We just made a little addition to this dataset(We can't publish it because of license issue) with Reddit API and trained models to find which one is best for abusive sentiment detection.

Ensemble Model and Random Forest trained models size is so big so here is the download links.

Random Forest
https://drive.google.com/file/d/1eTMv-VGgb4bojJvLAHy4Z9tI42AvX06U/view?usp=drive_link

Ensemble model with RF and SVM
https://drive.google.com/file/d/1t4NPSLGfjzqzmp0p3uzYNZPNrTL3nBkF/view?usp=drive_link


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
