# Cracking_the_Stress_Code
1. Folders to be created in Google Drive:
    1. Main folder : DS
    2. Sub folder1 : DS/extract
    3. Sub folder2 : DS/Input_data
 2. Stress-Predict-Dataset-main.zip has to be placed in folder structure : DS/Stress-Predict-Dataset-main.zip
 3. Above folders has to be created and Stress-Predict-Dataset-main.zip file has to be placed in respective file path
 4. EDA.ipynb file have to be run - This file contains 
     1. Data preparation steps - gets the raw data file and combine it 
     2. Data preprocessing 
     3. Visualization
     4. Data set is prepared for all the participants
     5. Data of each participant is written into .csv file and placed in filepath : DS/Input_data/
5.Execution_code file has to be run - This file contains
      1. Reads the .csv files from path DS/Input_data/ for all participants
      2. Common functions to train,test and evaluate models : Randomforest, LSTM and BiLSTM
      3. Execute the function - all the common functions are called and will run in a loop for all the participants and display the results
