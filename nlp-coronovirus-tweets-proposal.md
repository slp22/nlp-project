#### NLP | Project Proposal

# Coronavirus Tweets   

## Question
* What is the question behind your analysis or model and what practical impact will your work have?
    * What were Americans tweeting about coronavirus and COVID-19 in April 2020? 
* Who is your client and how will that client benefits from exploring this question or building this model/system?
    * To better inform future pandemic communication strategy, the [Centers for Disease Control and Prevention](https://www.cdc.gov/coronavirus/2019-ncov/index.html) want to understand what type of information spread via Twitter early on in the COVID-19 pandemic in the United States. 

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
        - `lang(uage)`
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
        * Remove punctuation, digits, special characters, convert to lowercase
        * Stemming/lemmatization, parts of speech, named entity recognition
        * Vectorize
    * Dimension reduction/topic modeling
        * VADER Sentiment Analysis
        * Latent Semantic Analysis
        * Non-Negative Matrix Factorization 