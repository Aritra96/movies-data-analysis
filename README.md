# TMDb Data Analysis
_Exploring movies revenue, popularity, upvotes and runtime with over 10,000 movies and TV shows!_

# Project Overview

This project explores the TMDb (Movies Dataset) data which has a list of ~11000 movies from IMDB. In addition to regular movies, it also features TV series and short films. The dataset itself has a number of variables including, but not limited to, budget, revenue, popularity, et al. Based on these factors, the following questions will be investigated:

1. _What is the relationship between revenue and popularity, revenue and vote count, revenue and vote average, and revenue and runtime?_

2. _Does the release date (month) of a movie/tv series affect its popularity, revenue, vote count and vote average?_

<b>Note:</b> Throughout this project, I will be referring to tv series and movies and short films all as "movies" for the sake of simplicity.

### Running the program

You can either run the .ipynb file on Google Colab or Jupyter Notebook or a similar environment that supports Jupyter notebooks. Or you can simply double-click the .html file to see the report on your browser.

### Program Details

This is one of those exploratory studies where I have gone through the TMDb dataset to find some specific answers to the aforementione two specific questions. 

The methodology here was as follows:

* Peek into the data to correct or to weed out imperfections - these include steps to wrangle the data with data cleaning, imputation, and elimination.
* Making sure to ask a lot of questions during this process - checkin out anything weird with the data, something unintuitive or something off. 
* Graphical exploration of the data - through histograms, correlograms, scatter plots and the like. 
* Finally, to derive inferences to support our initial thorughts or questions regarding the data.

# Requirements

* Language: Python 3.6 or above
* Libraries: pandas, numpy, matplotlib, seaborn

# Project data

* tmdb.csv - A dataset of over 10K movies and TV shows with details specific to each entity such as release date, votes, popularity, revenue, etc.

# Built with

* [Python 3.6.6](https://www.python.org/) - The language used to develop this.
* [pandas](https://pandas.pydata.org/) - One of the libraries used for this.
* [numpy](http://www.numpy.org/) - One of the libraries used for this.
* [matplotlib](https://matplotlib.org/) - One of the libraries used for this.
* [seaborn](https://seaborn.pydata.org/) - One of the libraries used for this.

# Author

 * [Aritra Chattaraj](https://github.com/aritra96) - Sole author for this program. Mentioned all the help received in 'Acknowledgements' section.
  
# Acknowledgements

* [Stack Overflow](https://stackoverflow.com/questions/25146121/extracting-just-month-and-year-from-pandas-datetime-column-python)

* Special thanks to [Carly Hochreiter](https://carly-data.com/)
