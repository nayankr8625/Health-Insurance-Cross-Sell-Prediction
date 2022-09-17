<p align="center"> 
  <img src="https://www.leadsquared.com/wp-content/uploads/2021/11/comprehensive-guide-to-cross-selling-policies.png" >
  <h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>
</p>
<p align="center"> 
  <img src="https://media.giphy.com/media/YqKPof1xLJaiCtpA6G/giphy.gif"  width="150px" height="150px">
</p>
<h1 align="center"> Health Insurance Cross Sell Prediction </h1>
<p>Developed various models to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.</p>

<h2> :floppy_disk: Data Description</h2>

In order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

**id** : Unique ID for the customer

**Gender** : Gender of the customer

**Age** : Age of the customer

**Driving_License** 0 : Customer does not have DL, 1 : Customer already has DL

**Region_Code** : Unique code for the region of the customer

**Previously_Insured** : 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

**Vehicle_Age** : Age of the Vehicle

**Vehicle_Damage** :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

**Annual_Premium** : The amount customer needs to pay as premium in the year

**PolicySalesChannel** : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

**Vintage** : Number of Days, Customer has been associated with the company

**Response** : 1 : Customer is interested, 0 : Customer is not interested

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable files, 3 text files as well as 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>Health_Insurance_Cross_Sell_Prediction.ipynb</b> - Includes all functions required for classification operations.</li>
  <li><b>Project presentation.docx</b> - Contains all the analysis which is presented after completing the analysis.</li>
  <li><b>Project report.pdf</b> - Contains whole analysis strategy and analysis methodology followed for the project.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>TRAIN-HEALTH 
INSURANCE CROSS SELL PREDICTION.csv</b> - Includes all the required data for the classification task.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: KNN (K-Nearest Neighbour) </h2>
<p>
The k-nearest neighbours algorithm, sometimes referred to as KNN or k-NN, is a supervised learning classifier that employs proximity to produce classifications or predictions about the grouping of a single data point.
</p>
<p>New data point and we need to put it in the required category. Consider the below image:
<img src="https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning3.png" alt="Formula 2" style="max-width:100%;"></p>

<p>Next, we will calculate the Euclidean distance between the data points. The Euclidean distance is the distance between two points, which we have already studied in geometry. It can be calculated as:

</p>
<img src="https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning4.png" alt="Formula 3" style="max-width:100%;"></p>

<img src="https://static.javatpoint.com/tutorial/machine-learning/images/k-nearest-neighbor-algorithm-for-machine-learning2.png" alt="Formula 3" style="max-width:100%;"></p>

#### As we can see the 3 nearest neighbors are from category A, hence this new data point must belong to category A. 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Execution Instruction</h2>
<p>The order of execution of the program files is as follows:</p>
<p><b>1) Health_Insurance_Cross_Sell_Prediction.ipynb</b></p>
<p>The Health_Insurance_Cross_Sell_Prediction.ipynb is to be executed to access all the analysis done for classification operations.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Conclusions -->
<h2 id="conclusions"> :scroll: Conclusions</h2>

<p><b>1) Classification algorithm models have been developed to improve the efficiency of insurance companies, as they can determine which customers to target and how to increase sales by predicting the label class, which helped increase retention.</b></p>
<p><b>2) Used SMOTE, Feature Importance, Classification algorithms like KNN, Random Forest techniques to resolve the issue.</b></p>
<p><b>3) A number of feature transformations were performed, including Labelencoding, Upsampling, and Correlation analysis, to improve the data.</b></p>
<p><b>4) Iterated with different models where KNN with 96% recall rate and 83% accuracy is the champion model and contender model being Decision Tree.</b></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Future Work -->
<h2 id="Future Work"> :scroll: Future work</h2>

-     Insurance Comapnies should promot and provide more customer friendly insuarance.
-     Benefits for clients with vehicles older than two years.
-     For analysis there should be more parameters for the analysis more some more features will help the analysis to be more explainatory.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Nayan Kumar | Data Scientist | Machine Learning Engineer | Deep Learning Engineer

<p> <i> Contact me for Data Science Project Collaborations and Data Science related job roles</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayan8625/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nayankr8625)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>javatpoint has helped to understand more about KNN</p>
      <p>Available: https://www.javatpoint.com/k-nearest-neighbor-algorithm-for-machine-learning</p>
  </li>
  <li><p>nemesisbyaviana helped to understand the prpblem more effciently and easily.</p>
      <p>Available: https://nemesisbyaviana.com/solutions/insurance-cross-sell-prediction/</p>
  </li>
  <li><p>Youtube.com, 'Health Insurance Cross Sell Prediction'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=CJSuG_S9cXo</p>
  </li>
  <li><p>Youtube.com, 'Binary Classification'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=zM4VZR0px8E</p>
  </li>
  <li><p>Manisha-sirsat.blogspot.com, 'What is Confusion Matrix and Advanced Classification Metrics?'. [Online].</p>
      <p>Available: https://manisha-sirsat.blogspot.com/2019/04/confusion-matrix.html</p>
  </li>
  <li><p>lexisnexis.com, 'Blog on cross sell insurance'. [Online].</p>
      <p>Available: https://risk.lexisnexis.com/insights-resources/case-study/maximize-property-to-auto-cross-sell-campaign-performance</p>
  </li>
</ul>

# **Thank you so much for visiting :smile:**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
