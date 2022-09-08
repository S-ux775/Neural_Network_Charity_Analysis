# Neural_Network_Charity_Analysis

Overview of the loan prediction risk analysis:

This project involves a filantropic organization (Alphabet Soup) that grants loans for projects aimed to the well being of the society. This organization wants to evaluate the risk behing some potential borrowers that may not be worth the time nor the money.

A robust model is proposed that goes beyond traditional ML models: Neural Networks.

The project invovles:
    Preprocessing Data for the Neural Netwokr Model
    Compile, Train and Evaluate the Model
    Optimize the Model

TensorFlow (Python -based) platform will be used.

Results:
Tha Alphabet Soup Charity model is prepared and run.
The base model show an accuracy of 0.72

An optimized script is run and delivered accuracy of 0.78

* Data Preprocessing

- Non beneficial columns are dropped
_ Split training/test datasets

* Compiling, Training, and Evaluating the Model

- 2 hidden layers were used for training initially and a "sigmoid" afterward.
- 80 neurons in the first layer and 30 neurons in the second.
- The model showed 72.45% accuracy.

For the optimized model 3 layers were used with 80, 30 and 10 neurons.
This model reached accuray of over 78.5%

Summary:
With some changes in the model (layers and neurons), the optimized model excedeed the target accuray of 75%.
