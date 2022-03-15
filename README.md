# Service_request_identifier
An assignment showing how NLP can be applied to a working industry to solve a problem of minimizing Human ressources.

The Project is about a Classifier developed by me, that, by using Keras(tensorflow), Spacy, pandas, spark and a self created pipeline to Create a tagging system to categorize support requests if they need further human support. 

# The structure of the Pipeline
https://github.com/Thejacensolo/Service_request_identify/blob/main/%C3%9Cbersichtsdiagramm.svg

the system works in 4 Steps:
1) Train a model based on data and select the most common POS tags, NER tags and Common words
2) create a sorting mechanism using the above mentioned Filters
3) enhance that scoring by running a pattern recognition via the trained model. Unsupervised machine learning suffices for our intent here
4) Sort out request based on a combined scoring of Rule and Model filtering
