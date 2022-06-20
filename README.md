# **Online-Retail-Customer-Segmentation**
Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately.

## **Problem Statement**
To identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts.

![image](https://user-images.githubusercontent.com/100409195/173539164-2de34e19-ed0c-4bcb-9a10-1c52b4b82b10.png)



## <b> Data Description </b>

### <b>Attribute Information: </b>

* **InvoiceNo:** Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* **StockCode:** Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* **Description:** Product (item) name. Nominal.
* **Quantity:** The quantities of each product (item) per transaction. Numeric.
* **InvoiceDate:** Invice Date and time. Numeric, the day and time when each transaction was generated.
* **UnitPrice:** Unit price. Numeric, Product price per unit in sterling.
* **CustomerID:** Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* **Country:** Country name. Nominal, the name of the country where each customer resides.

## Project Files :

* **Online Retail Customer Segmentation - Capstone Project.ipynb** - This file includes complete implementation of the project such as Features description, exploratory data Analysis, feature engineering, feature scaling and implemented algorithms.
* **Project PPT -** This is a power point presentation file for the project. It includes various visualaized plots of EDA .The result of the algorithms.
* **Project Summary -** A brief summary of the project.
* **Technical Documentation -** This document includes all the basic information and description of different stages of the project.


## <b> Recency-Frequency-Monetary (RFM) model to determine customer value:</b>
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

* Recency => How recent was the customer's last purchase? Number of days between analysis date and last invoice date

* Frequency=> How often did this customer make a purchase in a given period? Number of purchases.

* Monetary => How much money did the customer spend in a given period? In other words , How much money will the company potentially earn from a particular customer?

## <b> Data Pipeline:</b>

* **Understanding Dataset**: In this stage, we went on to some Initial review on the dataset in order to learn get an insight of the dataset.

* **Data Processing**: During this phase, data cleaning was the agenda so we looked for the outliers, duplicate values in the data.
 
* **EDA:** EDA or Exploratory Data Analysis is the critical process of performing the initial investigation on the data. So, through this we have observed certain         trends and dependencies and also drawn certain conclusions from the dataset that will be useful for further processing.

* **RFM Model (Recency, Frequency,Monetary )**: Here, we have transformed our features in terms of  Recency, Frequency, Monetary depending on these factors we segmented our customers.

* **Model Fitting:**  The transformed data is we pass it to different clustering models to get optimum number of segments.

## **Segmentation:**

The data is passed through different stages discussed in data  pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means and Heirarchical clustering algorithms are used  to determine the ideal segments in which the customers  are segmented. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm.

## **Observations and Conclusions:**
* Majority of the data belongs to United Kingdom.
* The Optimum number of clusters obtained were 2 using the K-Means and Heirarchical Clustering.

## **Model Reference:**
* K-Means Clustering: https://www.javatpoint.com/k-means-clustering-algorithm-in-machine-learning
* Hierarchical Clustering: https://www.javatpoint.com/hierarchical-clustering-in-machine-learning
 
 ## **Credit:**
* Parth Sharma | Data Scientist | Machine Learning Enthusiast

## **References:**
https://github.com/tyuion/Customer-Segmentation/blob/master/Arvato%20Project%20Workbook.ipynb

https://www.actioniq.com/blog/what-is-rfm-analysis/


