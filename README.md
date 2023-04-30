Download Link: https://assignmentchef.com/product/solved-csc434-csc634-database-management-system-homework-2
<br>
<h1>SQL Queries</h1>

Consider the Bank Database.




Bank Database




<em>branch (<u>branch-name</u>, branch-city, assets)</em>

<em> </em>

<em>customer (<u>customer-name</u>, customer-street, customer-city)</em>

<em> </em>

<em>account (<u>account-number</u>, branch-name, balance)</em>

<em> </em>

<em>loan (<u>loan-number</u>, branch-name, amount)</em>

<em> </em>

<em>depositor (<u>customer-name, account-number</u>)</em>

<em> </em>

<em>borrower (<u>customer-name, loan-number</u>) </em>

<em> </em>

<em>employee (<u>employee-name, branch-name</u>, salary) </em>

Do the following:

<ol>

 <li>Create the Bank database. Bank database schema is available on the blackboard.</li>

 <li>Populate the Bank Database, using the data records available on the blackboard.</li>

 <li>Do the following queries:</li>

</ol>




For each query:

Write the question

Write the SQL statement

Provide the output. For update queries (insert, delete, replace), display the table(s) before the query and after the query.




<h2>Retrieval Queries</h2>




<ol>

 <li>Find all loan number for loans made at the Perryridge branch with loan amounts greater than $1100.</li>

 <li>Find the loan number of those loans with loan amounts between $1,000 and $1,500 (that is, &gt;=$1,000 and &lt;=$1,500)</li>

 <li>Find the names of all branches that have greater assets than some branch located in Brooklyn.</li>

 <li>Find the customer names and their loan numbers for all customers having a loan at some branch.</li>

 <li>Find all customers who have a loan, an account, or both:</li>

 <li>Find all customers who have an account but no loan.</li>

</ol>

(no minus operator provided in mysql)

<ol start="7">

 <li>Find the number of depositors for each branch.</li>

 <li>Find the names of all branches where the average account balance is more than $500.</li>

 <li>Find all customers who have both an account and a loan at the bank.</li>

 <li>Find all customers who have a loan at the bank but do not have an account at the bank</li>

 <li>Find the names of all branches that have greater assets than all branches located in Horseneck. (using both non-nested and nested select statement) 12. 1 query of your choice involving aggregate functions 13. 1 query of your choice involving group by feature.</li>

</ol>

<h2>Insert Queries</h2>

Do 2 insert queries requiring multiple records insertion as follow:

<ol>

 <li>Create a HighLoan table with loan amount &gt;=1500.</li>

 <li>Create a HighSalaryEmployee table with employee having salary more than 2000.</li>

 <li>1 more query (meaningful) of your choice on any table.</li>

</ol>

<h2>Update Queries</h2>

<ol>

 <li>Increase all accounts with balances over $800 by 7%, all other accounts receive 8%.</li>

 <li>Do 2 update queries, each involving 2 tables.</li>

 <li>1 more update query of your choice on any table.</li>

</ol>

<h2>Delete Queries</h2>

<ol>

 <li>Delete the record of all accounts with balances below the average at the bank.</li>

 <li>Do 2 update queries, each involving 2 tables.</li>

 <li>1 more delete query of your choice from any table.</li>

</ol>




<h2>Views Queries</h2>

<ol>

 <li>A view consisting of branches and their customers</li>

 <li>Create a view of HQEmployee who work in downtown branch.</li>

 <li>Do one insert, delete, update, and select queries on HQEmployee view.</li>

</ol>




<h2>Complex Queries: provide results</h2>

<ol>

 <li>1 select query involving 3 tables</li>

 <li>1 Delete query involving 3 tables</li>

 <li>1 Update query involving 3 tables</li>

</ol>




Submit your Homework 2 as a PDF file as

YourName.pdf

Including. All your questions, SQL statements, and results.