# API Websites Analysis (STA 141B - Final Project)
### Group member:  Shih-Chi Chen (#917995392)

This project is aim to analyze if there exist some characteristics for a popular API website and also analyze these websites' domain type and status code.

Explore Questions:
 1. What category of API is popular?
 2. What kind of status code has high frequency in the dataset? 
 3. For those API websites that have status code = 200, what is the most frequent occurrences domain type ?
 4. What is the failure ratio by Category and by domain type?


### API Base URL :
https://api.publicapis.org/

### Project location :
The project can be found on **notebooks** file.

### Data location: 
The data can be found on **data** file.

### Data information: 
Data name: df_onenormal
<br>Columns: API, Description, Auth, HTTPS, Cors, Link, Category<br>
1.	API : API website names.
2.	Description : a brief description of an API website.
3.	Auth : the authentication type for API websites. There are three categories, APIkey, OAuth and unknown.
4.	Https : boolean values, support HTTPS or not.
5.	Cors: CORS support for entry ("yes", "no", or "unknown")
6.  Link: link of the API website.
7.	Category: category of API websites.

### Code location: 
The code can be found on **code** file.
