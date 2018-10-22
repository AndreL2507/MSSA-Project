# Andre Lacquement
## Project Use Cases
---
### Use Case 1

---
    
* Name: Create Account

* Actors: Business Owner/Product seller

* Precondition: Business Owner exists, application exists

* Triggers: User wants to create invoices for clients using a mobile application

Good Flow: 
* User downloads application
* User enters valid login data
* User has created an account

Alternate Flow: 
* User enters a username that is already taken
* User enters an invalid password
* User makes a typo 
--- 
### Use Case 2

---

* Name: Edit Account Info

* Actors: Application users/ database

* Precondition: User wants to edit/ update account info

* Triggers: User realizes they entered information incorrectly.
User wants to update info. 

Good Flow: 
* User goes to the edit account tab on the application home page
* User makes necessary changes 
* Changes are noted and updated in the database

Alternate Flow: 
* User enters an invalid email address 
* User enters an invalid territory in the United States
* Data is not updated on the database

---
### Use Case 3

--- 

* Name: Create Invoice

* Actors: User / Customer / Database

* Preconditions: User has application

* Triggers: Owner sells to Customer and needs to create an invoice

Good Flow: 
* User enters all data into the application and an invoice is created
* Invoice data is stored in the database
* User sends Customer the invoice for review and signatures

Alternate Flow: 
* User is missing data from the customer
* Invoice data is not saved in the database
* User is unable to access data for the product he is selling

        


