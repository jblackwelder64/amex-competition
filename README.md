# amex-competition
Our code for the American Express - Default Prediction competition hosted on Kaggle

In order for the code to work, place train_data.csv, train_labels.csv, and test_data.csv in the root project directory. May also have to manually create some empty folders within the project directory, these being: Train_Parquet, Test-Parquet, Outputs, Train-Cat-Columns, and Models. 

Training with a 10,000 row sample is almost instantaneous while using the full dataset took me about 40 minutes, although I believe this time can be reduced substantially. Making predictions on the full dataset also takes around 40 minutes currently.   
