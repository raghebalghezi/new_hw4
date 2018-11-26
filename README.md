### Question Answering Using SQuAD Dataset

This repo contains an implementation of stage2 logisitic regression for SQuAD 2.0.

### Instructions

* Please check Dockerfile
* Non-docker installation: In case docker did not work:
  * `git clone https://github.com/raghebalghezi/squad_hw4.git`
  * `cd  squad-final`
  * `unzip with_pos_overlap_score.csv.zip`
  * `pip install scikit-learn pandas matplotlib`
  * `python squad2_hw4.py`

To simplifying the process, and shorten the runtime, I have done the pre-processing in the background, and seralized the dataset. So, `serialized_df.pkl.zip` contains the following information:

* candid
* const_tags
* constituents
* cosine_2
* cosine_3
* left_span
* question
* right_span
* span_length
* text
* wh+tag
* target
* tfidf_sum
* 'tfidf_sum_2
* 'tfidf_sum_3
* glove_cos_2
