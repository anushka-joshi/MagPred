
<h1 align="center">MagPred</h1>

<p align="center" style="font-size: 15px;">by</p>

<h4 align="center" style="font-size: 5px; font-weight: bolder;">Anushka Joshi, Ph.D.</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">Indian Institute of Technology, Roorkee</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">March 2024</h4>

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
3. The file named as 'Test_Dataset' is given as input file for prediction of magnitude. The Table represents the name of the input features used in the MagPred model to predict magnitude and their terminilogy given in manuscript.

<!-- markdown -->
<table style="height:200px">
  <thead>
    <tr>
      <th>Table feature</th>
      <th>Significance</th>
      <th>Table feature</th>
      <th>Significance</th>
      <th>Table feature</th>
      <th>Significance</th>
      <th>Table feature</th>
      <th>Significance</th>
      <th>Table feature</th>
      <th>Significance</th>
      <th>Table feature</th>
      <th>Significance</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Vs30 Actual</td>
      <td>$V_{S30}$</td>
      <td>TAU_P</td>
      <td>$\tau_p$</td>
      <td>TAU_C</td>
      <td>$\tau_c$</td>
      <td>PGV UD</td>
      <td>$P_{GV}$</td>
      <td>PGD UD</td>
      <td>$P_{GD}$</td>
      <td>Magnitude</td>
      <td>$M_{JMA}$</td>
    </tr>
    <tr>
      <td>Hypocenter Distance</td>
      <td>$h_y$</td>
      <td>pgv/pgd</td>
      <td>$T_{va}$</td>
      <td>ACF ACC 1 UD NEG</td>
      <td>${ACF_1}$</td>
      <td>ACF ACC 2 UD POS</td>
      <td>$ACF_4$</td>
      <td>ACF VEL 2 UD POS</td>
      <td>$ACF_5$</td>
      <td>ACF VEL 2 UD NEG</td>
      <td>$ACF_7$</td>
    </tr>
    <tr>        
      <td>ACF DISP 1 UD POS</td>
      <td>$ACF_9$</td>
      <td>ACF DISP 1 UD NEG</td>
      <td>${ACF_3}$</td>
      <td>ACF DISP 2 UD POS</td>
      <td>$ACF_7$</td>
      <td>ACF DISP 2 UD NEG</td>
      <td>$ACF_7$</td>
      <td>0 cross 1 ACC</td>
      <td>${Z_{a1}}$</td>
      <td>0 cross 1 VEL</td>
      <td>${Z_{v1}}$</td>
    </tr>
    <tr>
      <td>0 cross 1 DISP</td>
      <td>${Z_{d1}}$</td>
      <td>0 cross 2 ACC</td>
      <td>${Z_{a2}}$</td>
      <td>0 cross 2 DISP</td>
      <td>${Z_{d2}}$</td>
      <td>ACF RATIO ACC</td>
      <td>${R_{a1}}$</td>
      <td>ACF RATIO DISP</td>
      <td>${R_{d1}}$</td>
      <td>VEL_ACF_1</td>
      <td>${A_{1}}$</td>
    </tr>
    <tr>
      <td>VEL_ACF_2</td>
      <td>${A_{2}}$</td>
      <td>VEL_ACF_3</td>
      <td>${A_{3}}$</td>
      <td>VEL_ACF_5</td>
      <td>${A_{4}}$</td>
      <td>VEL_ACF_6</td>
      <td>${A_{5}}$</td>
      <td>VEL_ACF_7</td>
      <td>${A_{6}}$</td>
      <td>RSSC VELOCITY</td>
      <td>$RSSC$</td>
    </tr>
    <tr>
      <td>CA VELOCITY</td>
      <td>$cv_{av}$</td>
      <td>IV^2</td>
      <td>$IV2$</td>
      <td>ID^2</td>
      <td>$ID2$</td>
      <td>T_VA</td>
      <td>$T_{va}$</td>
      <td>PI_v</td>
      <td>$PI_V$</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>


# Author

**Anushka Joshi (corresponding author)**

- Email: anushka_j@cs.iitr.ac.in
- LinkedIn: https://www.linkedin.com/in/anushka-joshi-iitr/
- Website: https://anushkajoshi.wixsite.com/anushka-joshi
- Contact address: Machine Vision and Intelligence Labs, IIT Roorkee, 
  Department of Computer Science and Engineering, IIT Roorkee, 
  Uttarakhand, India, 247667; 

**Contributors**

- Prof. Balasubramanian Raman
- Prof. C Krishna Mohan

## Acknowledgments

The author thanks the PMRF funding agency for supporting the research.
