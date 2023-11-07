# EX 9: Simulating Classification using WEKA Data mining and Analysis Tool
## Date: 
## AIM:
To perform a classification technique using WEKA tool
## WEKA:
<div align="justify">
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements.
WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

   ![image](/exp9_DBMS-1.jpg)
   
## CLASSIFICATION:
<div align="justify">
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.<br>
  
## PROCEDURE
1. Load the data file into the WEKA explorer. The data can be loaded from the following sources −
   Local file system
   Web
   Database
2. Click on the "Open file" button. A directory navigator window opens as shown in the following screen − <br>
   ![image](/exp9_DBMS-2.png)
3. Click on the Classify tab, and you would see the following screen <br>
   ![image](/exp9_DBMS-3.png)
4. Now, keep the default play option for the output class −<br>
   ![image](/exp9_DBMS-4.png)
5. Click on the Choose button and select the following classifier − weka→classifiers>trees>J48. <br>
   ![image](/exp9_DBMS-5.png)
6. Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here −<br>
   ![image](/exp9_DBMS-6.png)
7. To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here −<br>
   ![image](/exp9_DBMS-7.png)
8. Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below −<br>
   ![image](/exp9_DBMS-8.png)
9. Selecting Visualize classifier errors would plot the results of classification as shown here −<br>
   ![image](/exp9_DBMS-9.png)
10. A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.<br>

## RESULT:
Thus the simulation of classification technique has been executed using WEKA tool successfully.








