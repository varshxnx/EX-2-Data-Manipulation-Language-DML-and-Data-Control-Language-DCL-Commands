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
![21q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/1aef1cd5-19a7-4d8a-a257-9896751d1e1a)




### OUTPUT:
![21o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/1cb62181-28a0-4736-b7f6-30261f9386c0)



### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![22q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/0ea62175-4324-4da1-af18-bb56bdb57d75)


### OUTPUT:

![22o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/b6a43c12-2d1b-445c-82b0-0c39d70f7b57)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![23q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/c6346dfd-470c-4ba1-96b2-156ec0a2682a)


### OUTPUT:

![23o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/bb6d15a1-6be2-48bb-82b6-0874db34ad28)

### Q5)	List the names of Clerks from emp table.


### QUERY:
![5q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/1c496838-ee1d-4658-a1e1-53383e9f18cd)




### OUTPUT:
![25o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/1d85ae7f-eaef-47c8-b9c8-5a9f1482f681)



### Q6)	List the names of employee who are not Managers.


### QUERY:
![6q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/b1a40d0a-f3c1-4270-bd12-7296c078c63c)



### OUTPUT:
![26o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/5f7874a7-a7dd-4313-b7e6-96de6ed239b2)


### Q7)	List the names of employees not eligible for commission.


### QUERY:

![7q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/6a159930-2aeb-4906-8163-bb4a2f1e23b7)


### OUTPUT:

![27o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/2f585578-fcfd-43a8-bcba-5a6de8636c63)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![8q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/3102f99d-eaae-4749-b2d9-26e4cb651a66)



### OUTPUT:
![28o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/6e9d097e-c925-44d6-a4d2-b3c73dc48a31)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![9q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/ac2ca0e2-7002-4db0-a38f-0d7533466d08)


### OUTPUT:

![29o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/f93d662b-db07-41b8-9061-47ae1397c533)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![10q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/6315d153-f6fe-4b6d-9985-9a290363e31e)




### OUTPUT:
![210o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/6a01eddf-f2f5-489b-9597-0a1ac533e8c1)



### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![11q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/2c0c89bd-e753-4401-a932-d7804c99beee)


### OUTPUT:
![211o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/b73e00e6-9496-4ad3-9401-f34ada36ef5b)



### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![12q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/db82b8b3-f7da-4de5-9c65-45d3143357ee)



### OUTPUT:
![212o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/ac316255-7b16-4f86-bd2d-86da3292e300)


### Q13) Find number of rows in the table EMP

### QUERY:
![13q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/c39ad88e-0e1d-4a4f-8498-a25e37d6a505)



### OUTPUT:
![image](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/a65bc0b7-ee04-4166-b6ab-0c1f599a7184)



### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![14q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/35e39092-21e8-438a-8494-d6426bd089e9)



### OUTPUT:

![214o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/3bd86871-56c0-4b83-aa69-cf5c5c089e1b)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![15q](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/99f635cf-3d63-4247-91c9-fec19c232142)



### OUTPUT:
![215o](https://github.com/varshxnx/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122253525/3199c9d3-0062-4255-93c1-8bd76fb9e62a)


### RESULT:
The Data Manipulation Language (DML) Commands and built in functions in SQL is executed sucessfully.

