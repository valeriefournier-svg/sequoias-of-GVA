# Sequoias of Geneva

Here is my very humble first project I'm happy to complete, I will do better next time.

## What I expected
I wanted a data set with all the sequoias of Switzerland, assuming there will me only a few dozens, but it happened to be thousands of them. As Switzerland is a federal state of 26 cantons, all I could find on [opendata.swiss] (https://opendata.swiss/en/dataset?keywords_en=tree) was data for a bunch of cantons but no national listing. I found then a wonderful site for biodiversity with an API, [gbif.org](https://www.gbif.org/), Global Biodiversity Information Facility, but I failed to registrate (it just does'nt work). So I decided to focus on Geneva, and go to [sitg.ge.ch](https://sitg.ge.ch/), where I was able to download a csv of all trees in the state.

## Data analysis
Not that much. I sorted the dataframe by species, sequoias, and mapped them using datawrapper. I created several versions in QGIS, and I had to, because the longitude and latitude of the trees were in a unique swiss code (why, but why) which meant I had to convert them from CH1903+/LV95 to WGS84. I spent a lot of time solving this very particular (swiss) problem.
I was disappointed that I couln't design the swiss map of the sequoia locations myself, but I will keep trying.
I also would have been proud if I had managed to compare the current number of trees vs 50 years ago, or to chart what proportion the sequoias represent compared to the total number of trees or species. I also will keep looking for a way to do this.

## What I learned
It tooks me 15 hours to finish this, I realize my skills are for the moment very limited, especially in API and scrapping but I will continue to practice, practice and practice again.

