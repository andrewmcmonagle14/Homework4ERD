# Homework4ERD
MIS 375 Database Design for Business Application: Homework #4

Part I

Use diagrams.net or Microsoft Visio to draw an EER diagram for each of the following situations. If you need to make additional assumptions, clearly state them for each situation. 

1.	Nodak Bank & Trust has three types of accounts: checkings, savings, and loan. Following are the attributes for each type of account:

CHECKING: Acct Number, Date Opened, Balance, Service Charge
SAVINGS: Acct Number, Date Opened, Balance, Interest Rate
LOAN: Acct Number, Date Opened, Balance, Interest Rate, Payment
	
Assume that each bank account must be a member of exactly one of the three subtypes. Using the generalization approach, develop an EER model to represent this situation. Remember to include a subtype discriminator.

2.	Two-Bit Drilling Company keeps information on employees and their insurance dependents.  Each employee has an employee number, name, date of hire, and title. An employee may have multiple dependents or may not have any dependent. All dependents must be associated with one and only one employee.  Each dependent is identified by a unique dependent number. Their names are also kept in the database. If an employee is an inspector, then the date of certification and the renewal date for that certification should also be recorded in the system.  

3.	A technology company provides two separate types of offerings to its customers: products and services. Offerings are identified by an offering ID and has an attribute of description. In addition, products are described by product name and standard price. Services are described by responsible unit and conditions of service. The company offers different types of distinct services (e.g., repair, maintenance, etc.). A repair service has  cost and estimated time; a maintenance service has hourly rate.


 
Part II

Convert each of the following conceptual schemas into a relational schema. List all the tables and attributes. Clearly specify primary keys and foreign key references. 

Note: Please use proper notation when listing tables in your relational schema. For example:
Instructor (InstructorID, Lname, Fname, Office)
	Primary key: InstructorID
Course (CourseID, Title, Credits, InstructorID)
	Primary key: CourseID
	Foreign key: InstructorID references Instructor(InstructorID)
  
  1. 
![image](https://github.com/andrewmcmonagle14/Homework4ERD/assets/62773209/7cc58560-b641-4dfc-a7ce-2aee3acfc7f6)

2.
![image](https://github.com/andrewmcmonagle14/Homework4ERD/assets/62773209/62b1269b-b270-493a-9839-cc3780f9a786)
