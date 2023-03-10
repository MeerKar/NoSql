# NoSql

This project we are evaluting the UK Food Standards Agency' s various establishments across the United Kingdom, and gives them a food hygiene rating. 
For evalutiona of some of the ratings data in order food magazine, Eat Safe, Love is contracted by the editors. This is going to help their journalists and food critics decide where to focus future articles. 


This project is divided into three parts

### Part 1. Database and Jupyter Notebook Set Up

First import the data provided in the json file called establishment.json from the Terminal using 

<img width="473" alt="image" src="https://user-images.githubusercontent.com/116701851/224402853-a218bf3f-c753-4b52-adcb-5b33e9cacab7.png">

Name the Database as uk_food and the collection as establishments.Using find_one and pprint to ensure that the document is imported properly.
The link for the file is https://github.com/MeerKar/NoSql/blob/main/Starter_Code%203/NoSQL_setup_starter.ipynb


#### Part 2. Update the Database

Using the file above The magazine editors have some requested modifications for the database , Performing  different queries and  analysis for them, the following changes have done to the establishments collection:
 
1.  A new data for a new resturant has added and done the anlysis .

2. Found out the BusinessTypeID for the new resturant and updated 

4. First found ou how many documents contained the Dover LOcal Authority 
<img width="455" alt="image" src="https://user-images.githubusercontent.com/116701851/224405453-d56f9498-4859-458e-9338-19db59f113c9.png">

Then, removed any establishments within the Dover Local Authority from the database, and checked the number of documents to ensure they were deleted. 

5.  Some of the number values are stored as strings, when they should be stored as numbers. Use update_many to convert latitude and longitude to decimal numbers.


### Part 3.  Exploratory Analysis

 Inorder to answer specific questions, from Eat Safe, Love   which will help them find the locations they wish to visit and avoid.
 
 Using  the following questions to explore the database, and find the answers,was provided them to the magazine editors.
 
 An analysis file has been imported , the link follows, 
