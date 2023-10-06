# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>


## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>


## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```


## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```


### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![21q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/01d37c7f-fe82-41e8-98bc-df297d5ef9ff)

### OUTPUT:
![21o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/415f2e2a-9230-41b6-8646-2646c7a4f783)


### Q2) Delete the records from manager table where the salary less than 2750.

### QUERY:
![22q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/1b6dac61-832b-49b0-8172-3ab2beac5e3e)

### OUTPUT:
![22o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/04330681-910f-42dc-9dcc-ebef9fd77ea7)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)

### QUERY:
![23q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/1d6b0d4d-d8bb-4c59-aafc-4467a7557986)


### OUTPUT:
![23o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/33ccbccb-0cea-470d-8eb8-87d3bc9d1a4e)


### Q4)	List the names of Clerks from emp table.

### QUERY:
![24q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/a0758d54-1676-44ed-8cdf-47d1ad1706e2)

### OUTPUT:
![24q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/9bf274ab-9ccf-4a0a-af3f-72f6202ed2c7)


### Q5)	List the names of employee who are not Managers.

### QUERY:
![25q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/8871cf2e-2d56-486d-9bba-8a63a1d6643a)

### OUTPUT:
![25o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/922f15dc-3984-46cb-b429-a42c04c5eeb1)


### Q6)	List the names of employees not eligible for commission.

### QUERY:
![26q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/5034ffd5-6151-4b4b-a6c8-d5ec90f35e71)

### OUTPUT:
![26o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/efbbc318-279e-4ee8-9b59-b70f33131d62)


### Q7)	List employees whose name either start or end with ‘s’.

### QUERY:
![27q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/9ac3cfa2-2ab0-42b5-86ea-9fe326c41fb6)

### OUTPUT:
![27o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/9ac319f7-a3e1-4597-ab9d-fe1cf95a3782)


### Q8) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:
![28q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/888471ed-8171-4fc7-82f6-2391b5064fab)

### OUTPUT:
![28o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/3def0329-ad5e-42da-b816-cd739dc535db)


### Q9) List the Details of Employees who have joined before 30 Sept 81.

### QUERY:
![29q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/9f2e8098-6af2-4000-8c4d-642d72ef4084)

### OUTPUT:
![29o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/82835cb2-5954-4b2a-bb6b-a8e33c93c3eb)


### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

### QUERY:

![210q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/68cc4713-5184-4dce-8772-42f134390f56)

### OUTPUT:
![210o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/736cde75-01b3-4b9a-9fe7-b0fb6f1e964f)



### Q11) List the names of employees not belonging to dept no 30,40 & 10

### QUERY:
![211q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/967d3d75-52eb-4185-bcb6-9fce2a14e53c)

### OUTPUT:
![211o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/852c076a-b9f5-4d8a-85ed-faf574219003)


### Q12) Find number of rows in the table EMP

### QUERY:
![212q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/bf380f8e-810e-4263-86ea-8ef6fd93a8e0)

### OUTPUT:
![212o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/12197eaa-2e48-4292-aed2-b2d59acf5900)



### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:

![213q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/12906adc-f8f4-42af-816e-f30c7064bafa)

### OUTPUT:

![213o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/5d9da28d-5cd2-43d0-810b-c15728047157)


### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![214q](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/8959cd3e-9e03-4c6b-a977-284d7bdc5363)

### OUTPUT:
![214o](https://github.com/SudharsanamRK/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/115523484/4cd025dd-5365-4862-8f7c-27430abcbde1)


### RESULT
Thus,To create a manager database and execute DML queries using SQL is executed successfully.
