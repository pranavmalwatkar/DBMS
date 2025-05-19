1)
Create the following tables. Insert the appropriate data in these tables and solve the queries
Client_master (client_no, name, address1, address2, city,pincode,state,bal_due)
Product_master(product_no, description, profit_percent, unit_ measure, qty_on_hand ,
reorder_lvl, sell_price, cost_price)
Salesman_master(salesman_name, address1, address2, city, pincode, state, sal_amt,
tgt_to_get,ytd_sales,remarks)
Sales_order(order_no,order_date,client_no,dely_addr,salesman_no, dely_type,billed_yn,
dely_date, order_status)
Sales_order_details(order_no, product_no,qty_ordered,qty_disp,product_rate)
Constraints are
Client_master( Client_no is PK & first letter must start with ‘C’ , Name Not NULL)
Product_master(product_no is PK & first letter must start with ‘P’)
Salesman_master(salesman_no is PK & first letter must start with ‘S’ Name not NULL)
Sales_Order(order_no is PK & first letter must start with ‘O’,dely_type(Delivery:
part(P)/full(f) Default (F), dely_date cannot be less than order_date, order_status values (‘In
Process’, ‘Fulfilled’ ‘BackOrder’,’Cancelled’).
4)
Based on the below mentioned schema/tables apply the SQL queries
EMP (Empno, Ename, Job, Mgr, Hiredate, Sal, Comm, Dept no)
DEPT (Deptno,Dname,Loc)
a) Add a record to the department table with values (50,’PERSONNEL’,’BOSTON’).
b) If a new person HERALD joins the organization in place of TURNER on the 5th of
September 1992 with employee number 7999, make the required changes.
c) Delete all the records of the employees whose job is ‘Computer Programmar’.
d) Convert the hire date of the employees to the number of years.
e) Display details of all employees who were hired earliest and latest.
5)
f) Find out the department in which the maximum number of employees works.
g) Select names of all employees whose names start with ‘S’.
h) Find the day of the week, time of the day, month and century on which SMITH joined.
i) Find out details of employees where commission is greater than 7% of salary.
j) Display the names of people and their departments working in either the Sales or
Research department.
6)
Based on the below mentioned schema/tables apply the SQL queries
EMP (Empno, Ename, Job, Mgr, Hiredate, Sal, Comm, Dept no)
DEPT (Deptno,Dname,Loc)
a) Display the department name which has more than 3 employees in it.
b) Write a query which concatenates the employee number, his name and manager number.
Display the output with spaces in between the columns.
c) Display the locations of the employees.
d) Display name, salary and location of employees who stay in CHICAGO.
e) List number, name, job, manager number and manager job of each employee.
f) Display information about employees who have the maximum number of employees
reporting to him.
g) Create a view on emp table which will display empno, ename, sal, deptno, dname
7)
Write a PL/SQL which will accept age of the person if age is more than 18 display message
as “Eligible for voting” else display message as “Not eligible for voting”
8)
Perform the following operations with the help of cursors
i. Increase salary of each customer by 5000.
ii. Retrieve the customer name and address.
9)
Create a stored function to perform item_id check operation. Which accepts item_id returns a
flag as per the id exist or not.

10)
Application using database triggers – Create a transparent audit system for a table
Client_master. The system must keep track of the records that are being deleted or updated.
When the record is deleted or modified the original record details date of operation are stored
in the audit table then the delete update is allowed to go.
13)
Create an XML file for three students by creating External DTD for student record which
includes elements as Name and Address Which consists of sub elements Name(Fname,
Lname),Address(Street, City, State, Zipcode, email, phone.
14
Create a simple XML file of your personal information
15
Create a XML Schema for a Library System. Which contains book Information like (Title,
Author, Publisher, Price)
17
Design and Develop MongoDB Queries using CRUD operations. (Use CRUD operations,
SAVE method, logical operators). 
