# NLP-Final-Project
Code for Natural Language Processing - Group 5 

- [question_generation.ipyb](question_generation.ipynb) contains the code to create synthetic Question-Answer pairs from the raw paragraphs in the training set.
  - [paraphrase_questions.ipynb](paraphrase_questions.ipynb) contains code that takes the output csv from `question_generation` and creates paraphrased questions with it.
- [question_answering.ipynb](question_answering.ipynb) contains code fine-tuning pre-trained models using our generated training data
- [evaluation.ipynb](evaluation.ipynb) contains the code that was used to evaluate our QA model results
