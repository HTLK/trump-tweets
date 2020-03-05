# Trump Tweets Text Mining

- All files are relative paths in order to facilitate running on other computers. Set the working directory to the project folder and run the notebook there. 
- Trump tweet text is retrieved from [here](https://www.kaggle.com/jared4robertson/trumptweets).
- The dictionary we used is based on the **Harvard-IV** version, and we select the entries with `source == 'H4Lvd' in the augmented spreadsheet provided at [here](http://www.wjh.harvard.edu/~inquirer/homecat.htm). The second column indicates whether the entry word appeared in the Harvard ("H4"), Lasswell ("Lvd") or both ("*H4Lvd*") dictionaries. 
- The date range of tweets covered is the presidency of Trump - 2017, Jan 20 to the last day available 2019, Dec 05.
- There are a lot of URLs embedded in the tweets, such as photos, hyperlinks, etc. We removed them from the corpus.
- We benchmarked the sentiment scores with VIX-index levels in the concerned period.