Business needs

    The goal of this project is to develop a machine learning model that effectively predicts life expectancy in different countries around the world. Such a model would allow medical and government organizations to accurately identify key factors affecting life expectancy and develop effective strategies to improve it. By accurately predicting life expectancy, governments and organizations will be able to optimize their health care spending, improve the quality of health care services, and reduce mortality rates, which will contribute to an overall improvement in the standard of living of the population.

Requirements

    python 3.7

    numpy==1.17.3
    pandas==1.1.5
    sklearn==1.0.0

Running:

    To run the demo, execute:
        python predict.py 
    
    After running the script in the folder '../data/' will be generated <predictions.csv> 
    The file has 'prediction' column with the predicted result value and 'True' for real values.
    
    The input is expected  csv file in the  folder  './data/' with a name <test.csv>. The file should have all features columns. 

Training a Model:

    Before you run the training script for the first time, you will need to create dataset. The file <train.csv> should contain all features columns and target for prediction Life Expactency.
    After running the script the "insert_value_Polio.pkl", "insert_value_GDP.pkl", "label_encoder_Country.pkl", "label_encoder_Status.pkl", validation_results.txt, "feature_importance.txt" and other will be created.
    Run the training script:
        python train.py

    The model accuracy is 95%
    There is no fraud check.


Model Evaluation Metrics:

    The model performance is evaluated using the following metrics:
    
    Score.
    Mean Squared Error (MSE).
    Mean Absolute Error (MAE).
    R2 Score is the most important one. 
    
    The results are saved in file named like 'validation_results.txt' in the folder './saves/'.