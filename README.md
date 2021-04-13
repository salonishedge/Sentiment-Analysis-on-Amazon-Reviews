# Whether to Buy Amazon Product or no
First Data will be scrapped from the amazon website using BeautifulSoups and Requests
This data is then cleaned and the particular hook where the actual review is present is extracted
This file is then converted to csv and saved
After that Sentiment Analysis is done on the reviews 
The Subjectivity and Polarity of the reviews are added in the dataset
Based on the Polarity the reviews are categorised as positive,negative or neutral
If there are more positive review, then we buy the product
