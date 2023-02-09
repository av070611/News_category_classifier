# News_category_classifier

The columns/features in the given dataset are as follows:
● Article category - Type of news article (Target variable)
● News Headline - Headline of the news article
● Author - Author of the news article
● Short_description - Brief about what the headline is about
● Date - Date of publishing of article


Project Task 1: Cleaning text data using NLP libraries  
Task Explanation:
Text cleaning is task-specific and one needs to have a strong idea about what they want their
End result to be and even review the data to see what exactly they can achieve.
● had used of NLP libraries (NLTK, Spacy etc.) to clean the text data.
● had defined a function to Check and Remove stopwords and punctuations.
● had done Tokenize and lemmatize  text data

Project Task 2: Primary analysis on text data
Task Explanation:
● for Exploratory Data Analysis  with the use of barplots  finds most no. of articles year wise and the least no . of articles in Article category.
•	On that finds that  2012 to 2015 had most no. of article.
•	While 2018 had least no. of article.
● With the use of barplot finds the most no. of article month wise, which is like:
•	April, May and October had most no. of articles.
•	While January and feburary had least no. of articles.
● Applied barplot on Article category extract most no. of articles days wise, which are like:
•	5th, 8th and 28th of every month had most no. of articles.
•	While  1st and 31st of every have least no. article.  
● use count plot got that wellness category has most no. of articles .
•	Most number of article had article length around 170 to 180.
•	Least number of articles had article length around 130 to 140.
•	Used words cloud in sub category wellness.

Project Task 3: Deep learning model building
Task Explanation:
● import required modules .
● encoding using keras tokenizer and pad sequencing.
● Apply feature selection, choose the right features.
● Use word embedding .
•	basline model using embedding layers and simple RNN.
•	Evaluate the model .
•	Accuracy.




Project Task 4: Hyper parameter tuning, Optimizing deep learning model and validating performance.
Task Explanation :
•	Hyper-parameters were change during the training of the model.
•	On first got an accuracy of 
•	Applied the best parameters get an accuracy 0.81.

Conclusion
We come to know that we have used the RNN model to train the data and found the accuracy 82.50 % and after the hyperparameter tuning we found it 83.19%.
