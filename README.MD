Notebooks:
    - bertopic_all_games_neg.ipynb: conducting topic modeling with BerTopic on all negative reviews for all games with fine-tuning bert model parameters
    - bertopic_all_games_pos.ipynb: conducting topic modeling with BerTopic on all positive reviews for all games with fine-tuning bert model parameters
    - world_of_tanks_blitz_bertopic_nmf.ipynb: conducting topic modeling with BerTopic and NMF on the positive and negative reviews for the world of tanks blitz game.
    - lda_modeling.ipynb: conducting topic modeling with LDA on the positive and negative reviews for the world of tanks blitz game.
    - data_exploration: data understanding and exploration


Which Topic modeling algorithm I will chose for this task:
I will chose the BerTopic to extract the insights from the reviews, and the reasons for this:
    - with Bertopic there is no need for decide the optimal number of topcis before the training
    - there is no need to conduct deep pre-processing 
    - I found many mispelled words in the reviews, and those can effect the LDA, NMF if we didn't remove them, but with BerTopic it deosn't matter, because the model foucs on semantic representation.
    - I found many words from different language, like franch therefore which we need to remove them in the preprocessing step before LDA, NMF but with BerTopic we can use Multilangual model which able to understand all the languages.
    - the majority of reviews has a short length, therefore we can say that for each review there is only one topic, because BerTopic only extract one topic for each review.

future Improvments:
    - I might try with different BerTopic text embedding techniques.
    - Some reviews with high rate contain negative feedbacks, and some low rated reviews contain positive feedbacks in our dataset. therefore instead of relying on the game rate for extracting the sentiments for the reviews I will use different techniques like pretrained transformer model to extract the sentiments.
