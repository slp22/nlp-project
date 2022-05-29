#### NLP | Project Proposal

# Coronavirus Tweets   

## Question
* What is the question behind your analysis or model and what practical impact will your work have?
    * What were Americans tweeting about coronavirus and COVID-19 in April 2020? 
* Who is your client and how will that client benefits from exploring this question or building this model/system?
    * The [Centers for Disease Control and Prevention](https://www.cdc.gov/coronavirus/2019-ncov/index.html) wants to understand what information was spread early on during the COVID-19 pandemic on Twitter in the United States to better inform future pandemic communication efforts. 
    

## Data Description
* What dataset(s) do you plan to use, and how will you obtain the data? 
    * Coronavirus COVID-19 Tweets:
        - [early April](https://www.kaggle.com/datasets/smid80/coronavirus-covid19-tweets-early-april) 
        - [late April](https://www.kaggle.com/datasets/smid80/coronavirus-covid19-tweets-late-april)
* What is an individual sample/unit of analysis in this project?
    * One tweet
* What characteristics/features do you expect to work with?
    * Tweet characteristics:
        - `created_at`
        - `screen_name`
        - `text`
        - `country_code`
        - `account_lang`
        - `verified`
        - `lang`
    * Filtered for:
        - `country_code` = US
        - `lang(uage)` = English
* If modeling, what will you predict as your target?
    *  N/A
    
## Tools
* How do you intend to meet the tools requirement of the project?
    * Python, numpy, pandas, sklearn, 
    * NLTK, VaderSentiment
    * Matplotlib, Seaborn
* Are you planning in advance to need or use additional tools beyond those required?
    * None at this time.

## MVP Goal
* What would a minimum viable product (MVP) look like for this project?
    * Exploratory data analysis
    * Preprocess text data
        * Define corpus-specific stop words
        * Remove punctuation, digits, special characters
        * Stemming or lemmatization
        * Vectorize
    * Dimension reduction/topic modeling
        * Latent Semantic Analysis
        * Non-Negative Matrix Factorization 