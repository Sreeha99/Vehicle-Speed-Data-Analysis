# Vehicle-Speed-Data-Analysis
VEHICLE SPEED DATA ANALYSIS
This project aims to analyze the vehicle speed data and find the relationship between the attributes and further analysis on best and worst driver is found.

TOOL USED:  Jupyter Notebook

DATA SET DESCRIPTION:

•	Dataset consists of 11 columns and 343628 rows.
•	Dataset Link: https://drive.google.com/a/everlytics.io/file/d/0B9Qz13i9d7XJOWNLLXNrTDFPT2M/view?usp=sharing

ANALYSIS DONE:

1.	Firstly, I have imported the required packages for the analysis

	Numpy  -  mathematical and logical operation

	Pandas  -  importing and analysing

	Matplotlib.plot  -   plotting

	Seaborn  -  Statistical Visualization

2.	After importing the packages , I have used the describe function to find the basic statistical details like percentile, mean, standard deviation.
3.	Next, I have found the correlation testing for the attributes to check the strength of relationship between the attributes.
4.	Skewness testing for the data is done to find the asymmetric statistical distribution.
5.	Pairplot of the data is done to visualize the pair wise relationship of the attributes.
6.	Data is to be normalized to reduce the redundancy of the data. Norm() function is used and it is converted into a data frame for convenient further analysis
7.	To find the worst and the best drivers, Speed limit of the driver condition is used.

	First drivers who have not violated the speed is found separately for both normal and highway roads.

	Next drivers who have violated the speed is found separately for both normal and highway roads.

	Box plot is used to visualize the outliers in the speed attribute.

8.	Count of the drivers who have violated and non violated is found as further analysis of the best and worst driver. Bar Graph is drawn for visual representation of the count of both violated and non violated drivers.
9.	Driver Id with the same number of violations are grouped to find the violation count.
10.	Maximum speed in a highway and non highway is also found.
11.	Count of the functional Class is also found and put in a count plot.
 

