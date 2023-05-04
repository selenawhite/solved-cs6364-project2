Download Link: https://assignmentchef.com/product/solved-cs6364-project2
<br>
1 <strong>Linear</strong> <strong>Regression</strong>

In this exercise, you will implement a linear regression model to predict the house price. For this exercises use the dataset from the link below. Only use a single feature for you regression model and explain your reasons for selecting that feature. Please explain the data setting and experimental setup similar to Project 1.

The key components of your linear regression model are the cost function and gradient decent method to update the weights.

<ol>

 <li>https://www.kaggle.com/mayanksrivastava/predict-housing-prices-simple-linear-regression/ data</li>

</ol>

<h1>2 Decision Trees</h1>

<strong>2.1</strong> <strong>ID3</strong>

Consider the following set of training examples for the unknown target function <em>&lt;</em> <em>X</em><sub>1</sub><em>,</em> <em>X</em><sub>2</sub> <em>&gt;</em>→ <em>Y</em> .

<table width="144">

 <tbody>

  <tr>

   <td width="35"><em>Y</em></td>

   <td width="33"><em>X</em><sub>1</sub></td>

   <td width="25"><em>X</em><sub>2</sub></td>

   <td width="52">Count</td>

  </tr>

  <tr>

   <td width="35">+</td>

   <td width="33">T</td>

   <td width="25">T</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">+</td>

   <td width="33">T</td>

   <td width="25">F</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">+</td>

   <td width="33">F</td>

   <td width="25">T</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">+</td>

   <td width="33">F</td>

   <td width="25">F</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">–</td>

   <td width="33">T</td>

   <td width="25">T</td>

   <td width="52"></td>

  </tr>

  <tr>

   <td width="35">–</td>

   <td width="33">T</td>

   <td width="25">F</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">–</td>

   <td width="33">F</td>

   <td width="25">T</td>

   <td width="52"> </td>

  </tr>

  <tr>

   <td width="35">–</td>

   <td width="33">F</td>

   <td width="25">F</td>

   <td width="52"> </td>

  </tr>

 </tbody>

</table>

<ol>

 <li>What is the sample entropy <em>H</em>(<em>Y </em>) for this training data (with logarithms base 2)?</li>

 <li>What are the information gains <em>IG</em>(<em>X</em><sub>1</sub>) ≡ <em>H</em>(<em>Y </em>)−<em>H</em>(<em>Y </em>|<em>X</em><sub>1</sub>) and <em>IG</em>(<em>X</em><sub>2</sub>) ≡ <em>H</em>(<em>Y </em>)−<em>H</em>(<em>Y </em>|<em>X</em><sub>2</sub>) for this sample of training data?</li>

 <li>Draw the decision tree that would be learned by ID3 (without postpruning) from this sample of trainingdata.</li>

</ol>

<strong>3</strong> <strong>Perceptron</strong>

Please use the notebook provided for you to complete the perceptron exercise.

<h1>4 Support Vector Machine</h1>

In this problem, you will repeat the format of Project 1 but using an SVM. On the Breast Cancer Wisconsin (Diagnostic) Data Set. See associated link.