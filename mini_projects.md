# These are the list of projects suggested but you are free to choose your own topic as well.


1. Deep fake detection challenge
    - We will use the dataset from https://www.kaggle.com/c/deepfake-detection-challenge/overview
    - Explore different deep neural network architectures 
    - Copying existing notebooks will result in disqualification 
    - The solution should be using tensorflow APIs or pytorch or any other framework

2. Textual entailment task
    - Given two sentences classify if first sentence follows from second sentence or if they are unrelated
    - We will use two datasets for this task Fever 2.0 dataset https://s3-eu-west-1.amazonaws.com/fever.public/fever2-fixers-dev.jsonl and https://www.kaggle.com/c/fake-news-pair-classification-challenge

3. Background news linking task from TREC 2020
    - see the details here http://trec-news.org/guidelines-2020.pdf

4. Hyperpartisan new detection
    - Use the labelled data for hyperpartisan news detection here https://github.com/BuzzFeedNews/2017-08-partisan-sites-and-facebook-pages 
    - Train a classifier for the hyperpartisan news detection
    - More details on the task is defined here 

5. Reinforcement learning
    - In this project, students can experiment and learn about various reinforcement learning algorithms within the arena of Atari games from OpenAI's gym. 
    - This project will give students the opportunity to explore the challenges and tradeoffs associated with different algorithms. 
    - Students are welcome to apply algorithms from well-known libraries, ie. stable-baselines.
    - Resources: 
        - https://stable-baselines3.readthedocs.io/en/master/
        - https://gym.openai.com/envs/#atari

6. Stock market analysis: Finding the seasonality and trend

- In this project you will investigate several stocks of your choosing to compare their seasonality and trend. Try choosing some stocks that are seasonal, like airlines, air conditioning, heating, etc. Decompose the stocks that you choose and discuss their seasonality and trend. Using one or more ARIMA models, try to predict the future price of the stock. The data is gathered from yahoo Finance, and can be accessed throug the yahoo-finance python library (https://pypi.org/project/yahoo-finance/).

7. Watermarking neural networks
    - Implementation of a custom loss function for a neural network with evaluation for different types of model stealing attacks, similar (and possibly an extension to) these two papers:

        - https://dl.acm.org/doi/pdf/10.1145/3297858.3304051
        - https://dl.acm.org/doi/pdf/10.1145/3323873.3325042

8. Fake news detection using snopes and poltificat data
    - In this project students will implement various classifiers using both neural and feature based technqiues to detect false claims from the Snopes and Politifact data.
    - Dataset is available here https://drive.google.com/file/d/1OcSQW1_bqahgKn5krQWY9Le8VGyY2utX/view?usp=sharing
    
9. Detect claims to fact check in political debates
    - In this project you will implement various classifiers using both neural and feature based technqiues to detect which sentences in political debates should be fact checked. 
    - Dataset from ClaimBuster: https://zenodo.org/record/3609356
    - Evaluate your classifiers using the same metrics as http://ranger.uta.edu/~cli/pubs/2017/claimbuster-kdd17-hassan.pdf (Table 2)
        - Classification report from sklearn provides everything
        - Group crowdsourced.csv and groundtruth.csv into one dataset. Use debates from 1960-2008 for training (27 first debates) and 2012-2016 for testing (6 last debates)
        - Create a baseline model: Should be fairly simple one, e.g. SVM, Random Forest, Logistic regression using TF-IDF or other features of your choice. Aim for 60% or more for f1 weighted average.
        - Create advanced model(s) (suggestions are given below)
            - Generate more features that a model can use. For example the context around the sentence, sentiment, named entities etc.    
            - Rule based classifier. For example, if sentence contains certain words, tags, statistics etc.
            - Deep learning (word embeddings, transformer models etc.)
            - Sub-sentence classifier. Long sentences may include several claims, so the goal is to mark the span of claim(s) within a sentence


More topics coming!
