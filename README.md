### Text Analysis Project README
## Project Overview
![heart disease ss](https://github.com/shiva0123m/Text-Summarization/assets/117260868/17b714cb-deb7-4fe1-b276-7c1d4a768ee7)


Features
List the key features of your text analysis tool. This could include:

Text summarization
Keyword extraction
Sentiment analysis
Language support
Input and output formats

## Getting Started
# perform preprocessing of total data
  # It include
  tokenization
  lemmatization
  bag of words
  tf-idf
  wieghtage of words

bash
# Installation
pip install -requirement.txt
  contians:
   pandas 
   spacy
   numpy
# run
run app.py

## Basic code for summmarization
from text_analysis_tool import summarize_text
text = "Lorem ipsum dolor sit amet, consectetur adipiscing elit..."
summary = summarize_text(text)
print(summary)



