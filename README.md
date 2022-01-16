# Earning Call Speech Sentiment Analysis
To analyze earning call speech by a CEO of a company. It will deduce sentiment analysis of the speech and provide financial results as business metric visualization.

## Motivation and Thought Process 

Company earning calls is one of the main sources of information to understand how businesses are doing and what are expectations for the next quarters.

They are quite insightful to listen to. However, it may be time consuming to go through the whole call, specially, if we are interested in multiple companies.

Therefore, what we will do in this project is to **automate the analysis of company earning calls using Python**.

With Python, we are not only able to perform quantitative analysis  Among other things, we can, for example, use natural language processing in order to analyse linguistic structure or perform sentiment analysis.
In this post, we are going to focus on passing a full transcript from company earning calls as an input. Then, we will extract key points that will help us to understand where a company is heading to and how was the recent performance. 

Below are some of the questions that we will answer:

- The company we think the provided speech transcript is related to. 
- The Financial year CEO is discussing.

## Technical Stack Used

NLP is vast an text analysis can be done using various technologies. 
For the project we have chosen minimalistic tech-stack and easy-to-integrate
technologies with high interpretability of results by normal human.

Enlisting the technologies-

- <u>Tools</u> - Jupyter Notebook 
- <u>Langauge</u> - Python
- <u>Text extraction techniques</u> - RegExp, Tokenization, Sentiment Analysis, Named Entity Recognition (NER), WordCloud, Stemming, Lemmetization
- <u>Libraries</u>
  - **Text Analysis** - NLTK, SpaCy, TextBlob, NumPy, Pandas
  - **Data Visualization** - Matplotlib, Seaborn

## Answer to primary goals

Please refer to the [notebook](speech-analysis.ipynb) for the detailed analysis and results.

## Visualization and Information Presentation

All types of visualizations are also part of [notebook](speech-analysis.ipynb). Please refer the same.

## Future Prospects

To investors and analysts, these earning calls provide valuable insight into the state of a company, which can inform their fundamental analyses and trading decisions.

In addition to looking into company earnings call, we could analyse <u>customer opinions on company products</u> to complement the sentiment analysis. We can do that, for example, by taking user tweets about company products.

Some more future aspects can be - 
- <u>Run analysis to weigh keywords</u> - to identify the most weighed parts of the speech, which can denote overall company outlook.
- <u>Feature word generation</u> - To extract words that can predict future company growth, and use them for analyzing more transcripts.
- Develop scoring algorithm to determine <u>when to buy/sell</u>.
- <u>Identify all sub-entities and competitors</u> to cross-corelate the earnings and effect on other companies from the current company earning call.

