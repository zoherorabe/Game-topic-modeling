# Topic Modeling with Reviews

## Notebooks

- **bertopic_all_games_neg.ipynb:** Conducting topic modeling with BerTopic on all negative reviews for all games with fine-tuning BERT model parameters.

- **bertopic_all_games_pos.ipynb:** Conducting topic modeling with BerTopic on all positive reviews for all games with fine-tuning BERT model parameters.

- **world_of_tanks_blitz_bertopic_nmf.ipynb:** Conducting topic modeling with BerTopic and NMF on the positive and negative reviews for the "World of Tanks Blitz" game.

- **lda_modeling.ipynb:** Conducting topic modeling with LDA on the positive and negative reviews for the "World of Tanks Blitz" game.

- **data_exploration.ipynb:** Data understanding and exploration.

## Chosen Topic Modeling Algorithm: BerTopic

I have chosen the BerTopic algorithm for extracting insights from the reviews. Here are the reasons for this choice:

1. **No Need for Pre-deciding Number of Topics:** With BerTopic, there is no need to decide the optimal number of topics before training.

2. **Minimal Pre-processing:** BerTopic does not require deep pre-processing, making it suitable for dealing with misspelled words and words from different languages.

3. **Robust to Mispelled Words:** BerTopic focuses on semantic representation, making it robust to misspelled words in reviews.

4. **Multilingual Support:** BerTopic can handle reviews with words from different languages, thanks to its multilingual model.

5. **Short Review Handling:** As the majority of reviews are short, BerTopic, which extracts one topic for each review, is well-suited for this scenario.

## Future Improvements

- **Different BerTopic Text Embedding Techniques:** Experimenting with various BerTopic text embedding techniques for potential enhancements.

- **Sentiment Analysis Enhancement:** Instead of relying on game ratings for sentiment extraction, exploring the use of pretrained transformer models to extract sentiments from reviews.

