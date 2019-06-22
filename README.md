# Politics-Adjacent Guests on the Late Show with Stephen Colbert
A look at the views for YouTube uploads of Colbert’s interviews as host of the Late Show, specifically highlighting the view counts of interviews with politicians, journalists, and others involved with politics. Colbert’s reliance on political humor seems to have attracted a younger, educated, and more liberal audience (familiar with his Daily Show and Colbert Report days) that CBS otherwise would not have. This analysis shows that his politics-adjacent guest interviews command a significant portion of total YouTube views and, in some cases, outperform interviews with movie stars.

## Wikipedia Data
Obtained using this scraper (https://roche.io/2016/05/scrape-wikipedia-with-python) on the yearly episode lists found at https://en.wikipedia.org/wiki/List_of_The_Late_Show_with_Stephen_Colbert_episodes.

## YouTube Data
Obtained using this online tool (https://tools.digitalmethods.net/netvizz/youtube/mod_channel_info.php) built by the University of Amsterdam's Digital Methods Initiative. The pull is downloaded in TAB format, so you must first convert this to a CSV file.

## Google Knowledge Data
Obtained using the Google Knowledge API, which requires your own API key.

### Google Knowledge API URL
https://developers.google.com/knowledge-graph/

### Getting an API Key
https://developers.google.com/knowledge-graph/how-tos/authorizing

# How to Read the Analysis
Start with the 01_wikipedia_scraper notebook and from there proceed in numerical order through the other notebooks.
