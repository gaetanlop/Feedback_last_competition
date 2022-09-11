# Feedback_last_competition

## Before Start Ideas

* Treat the competition as a classification instead of a regression (https://www.kaggle.com/competitions/petfinder-pawpularity-score/discussion/301044)
* Use multiple heads on top of deberta embeddings like 3 SVR with different params (https://www.kaggle.com/competitions/petfinder-pawpularity-score/discussion/301044)
* Use Petfinder winner solution => Rapids SVR (https://www.kaggle.com/competitions/petfinder-pawpularity-score/discussion/301686 + Starter notebook: https://www.kaggle.com/competitions/feedback-prize-english-language-learning/discussion/351577)
* Change the pretrained backbones: deberta trained on other feedbacks or trained on readability feature of commonlit.
* Pseudo labeling either using prev competition data or creating new ones using gpt or T5 (so that it is from students from same age)
* Verify as fasdt as possible if adding diversity/plurality will increase performance (pipeline of ensembling to do fast)
* Try gpr for ensembling (https://www.kaggle.com/competitions/commonlitreadabilityprize/discussion/258554)
* Try to recreate an approach using sentence transformer like the first of the competition (based on readability feature for example?) (https://www.kaggle.com/competitions/commonlitreadabilityprize/discussion/257844)
* ...
