Overview: 

The purpose of this analysis was to conclude whether a prediction model with this given data
can be accurate enough for business use.

Based on the data provided and the models created, it was analyzed that this data is not
strongly capaable of predicting whether or not applicants for funding will be successful. Though the 
previous statement may be subjective, the conclusion was based on the findings of the model created
and trained. 


Results: 

The variable that was considered the target for my model was the 'IS_SUCCESSFUL' column in the dataframe while the variable considered as features were the rest of the dataframe that was cleaned.
The 'EIN' and 'NAME' columns were removed from the dataframe as they were considered non-beneficial for the purpose of this analysis.

2-3 layers and 2 different kinds of activation functions were used for the neural network model in order to improve the accuracy of the model with a particular epoch argument. After multiple attempts, it was unable to achieve the target model performance. Such attempts include adding an extra hidden layer, manipulating which activation function to be used, and changing the amount in the epochs argument.    


Summary:

The model resulted in having a ~69% accuracy and .63 loss. I would recommend using a RandomForestClassifer instead for the model to predict because I believe it is proficient with this sort of dataset containing multiple features.



