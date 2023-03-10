<h1>Machine-learning-classifier-model-to-predict-the-covid-19-disease-in-patients</h1>
<h2>Objective</h2>
<p>The goal of this project is to deploy a machine learning classifier model using deep neural network to predict the covid-19 disease in patients. The deep neural network model built in Matlab is exported as a simulink model. The trained model is then tested for various inputs in MATLAB live script. This project can be used by the healthcare professional to detect covid-19 in patients and to understand various symptoms that contribute to the disease.</p>

   
<h2>Data collection</h2>
As the WHO has declared the Coronavirus pandemic as a health emergency, researchers have been provided open access to data related to the epidemic. The dataset was collected from kaggle.com and it has 5434 × 21 rows of columns. This dataset contains 20 input variables which are the symptoms in the prediction of covid-19, as well as one target class attribute that defines if covid-19 is found or not.
<p align="center">
  <img  src="https://user-images.githubusercontent.com/109975786/209524605-734023f7-3c2f-486e-8af5-e88a7fcda9ee.JPG" width="300" height="350"></p>
<p align="center">Fig 1: Symptoms and various factors considered for model input</p>
</p>

<h2>Trained Neural Network Model In MATLAB</h2>
The trained neural network model in MATLAB  is shown below.
<p align="center"><img  src="https://user-images.githubusercontent.com/109975786/209524725-f38fb066-6f21-4be8-bda2-54e523cf7a64.png" ></p>
  <p align="center">Fig 2: Trained neural network model in MATLAB</p>

  
 <h2>Plots of the Trained neural network model</h2> 
 <p align="center">
  
  <img  src="https://user-images.githubusercontent.com/109975786/209524851-4913fb78-c0d7-4ed4-a7af-0c95b715a750.png" width="400" height="250">
  
<p align="center">Fig 3: Performance of the Trained neural network model </p>
  </p>
  
   <p align="center">
  <img  src="https://user-images.githubusercontent.com/109975786/209524964-2eb9f74f-2004-48b4-88d1-3eeac654d55f.png" width="400" height="300">
  
<p align="center">Fig 4: Confusion matrices of the Trained neural network model</p> 
  </p>
   <p align="center">
  <img  src="https://user-images.githubusercontent.com/109975786/209525058-8d4ae561-dac1-42a6-9340-574c1086c191.png" width="300" height="300">
  
  
<p align="center">Fig 5: ROC of the Trained neural network model </p>
  </p>
 <h2>Results</h2>
<p align="center">
  <img  src="https://user-images.githubusercontent.com/109975786/209525994-0d59cb5f-df50-4ab4-8383-97ed7845dacf.png" width="500" height="450">
  
<p align="center">Fig 6: Trained neural network model classifies the patient as covid positive</p>
  </p>
  <p align="center">
  <img  src="https://user-images.githubusercontent.com/109975786/209526130-54da2fa3-7f82-4948-ad59-9e0f7e2e027d.png" width="500" height="450">
  
<p align="center">Fig 7: Trained neural network model classifies the patient as covid negative</p>
  </p>
  <h2>Conclusion</h2>
AI and deep learning play an essential role in COVID-19 cases identification and classification using computer-aided applications, which achieves excellentand accurate results for identifying COVID-19 cases based on known symptoms.
