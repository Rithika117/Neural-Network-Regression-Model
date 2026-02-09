# Developing a Neural Network Regression Model

## AIM

To develop a neural network regression model for the given dataset.

## THEORY

Explain the problem statement

## Neural Network Model
<img width="1099" height="643" alt="image" src="https://github.com/user-attachments/assets/cb552d51-1eda-4237-b43b-71d8a5d2cd1f" />


## DESIGN STEPS

### STEP 1:

Loading the dataset

### STEP 2:

Split the dataset into training and testing

### STEP 3:

Create MinMaxScalar objects ,fit the model and transform the data.

### STEP 4:

Build the Neural Network Model and compile the model.

### STEP 5:

Train the model with the training data.

### STEP 6:

Plot the performance plot

### STEP 7:

Evaluate the model with the testing data.

## PROGRAM
### Name:Rithika K
### Register Number:212224230230
```python
class NeuralNet(nn.Module):
    def __init__(self):
        super().__init__()
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer



def train_model(ai_brain, X_train, y_train, criterion, optimizer, epochs=2000):
    #Include your code here



```
## Dataset Information
<img width="434" height="455" alt="image" src="https://github.com/user-attachments/assets/43b5ac8f-ad05-40de-a2af-56100224de8a" />

## OUTPUT

### Training Loss Vs Iteration Plot

<img width="741" height="270" alt="image" src="https://github.com/user-attachments/assets/26a9cf82-1ce7-4f5e-ba4a-2ab19df6d422" />


### New Sample Data Prediction


## RESULT
The neural network regression model was successfully trained and evaluated. The model demonstrated strong predictive performance on unseen data, with a low error rate.
Include your result here
