<h1>SQL Identity and Employee Management</h1>



<h2>Description</h2>
<b>
In this database exploration project, I took on the role of a security analyst tasked with retrieving specific information about employees, their machines, and department affiliations. Leveraging SQL queries, I applied logical operators such as AND, OR, and NOT to filter data effectively. Tasks included identifying failed login attempts after business hours, retrieving login attempts on specific dates, isolating logins outside of Mexico, and extracting details about employees in the Marketing department. Additionally, I located records for employees in Finance or Sales and identified those not in the Information Technology department. This hands-on experience showcases my proficiency in SQL query execution for targeted data retrieval in a database security context.

</b>
<br />
<br />
<br />
<br />



<h2>Identity and Employee Login using SQL Queries</h2> 

- <b>Analyzing After-Hours Failed Login Attempts:</b> SQL Filtering in Action

  - <b>Description:</b> Utilized SQL filtering with the AND operator to identify and retrieve failed login attempts occurring after business hours (18:00). Analyzed the log_in_attempts table using the login_time and success columns to pinpoint potential security issues during specific time frames.
    - Employed SQL filtering with the AND operator to retrieve failed login attempts after business hours, analyzing the log_in_attempts table based on login_time and success columns.

    - Utilized SQL filtering with the OR operator to retrieve login attempts on specific dates ('2022-05-09' and '2022-05-08') from the log_in_attempts table.

    - Investigated logins outside of Mexico using the NOT and LIKE operators with the pattern 'MEX%' in the country field of the log_in_attempts table.

    - Extracted information about employees in the 'Marketing' department located in East building offices ('East-170' or 'East-320') using SQL queries on the employees table with the AND and LIKE operators.

<p align="center">
<img src="https://imgur.com/XI8ghu3.png" height="85%" width="85%" alt="Directory discovery and File exploration"/>
</p>

<p align="center">
<img src="https://imgur.com/VkkkodF.png" height="85%" width="85%" alt="Directory discovery and File exploration"/>
</p>

<h2>Securing File Permissions in the Directory: Access Management</h2>

- <b>Access Management for Departmental Updates:</b> SQL Filtering in Action

  - <b>Description:</b> Executed SQL queries to gather crucial employee data for specific departmental updates in Finance and Sales, showcasing precise access management strategies in the realm of cybersecurity.

    <b>Task 1: Retrieve Employees in Finance or Sales</b>
    -  Leveraging SQL queries, Identified and retrieved records for employees in the Finance or Sales departments
  
    -  Ensuring targeted access management for departmental updates.

    
    <b>Task 2: Retrieve Employees Not in IT</b>
    - Employing SQL queries with the NOT operator, I obtained information about employees outside the Information Technology department.
      - A critical step in implementing robust access management measures.





<p align="center">
<img src="https://imgur.com/fvAZfFb.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
