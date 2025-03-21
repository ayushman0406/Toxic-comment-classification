Toxicity Classification:
1. Business Problem:
Source: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification

Problem Statement: Given a comment made by the user, predict the toxicity of the comment.

2. Machine Learning Problem Formulation:
2.1 Data:
Source: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data
    We have one single csv file for training and one cvs file to test.
        - **Main Features:**  
    - `comment_text`: Contains text data used to determine toxicity.  
    - `target`: Target values (ranging between 0 and 1) representing toxicity levels.  

    - **Toxicity Subtype Attributes (Not for Prediction):**  
    - `severe_toxicity`  
    - `obscene`  
    - `threat`  
    - `insult`  
    - `identity_attack`  
    - `sexual_explicit`  

    - **Identity Attributes Extracted from Comment Text:**  
    - `male`  
    - `female`  
    - `homosexual_gay_or_lesbian`  
    - `christian`  
    - `jewish`  
    - `black`  
    - `white`  
    - `asian`  
    - `latino`  
    - `psychiatric_or_mental_illness`  

    - **Additional Metadata from Jigsaw:**  
    - `toxicity_annotator_count`  
    - `identity_annotator_count`  
    - `article_id`  
    - `funny`  
    - `sad`  
    - `wow`  
    - `likes`  
    - `disagree`  
    - `publication_id`  
    - `parent_id`  
    - `created_date`  
