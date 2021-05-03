# Numan_task
Assessment task for Backend Data Engineer Internship
Before proceeding with the assignment task please make sure to fill up the given questionnaire form share already and available at Backend Data Engineer Internship Questionnaire Form.

2 identical XLS files are shared which contains data sampled at 1 sample/second

These 2 data files are from the same data source and represents same data, due to space restrictions of the file type it is divided into 2 separate files named 'data.xlsx' and 'data_1.xlsx' and while saving the data, it is also saved not accordingly, follow the index column named 'Record Index' to see the parity.

# Tasks
Create 3 separate '.csv'* files named 'detail.csv', 'detailVol.csv' and 'detailTemp.csv'.

Combine all the data in sheets named like "Detail_67_" only, among the two data files provided, and save into 'detail.csv'
Combine all the data in sheets named like "DetailVol_67_" only, among the two data files provided, and save into 'detailVol.csv'
Combine all the data in sheets named like "DetailTemp_67_" only, among the two data files provided, and save into 'detailTemp.csv' Provide attention to the column 'Record Index' which provided index values to avoid mismatching the rows while combining multiple files.
Apply down-sampling method to reduce the sampling rate to 1 sample/minute. Appy the same to 'detail.csv', 'detailVol.csv' and 'detailTemp.csv' and creating 3 files named 'detailDownsampled.csv', 'detailVolDownsampled.csv' and 'detailTempDownsampled.csv'

Apply low pass filter technique for noise removal on the data set for 'detailVolDownsampled.csv' and show the distribution of the dataset through visualization, also provide explanation of the same.

Run profile for all the functions; use cProfile for Python for profiling of individual functions.

Run unit test on each function,i.e., write test cases for each function. Use unittest for the same.

Try to maintain Coding Style Guide PEP-8, and use pylint or flake8 to check the code for PEP-8 violations.
Deliverables
One '*.py' file with detailed commented code on the working for Task 1 and its subtasks. The intention is to see how the code is architected rather than simple execution. Try employing functional programming concepts and making the code look clean by following PEP-8 coding style.
The code should be reproducible on any environment; i.e. system agnostic and the intended data files should be generated running the code.
One '*.py' file with detailed commented code on the working for Task 2 and its subtasks. Try employing functional programming concepts and making the code look clean by following PEP-8 coding style.
The code should be reproducible on any environment; i.e. system agnostic and the intended data files should be generated running the code
One Jupyter NoteBook file for Task 3 along with visualization.
Profile testing result in a "*.txt" file for all the functions runtime; use cProfile
Unit testing result in a "*.txt" file for all the functions ; use unittest.
