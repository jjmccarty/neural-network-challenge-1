# Student Loan Recommendations (neural-network-challenge-1)

In this AI challenge we are evaluating a set of data that holds student information for the purpose of evaluating the potential for student loan repayment based on a variety of factors including degree choice, GPA and alumni history in the same fo similar degrees. 

## Data Preparation

Data in the set provided is looking at the ```credit_ranking``` as a target for the neural network and all remaining data is scaled using ```StandardScaler```

## Compiling and Evaluating Data

For our neural network we are utilizing TensorFlow to predict the credit quality of a student based on the features provided in the the dataset given.  In this case we are creating a deep neural networking based on the count of all features in the dataset. 

Two hidden layers are created and the the model is compiled using ```binary_crossentropy``` as the loss function and the ```adam``` optimizer.  Accuracy metrics will be displayed 

## Storing and retrieving the model

Model information is stored and retrieved from ``` saved_models/student_loans.keras ``` for prediction
