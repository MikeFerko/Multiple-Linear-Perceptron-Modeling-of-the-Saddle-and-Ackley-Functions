<!DOCTYPE html>
<html>
<!-- MLP Section -->
<body>
  <div>
  
   Regression with Multiple Linear Perceptron (MLP) Modeling of the Saddle and Ackley Functions
   <li>MLP Machine Learning Algorithm:</li>
    <ol type="1">
      <li>Generate a data set with the simple Saddle Point or the Ackley Function</li>
        <ul>
          <li>Saddle Point:</li>
          <img src="https://latex.codecogs.com/gif.latex?z%28x%2Cy%29%20%3D%20x%5E%7B2%7D%20&plus;%20y%5E%7B2%7D"></img>
          <li>Ackley:</li>
          <img src="https://latex.codecogs.com/gif.latex?z%28x%2Cy%29%20%3D%20-20e%5E%7B%5Cfrac%7B1%7D%7B5%7D%20%5Csqrt%7B%5Cfrac%7B1%7D%7B2%7D%20%28x%5E%7B2%7D%20&plus;%20y%5E%7B2%7D%29%7D%7D%20-%20e%5E%7B%5Cfrac%7B1%7D%7B2%7D%28cos%7B%28%5Cpi%20x%7D%29%20&plus;cos%7B%28%5Cpi%20y%7D%29%29%7D"></img>
        </ul>
      <li>Add uniform random noise and visualize the 3D meshgrid</li>
      <li>Reshape the generated data to be a tensor input vector (shape will be: sample rows by feature columns)</li>
      <li>Regression MLP Model Parameters:</li>
      <ul>
        <li><a href="https://en.wikipedia.org/wiki/Stochastic_gradient_descent">Stochastic Gradient Descent optimizer</a></li>
        <ul>
          <li>Learing Rate = 0.1</li>
          <li>Exponential Decay Factor = 0</li>
          <li>Momentum = 0.1</li>
          <li>Train Duration: 50 Epochs</li>
          <li>Batch Size = 10</li>
         </ul>
        <li><a href="https://en.wikipedia.org/wiki/Mean_squared_error">Mean Square Error Loss Function</a></li>
      </ul>
      <li>Create a predicted Saddle point and Ackley Function from the Regression MLP trained Neural Network</li>
      <li>Plot the Results</li>
    </ol>
    <p align="center">
      <a href="https://drive.google.com/file/d/17p5fgVgv836Nup1Jq5vYwrFuBrS3THVM/view?usp=sharing">
      <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/MLPModel.png" width="50%" height="50%">
      </a>
      <br>Multiple Linear Perceptron (MLP) Model</br>
    </p>
    <p align="center">
      <a href="https://drive.google.com/file/d/17p5fgVgv836Nup1Jq5vYwrFuBrS3THVM/view?usp=sharing">
      <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/SaddlePointPredictions.png" width="75%" height="75%">
      </a>
      <br> Results of Saddle Function Predictions </br>
      <ol>
        <br>Results are shown in the above image Left-to-Right, Top-to-Bottom</br>
        <li>Real vs. Predicted Saddle</li>
        <li>z-x cross section @ y = 2</li>
        <li>z-x cross section @ y = 0</li>
        <li>Model Loss Vs. Epochs</li>
        <li>Topological Heat Map</li>
      </ol>
    </p>
    <p align="center">
      <a href="https://drive.google.com/file/d/17p5fgVgv836Nup1Jq5vYwrFuBrS3THVM/view?usp=sharing">
      <img src="https://github.com/MikeFerko/MikeFerko/blob/main/images/AckleyPredictions.png" width="75%" height="75%">
      </a>
      <br> Results of Ackley Function Predictions </br>
      <ol>
        <br>Results are shown in the above image Left-to-Right, Top-to-Bottom</br>
        <li>Real vs. Predicted Ackley</li>
        <li>z-x cross section @ y = 2</li>
        <li>z-x cross section @ y = 0</li>
        <li>Model Loss Vs. Epochs</li>
        <li>Topological Heat Map</li>
      </ol>
    </p>

  </div>
