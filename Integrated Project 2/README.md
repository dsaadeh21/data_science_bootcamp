# Project description
The data is stored in three files:
- 'gold_recovery_train.csv' — training dataset download
- 'gold_recovery_test.csv' — test dataset download
- 'gold_recovery_full.csv' — source dataset download

- Data is indexed with the date and time of acquisition (date feature). Parameters that are next to each other in terms of time are often similar.
- Some parameters are not available because they were measured and/or calculated much later. That's why, some of the features that are present in the training set may be absent from the test set. The test set also doesn't contain targets.
- The source dataset contains the training and test sets with all the features.
- You have the raw data that was only downloaded from the warehouse. Before building the model, check the correctness of the data. For that, use our instructions.

# sMAPE FORMULA REFERENCES
![image](https://user-images.githubusercontent.com/110855552/206306252-4039fb47-8e37-4744-874b-d8edb4897aa1.png)
![image](https://user-images.githubusercontent.com/110855552/206306285-a8e6a5e9-6c63-49a7-b1c4-a423634168c6.png)

# Goal 
- Write a function to calculate the final sMAPE value.
- Train different models. Evaluate them using cross-validation. Pick the best model and test it using the test sample. Provide findings.
