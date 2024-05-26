Business needs

    The aim of this project is to develop a machine learning model that effectively assesses the creditworthiness of customers, thereby minimizing the risk of loan defaults. By accurately evaluating customer creditworthiness, the bank seeks to enhance its lending processes and mitigate potential financial risks.
        
Requirements

    python 3.7

    numpy==1.17.3
    pandas==1.1.5
    sklearn==1.0.0

Running:

    To run the demo, execute:
        python predict.py 

    After running the script in saves folder will be generated <predictions.csv> 
    The file has 'prediction' column with the result value.

    The input is expected  csv file in the same folder with a name <test.csv>. The file should have all features columns. 

Training a Model:

    Before you run the training script for the first time, you will need to create dataset. The file <train.csv> should contain all features columns and target for prediction CreditWorthiness.
    After running the script the "encoding_dict.pickle", "insert_value.pkl", validation_results.txt, "feature_importance.txt" and other will be created.
    Run the training script:
        python train.py

    The model accuracy is 96%
    There is no fraud check.