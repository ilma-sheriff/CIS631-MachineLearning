# Sentiment Analysis of Social Media Data on Perception Towards the COVID-19 Vaccine
The spread of the novel Coronavirus has taken over the world stagnant and impacted many aspects of our daily and social life. The World Health Organization (WHO) has declared COVID-19 as a pandemic due to droplet-based transmission and an unprecedented death rate. Furthermore, the lack of vaccinations for this novel disease, the internet has been flooded with rising concerns about public safety and well-being. Using sentiment analysis - a supervised machine learning technique, the data can be analyzed and can be further used by public health agencies to design new interventions against the spread of this disease. In this research, we propose a framework for analyzing and classifying public sentiments on the COVID-19 vaccine using Twitter data. In the proposed framework, each tweet is first assigned a polarity score ranging from -1 to 1 using TextBlob, a Python library for Natural Language Processing and Sentiment analysis. Following which, novel machine learning models are implemented to classify tweets based on polarity scores from TextBlob - into negative, neutral, and positive discrete classes. This project also leveraged various machine learning and deep learning techniques to classify Tweets.
## Once your command line is open, enter these commands:
python --version <br/>
pip --version <br/>
Make sure they're latest version

## Next, you’ll need to install keras, sklearn and nltk. At the command line, type
pip install keras <br/>
pip install sklearn <br/>
pip install nltk <br/>

# Run the project in Jupyter Notebook
### Clone the repo: 'git clone https://github.com/ilma-sheriff/CIS631-MachineLearning.git' or download code files.
#### Step 1: cd CIS631-MachineLearning - make sure all the datasets(combined_data_gather_twitter_Oct_30.csv and tweetdata.csv) and jupyter notbook files (Twitter_sentiment_analysis_covid19vaccine.ipynb, Deep Learning - Neural Network Model.ipynb, Deep Learning Model LSTM.ipynb, Random Forest Model.ipynb, SVM Model.ipynb) are in this directory
#### Step 2: Run file Twitter_sentiment_analysis_covid19vaccine.ipynb (Run all cells) 
##### Twitter_sentiment_analysis_covid19vaccine contains:
###### Exploratory Twitter Data Analysis
###### Naive Bayes Classifer and initial Random Forest Classifer - Machine Learning Models. 
#### Step 3: Run file Random Forest Model.ipynb (Run all cells) 
##### Random Forest Model contains: 
###### Random Forest Classifer (RF) - Machine Learning Model
#### Step 4: Run file SVM Model.ipynb (Run all cells) 
##### SVM Model contains: 
###### Support Vector Machine Classifer (SVM) - Machine Learning Model
#### Step 5: Run file Deep Learning - Neural Network Model.ipynb (Run all cells) 
##### Deep Learning - Neural Network Model contains: 
###### Neural Network Model (DNN) - Deep Learning Model
#### Step 6: Run file Deep Learning Model LSTM.ipynb (Run all cells) 
##### Deep Learning Model LSTM contains: 
###### Long short-term memory (LSTM)- Deep Learning Model

