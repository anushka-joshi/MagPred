
<h1 align="center">MagPred</h1>

<p align="center" style="font-size: 15px;">by</p>

<h4 align="center" style="font-size: 5px; font-weight: bolder;">Anushka Joshi, Ph.D.</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">Indian Institute of Technology, Roorkee</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">March 2023</h4>

## Description

An earthquake Magnitude predictor model is developed that utlizes the synthetic dataset generated using conditional tabular generative adversarial networks and ensemble of various models to predict the magnitude.

### Executing program

The program can be executed in the Google Colaboratory, Jupyter notebook or any other platform that runs python code.

## Result
The result file named as 'MagPred_Result.csv' is generated after execution of the code. The file consists of the predictions from all the selected individual machine learning model and the MagPred model.

## Help

The following advices are suggested while executing the program:
1. The file location should be changed accordingly. The authors have used their respective file location.
2. The tasks performed by the following functions are described below:
```python
# Python function
def read_Syn():
```
Is used to read the test dataset provided in it. It returns the X_test and y_test array that consists of input features and actual output prediction.
```python
# Python function
def Testing_on_Dataset()
```
Is the function that predicts the magnitude of an earthquake using the MagPred model.

# Author

**Anushka Joshi (corresponding author)**

- Email: anushka_j@cs.iitr.ac.in
- LinkedIn: https://www.linkedin.com/in/anushka-joshi-iitr/
- Website: https://www.anushijoshi.com/
- Contact address: Machine Vision and Intelligence Labs, IIT Roorkee, 
  Department of Computer Science and Engineering, IIT Roorkee, 
  Uttarakhand, India, 247667; 

**Contributors**

- Prof. Balasubramanian Raman
- Prof. C Krishna Mohan

## Acknowledgments

The author thanks the PMRF funding agency for supporting the research.
