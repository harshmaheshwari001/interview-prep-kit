### Database and SQL Question

| Col_Name      | DataType      | Constrants  |
| ------------- |:-------------:| -----------:|
| Emp_Id        | numeric 		| primary-key |		
| Name      	| nvarchar(100) |   not-null  |
| salary 		| numeric       |    not-null |
|Address        | nvarchar(250) | not-null  | 
| Designation   | nvarchar(50)  | not-null    |
| DeptId		|numeric		| Foreign-key |



1. Find second hightest salary from Employee table.
2. LEFT OUTER JOIN Vs INNER JOIN
3. What IFNULL() statement is used for in MySQL?
	-- SELECT name, IFNULL(id,'Unknown') AS 'id' FROM Employee;  (if first argument not null return else )
4. What is the use of Windowfunction in Oracle. Can you please name or explain any 	   window function.	
5. Explain Rank() and danseRank() function in Oracle.
6. How to display top 50 rows? -- (limit 0,50)
7. How will you remove all duplicate reocrds from a table?   
8. How can you see all the indexes defined for a table?
9. Write Query in Oracle/SQL to return count of records 
 	* if table is empty count of records must return 0
    * else count of records =total number of records
10. Explain FullOuter join and it uses cases.
11. Write Query to return list of DeptId where no of employee more then 10    