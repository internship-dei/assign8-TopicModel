### assign8-TopicModel

For the web scraped text in data.zip folder , Create a Topic Model (using LDA) and identify relevant topics based on the terms that are present in the topic.Save the trained topic model and assign topics to each of the file document mentioned in data.zip folder

Your output dataframe should be having the 3 fields below:

**Web page file | Tokenized Text | Topics Distribution **

----------------------------
*Suggested Approach* 

* After cleansing and NLP Pipeline preprocessing , utilize LDA Model from the Gensim library
* Keep the number of topic minimal and independent (since data is less)
* Play with the hyperparameters and tune for achieving optimal Topic Coherence score
* Once the optimal topics are achieved , intuitely assign Topic Categories.This will be a process of looking over the terms a Topic possess and assigning Manually
* Do visualizations - Word Clouds , Distribution of words etc
* Save the trained model. And then based on the topics identified  , assign the topic distribution to each document
* Obtain the resultant dataframe


*References*:

1. https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/
2. https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/
3. https://radimrehurek.com/gensim/models/ldamodel.html
4. https://stackoverflow.com/questions/46326173/understanding-lda-topic-modelling-too-much-topic-overlap



