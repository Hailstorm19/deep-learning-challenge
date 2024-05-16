# deep-learning-challenge

## Overveiw
With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results:
 - Data Processing
     - The target variable for the model was the 'IS_Successful' column of data.
     - The variables that was the feature of the model were the other columns of data
     - The variables that were removed were 'EIN' and 'NAME'.

   - My first attempt in Starter_Code.ipynb used 80 units for the first hidden layer, 30 units for the second hidden layer and 100 epochs. This had an accuracy of roughly 0.7295.
   - My next 3 attempts were in AlphabetSoupCharity_Optimisation.ipynb:
       - I tried 1600 units for first hidden layer and got an accuracy of 0.7311
       - I tried 400 units for first hidden layer and got an accuracy of 0.7313
       - I tried 1600 units first later and 200 epochs and got accuracy of 0.7259

## Summary 
The deep learning model provided a different way to make predictions using data. However it is time consuming and as shown, it was hard to get an accuracy above 75%. Another model that can be used is the Random Forest model, which can be used to predict data.

