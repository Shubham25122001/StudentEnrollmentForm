# Student-Enrollment-Form
## Description 

## Micro Project Work

1. Create a form based on any one of the TOPICS given below. The form should store data in the database. The primary key and input fields of each topic is mentioned.

2. There will be three control buttons [Save], [Update] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key in the relation. All other fields and buttons should be disabled at this time.

3. User will enter data in the field having primary key and

  o If the primary key value does NOT exist in the database, enable [Save] and [Reset] buttons and move the cursor to the   next field and allow the user to enter data in the form.

   * Check that the data should be valid i.e. no empty fields.

   * Complete the data entry form and click the [Save] button to store the data in the database and go to step-2.

   o If the primary key value is present in the database, display that data in the form. Enable [Update] and [Reset]           buttons and move the cursor to the next' field in the form. Keep the primary key field disabled and allow users to         change other form fields.

 * Check that the data should be valid i.e. no empty fields.

 * Click on [Update] button to update the data in the database and go to step-2.

 * Click [Reset] to reset the form as per the step-2.


Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database.

Input Fields: {Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date}

Primary key: Roll No.



# Benefits of using JsonPowerDB
* Simple to use , real time database
* Simplest way to retrieve data in a JSON format.
* Backends code is not required for database 
* No need for defining schema 
* Querying the database is easy there is no need  of knowledge of SQL commands

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

# Screenshots:
<img src="https://user-images.githubusercontent.com/101853403/213921807-758a1c8e-a2b5-415d-a1ac-1920825e584d.png">


<img src="https://user-images.githubusercontent.com/101853403/213921927-51d5ef31-3fdb-46a7-8c0b-9953e12ec502.png">


<img src="https://user-images.githubusercontent.com/101853403/213922888-74e53483-ae3b-4df9-ba37-7a3a81117ef0.png">

# Illustrations:
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**

We need to enter a roll number 

If roll number is not valid 

If roll number is valid and that roll number is existnig in database


* **Fetching student data using roll number**
  If student already present in database, then all field filled with that student information
  otherwise, other fields are enabled after user input roll number
  
* **Updation of student details**
  In order to update student details input roll number, and then we can update the student data

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid

  
 * **If input data is not valid**
    
  
  # Installation
  
 ## clone of the repository 
  ```
  git clone https://github.com/Shubham25122001/StudentEnrollmentForm.git
  ```
  After cloning 
  
  Move to **public_html** and then **JS** folder and in **index.js** file replace the **connectionToken** by with your Connection Token
  
  # Sources
  * Introduction to JsonPowerDB - V2.0 course  on https://careers.login2explore.com/
  * [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 
  

  # Demo Video
  https://user-images.githubusercontent.com/101853403/213923166-444ac5de-de0c-46c6-8e1e-37a48f42afda.mp4

  

  --------------------
## 🙏Thank You 🙏 
