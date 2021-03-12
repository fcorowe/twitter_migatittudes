# Data

The data set is released in compliance with the Twitter's Terms and Conditions, under which we are unable to publicly release the text of the collected tweets. We are, therefore, releasing the tweet IDs, which are unique identifiers tied to specific tweets. The tweet IDs can be used to query Twitter’s API and obtain the complete Tweet object, including tweet content (text, URLs, hashtags, etc.) and authors’ metadata. This process to retrieve the full Tweet object from Twitter starting from a tweet ID is referred to as hydration. There are several easy to use tools that have been developed for such purposes, including the [Hydrator](https://github.com/DocNow/hydrator) and [Twarc](https://github.com/DocNow/twarc). You can also use Twitter’s API to retrieve the data using our code provided [here](twitter_migatittudes/methods/01_calling_and_processing_twitter_Data.ipynb).

## Data source

We used the Twitter Premium API to download all tweets containing migration related key words, accounts and hashtags. Please refer to the paper for details on the data set, including dates, search terms and geographic information used for the data collection.