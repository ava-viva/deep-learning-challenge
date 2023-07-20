# deep-learning-challenge
 
AlphabetSoup Charity Project:
This project involved the development of a binary classifier using machine learning and neural networks to predict the success of organizations funded by Alphabet Soup. The provided dataset contained information on over 34,000 organizations that had received funding from Alphabet Soup over the years.

Preprocessing the Data:
The dataset was preprocessed using Pandas and scikit-learn's StandardScaler(). The "EIN" and "NAME" columns were dropped, and categorical variables were encoded using pd.get_dummies(). The data was then split into features (X) and target (y) arrays.

Compiling, Training, and Evaluating the Model:
A neural network model was designed and trained using TensorFlow and Keras. The model was compiled, fitted to the training data, and evaluated for loss and accuracy using the test data.

Model Optimization:
Efforts were made to optimize the model to achieve a target predictive accuracy higher than 75%. Adjustments were made to the input data, such as dropping or modifying columns, creating additional bins for rare occurrences, and adjusting the number of values in each bin. Changes were also made to the model architecture, including adding more neurons or hidden layers, utilizing different activation functions, and adjusting the number of epochs.

Report on the Neural Network Model:
A comprehensive report was prepared to analyze the performance of the deep learning model created for Alphabet Soup. The report provided an overview of the analysis, discussed the data preprocessing steps, and described the model compilation, training, and evaluation processes. The achieved model performance was assessed, and the steps taken to increase model performance were explained. 
