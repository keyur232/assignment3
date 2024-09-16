# assignment3

Task 1

Creating a Python function called staff_ info. Using Python input methods to collect information about a staff member submitting a requisition i.e., Date, Staff ID, Staff Name, and requisition ID). A unique ID should be generated using a counter plus 10000 and assigned as the requisition ID, as shown in the code. This function must be returning all inputs and the unique requisition ID. 

Task 2

Creating a Python function called requisitions_ total. Calling the function staff_ info from Task 1 and then ask the staff to input his requisition items (i.e., each item name with a price). This function must be returning the computed total value for all the requisition items. 

Taks 3

This function is built on Tasks 1 and 2. Write a Python function called requisition approval. This function is intended to make approval decisions based on the conditions provided in the 'Responding to requests' section below. 
This function should use the function requisitions total (from Task 2) as input. 

Responding to requests: 

The default status of all submitted requisitions should be set as "Pending". Once a requisition is approved, the status should change to "Approved". If the Total of a submitted requisition is less than $500, the system should automatically approve the requisition and assign an approval reference number based on the following rule. Staff ID followed by the last three characters of the Requisition ID. If the Total of a submitted requisition is $500 or higher, the program should automatically set the status to "Pending". 


Task 4: 

Create a Python function called display_requisitons. The function should display the staff's basic information and the total of his requisition.
