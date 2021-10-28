# 
Main Goal: to learn and practice working with Twitter API and Wrangling data from various sources.

The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 
SOme info: These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Within this project I've gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it. 
And as a result of this project, I've documented my wrangling efforts in a Jupyter Notebook, plus showcased them through analyses and visualizations using Python(and its libraries) and/or SQL.

I've used: pandas, NumPy,requests, tweepy, json libraries

Project Files description:

1.twitter_archive_enhanced.csv

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets -  rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo)

2. tweets_json.txt

Gathered data via Twitter API , which contains retweet count and favorite count 

3. image_predictions_3.tsv

Every image in the WeRateDogs Twitter archive was run by educational cource instructor through a neural network that classified breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

4. Wrangle_act.ipynb notebook

Here I 've gathered all pieces of data 

5. twitter_archive_master.csv

Here I've stored the cleaned master DataFrame as an outcome of Wrangling data in wrangle_act.ipynb notebook

6. wrangle_report.pdf 

here Ive briefly described my wrangling efforts

7. Act_report.pdf

And finally as a result of this project, I've reported here some final fun insights about dogs winners. Enjoy!

Thanks for reading! :)
