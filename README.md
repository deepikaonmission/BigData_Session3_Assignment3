# BigData_Session3_Assignment3
<<<<<<<<<<<<---------- Problem Statement ----------->>>>>>>>>>>>

We have a dataset of sales of different TV sets across different locations.
Records look like:

Samsung|Optima|14|Madhya Pradesh|132401|14200

The fields are arranged like:

Company Name|Product Name|Size in inches|State|Pin Code|Price

There are some invalid records which contain 'NA' in either Company Name or Product Name.

Associated Data File : television.txt
<<<<<<<<--------- Task 2 --------->>>>>>>

2. Write a Map Reduce program to calculate the total units sold for each  Company

<<<<<<<<--------- Solution for Task 2 --------->>>>>>>>

(i) Three .java files are created:
-> Driver Class: 'MRTask2.java' which controls configuration/properties/attributes of Mapper and Reducer
-> Mapper Class: 'MRMapperTask2.java', which does map processing on input data and generates expected output
-> Reducer Class: 'MRRedcuerTask2.java', which takes input from Mapper, and produces final output

(ii) Task2Screenshots 1-8 describe how map and reduce processings take place

<<<<<<<<--------- Task 3 --------->>>>>>>

3. Write a Map Reduce program to calculate the total units sold in each state for Onida company.

<<<<<<<<--------- Solution for Task 3 --------->>>>>>>>

(i) Three .java files are created:
-> Driver Class: 'MRTask3.java' which controls configuration/properties/attributes of Mapper and Reducer
-> Mapper Class: 'MRMapperTask3.java', which does map processing on input data and generates expected output
-> Reducer Class: 'MRRedcuerTask3.java', which takes input from Mapper, and produces final output

(ii) Task3Screenshots 1-5 describe how map and reduce processings take place
 
