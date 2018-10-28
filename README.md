# OOPS

Some sample OOPs concept will be seen by solving some problems by OOPs concept

1. Design a class called Student with the following details about the student:
a. Name
b. Age
c. Roll Number - unique
d. Branch
e. Latest Roll No
So, this class with have overloaded constructors -
A. Default constructor
B. Constructors with all fields as parameters 

 There will be setter and getter methods for the fields of the class. 
 Define a toString method that prints all the fields in Student class.
 ‘Latest Roll No’ field of the class will be static containing latest roll number. A new
student when added gets his or her roll number after incrementing this status
counter. 
 Initialize the students’ information by storing information about 10 students. That is,
create an array of type Student of size 10 and then instantiate each element.
 Print the information about students’ by just calling object.toString(). 


2. Design a class called Account - which stores the following details about the
a. Customer Name
b. Address
c. Balance
d. Account
e. Count
This class will have appropriate constructors.
Each object of the Account class represents an account which has unique account number.
‘Count’ field of the class will be static and it increments whenever we we create a new
account. 

Define a toString method that prints all the fields in Account class. Print the information
about accounts’ by just calling object.toString().
This class supports debit and credit facilities for the customer’s account.
Debit will have following features -
A. Reports Error if account balance is not sufficient
B. Attract penalty of Rs. 5 in two cases -
a. Account balance is less than or equal to Rs. 500
b. If after deducting the amount of debit from the account balance, account balance <=
500. 
Initialize the accounts’ status by creating at least 20 accounts with an initial deposit of Rs.
1000. That is, create an array of type Account of size 20 and then instantiate each element.
Write a menu driven program that asks the user his/her account number followed by the
operation to perform on his account. 
