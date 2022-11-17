Do note to/that: 

1. Change the save_file and read_file functions for pickling data as it currently points to our google drive 

2. Re-running the code would mean that the generated hyperparemeters for all models and the SelectKBest values would be different from
the one we obtained and are using 

3. To avoid running the code to generate model hyperparameters and SelectKBest values, change the respective 'load' parameter in the code 
chunk to load the pickle data instead 

4. Things inside the folder: Source code, README.txt, and a folder which contains the pickle data

5. It might be better to run the code on colab, due to the differing library versions 