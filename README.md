<h2>"Corn Yield Forecasting: A Supervised Learning Model for Sustainable Farming"</h2>
<h3>Introduction</h3>
<p> This project develops a Simple linear Regression model using supervised learning dataset to predict corn yield using inputs like land area, seed quantity, and fertilizer. It aims to deliver accurate yield forecasts, helping farmers optimize resource use and adopt sustainable farming practices. The insights gained will support informed decision-making, boosting both efficiency and productivity in corn production.
</p>
<h3>Motivation</h3>
<p>Imagine a farmer who owns a large corn farm. He's looking to develop a system to help him predict his corn yield based on various input factors. Specifically, he wants the system to analyze data such as the size of the land, the quantity of seeds planted, and the amount of fertilizer applied. By leveraging this data, the farmer hopes to build a predictive model that will estimate the corn yield for each season. Additionally, he aims for the system to provide guidance on the optimal amounts of land, seed, and fertilizer required to achieve the desired yield, helping him manage resources efficiently. </p>
<h3>Objectives</h3>
1. Predict Corn Yield: Use fertilizer input data to predict corn yield, enabling better resource planning. <br>       
2. Optimize Resource Allocation:Provide insights into fertilizer requirements to achieve target yields, minimizing waste and supporting sustainability.
<h3>Data and Methodology</h3>
The dataset includes two key variables:
1. Fertilizer Used: Amount of fertilizer applied.<br>
2. Corn Yield:Yield produced in response to fertilizer application.<br><br>

<br><br>


![Screenshot 2024-10-23 162753](https://github.com/user-attachments/assets/21618365-5d04-4761-8b4e-861b4a0260bc)



<br><br>

![Screenshot 2024-10-23 163131](https://github.com/user-attachments/assets/5492fc28-798b-4fcf-98bd-6ac6c56d22eb)


<br><br>

<h3>A simple linear regression model was selected due to the clear linear relationship expected between fertilizer use and yield. The dataset is split into training and testing sets, with 80% of the data used for training and 20% for testing. The model's performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R²) to gauge accuracy.</h3><br><br>

<h3>Result</h3>
The resulting model achieved:

1. Mean Squared Error (MSE): 5100.41, reflecting the average squared difference between actual and predicted values.<br><br>
2. R-squared (R²): 0.86, indicating that 86% of the variance in corn yield can be explained by the fertilizer input.<br>
The model's prediction equation:
Corn Yield=5.72×(Fertilizer Used)−101.26 <br>
This equation can be used to predict future yields based on fertilizer amounts, allowing farmers to estimate expected outcomes more accurately.<br><br>
<br><br>


![Screenshot 2024-11-05 234927](https://github.com/user-attachments/assets/5d1d25dc-3a00-4968-85ed-8e3637d674fd)

<br><br>
<h3>Conclusion</h3>
This project demonstrates how a supervised learning model can aid agricultural decision-making by forecasting crop yields based on key inputs. The insights gained from this model empower farmers to allocate resources more effectively, supporting both increased productivity and sustainable farming practices.
