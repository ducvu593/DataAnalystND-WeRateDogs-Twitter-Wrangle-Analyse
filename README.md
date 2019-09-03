# Data Wrangling and Exploratory Analysis - Twitter's WeRateDogs
This is the fourth project of the Udacity's "Data Analyst Nanodegree". The Twitter's WeRateDogs dataset is investigated. This dataset contains the basic information of over 5000 tweets from WeRateDogs. The core of this project revolves around the process of data wrangling and exploratory analysis of the data. 

In the data wrangling process, the data is first gathered from different sources (download programmatically and using Twitter's API).
Then, the data is assessed and the tidiness and quality issues of the data are documented. 
Subsequently, these issues are addresssed through the cleaning of the data.

The exploratory data analysis involves analysing the data and creating visualisations to convey interesting insights about the dataset.

A final report is provided to summarise the findings of the dataset.

### Quick Guide

- A concise summary of the most interesting insights: **Report_Exploratory_Data_Analysis_and_Visualisations.pdf**. 
- View the comprehensive code and comments: 
    1. Open the **Wrangle_and_Analyse_Data.ipynb** and view it straight on GitHub, or
    2. Open the **Wrangle_and_Analyse_Data.html** and prepend the URL with the URL link shown in the penultimate section.
- Run the code: Follow the steps in the next section using the file **Wrangle_and_Analyse_Data.ipynb**.


### Running the Code in Jupyter Notebook 

1. Download Jupyter Notebook for example through [Anaconda-Navigator](https://docs.anaconda.com/anaconda/navigator/).
2. Open Jupyter Notebook either through the Anaconda-Navigator App or type "jupyter notebook" in the command line (this will open in a browser).
3. Select directory that contains the Jupyter Notebook file (extension ipynb) and the CSV files. Make sure all files are in the same directory as the notebook.
4. Run the code from the toolbar.

### To Open the HTML File

Prepend the HTML link with https://htmlpreview.github.io/?. 

For example, https://htmlpreview.github.io/?https://github.com/ducvu593/DataAnalystND-Wrangle-Analyse-WeRateDogs-Twitter-Data/blob/master/Wrangle_and_Analyse_Data.html.

### Understanding the Files

For the "Data Wrangling Process" section, the files required are *twitter_archive_enhanced.csv*, *tweet_json.txt*, and another file downloaded from the web. 
Note that the code that runs and obtains the Tweet information by querying Twitter AP should be skipped (Section 3 under Gathering Data). 
This file has already been prepared under the name *tweet_json.txt*.

For the "Exploratory Data Analysis" section, the master file containing the combined datasets is required, *twitter_archive_master.csv*.
