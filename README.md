# Hindi_Text_Prediction_using_LSTM

# Objective
This project aims to build LSTM models that can predict hindi texts based on a charecter level prediction.

# About the data
The code requires the following dataset from : 
The dataset contains : First Fourteen chapters from the book chankya neeti in hindi language, with around corpus length of 45245. 

# Methodology
The code consists of 3 main parts:
- Data loading and exploration: invloves loading the chankya neeti hindi text file with the first 14 chapters as training data, followed by exploring the corpus of data.
- Preprocessing: Involves getting rid on data in English and numbers to simplify the model training process.
- Model building and training: This part using the keras libraries to build a single LSTM model with only 128 units and softmax activation layer, followed by Stacked LSTM model with a hidden LSTM with 128 units and a softmax activation layer. 
- After seting seed of the 60 charecters we go on to predict 400 charecters
- We then track the loss function at every epoch and finally compare the loss function of both the LSTMs


#  Requirements
To run the code, you need to install the following libraries:
- matplotlib
- Keras.layers
-keras.optimizers 
- keras.model

# Algorithm 
-Single LSTM model 
- Stacked LSTM model

# Procedure
You can install them using pip or conda commands.
To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and view the text and explore the data 
3. Define the layers of the LSTM model 
4. Building and fitting the model with keras package.
5. Predicting the tect on a charecter level
6. Evaluating and visualize the model performance using metrics and plots.

The code is commented and documented for better understanding and readability.