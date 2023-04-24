# Cracking_the_Stress_Code
1. Folders to be created in Google Drive:
    a. Main folder : DS
    b. Sub folder1 : DS/extract
    c. Sub folder2 : DS/Input_data
2. Stress-Predict-Dataset-main.zip has to be placed in folder structure : DS/Stress-Predict-Dataset-main.zip
3. Above folders has to be created and Stress-Predict-Dataset-main.zip file has to be placed in respective file path
4. EDA.ipynb file have to be run - This file contains 
     a. Data preparation steps - gets the raw data file and combine it 
     b. Data preprocessing 
     c. Visualization
     d. Data set is prepared for all the participants
     e. Data of each participant is written into .csv file and placed in filepath : DS/Input_data/
5.Execution_code.py file has to be run - This file contains
      a. Reads the .csv files from path DS/Input_data/ for all participants
      b. Common functions to train,test and evaluate models : Randomforest, LSTM and BiLSTM
      c. Execute the function - all the common functions are called and will run in a loop for all the participants and display the results
