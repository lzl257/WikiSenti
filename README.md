[![Binder](https://notebooks.gesis.org/binder/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/lzl257/WikiSenti/master?urlpath=%2Fapps%2FWikiSentiFlow.ipynb)

# WikiSenti

## Description

This demonstration contains three widgets that analyse sentiments on Wikipedia entities. Wikipedia entities contains entities 
in Wikipedia Article and Wikipedia Talk. Talk page is an area for editors to discuss about corresponding article, 
which can be visited from upper left side of article page. All the widgets include entities of both People and Events. 
The date for people indicates birth date, while the date for events indicates occurrance date.

Three widgets are:

1. **WikiSentiFlow**: used to show the changes of sentiment scores for Wikipedia entities (concepts) over time. It shows 25%, 50% (median), 
75% quantile of sentiment score for each month to present the sentiment distribution.

2. **WikiSentiScatter**: used to show sentiment score including positive score and negative score for Wikipedia entities (concepts) verying with time.

3. **WikiSentiViewer**: used to show sentiment distribution on geolocation for Wikipedia entities.


The text of Articles and Talks is extracted from Wikipedia Dump, and time stamps are extracted from [DBPedia](https://wiki.dbpedia.org/).

The scores are calculated with term frequency for sentiment words based on certain lexicons (OL, MPQA, LIWC, ANEW). 
For ANEW we take valency into account too.

## Getting Started

1. Click the Binder badge above or this [Binder link](https://notebooks.gesis.org/binder/v2/gh/lzl257/WikiSenti/master?urlpath=%2Fapps%2FWikiSentiFlow.ipynb)
to run the notebooks. (It may takes around 10 mins to prepare the environment)

2. The widget will start automatically and now you can operate with it. If you want to check the details of code, please click the "Edit App" button in toolbar

3. If you want to switch to the next notebook, just click the link below the current widget.

## Run It Locally

If you want to run it locally, you need to install libraries listed in environment.yml with version showed in requirements.txt. 
Dataset can download dataset in the [dropbox link](https://www.dropbox.com/sh/mt7by5f1wgl6n3z/AACddwkFPq5lPpH3ry83MgSDa?dl=0).

