# clg-sql-work
here all the my work is saved

### employee table sructure 

```
"Column Name","Data Type","Nullable","Default","Primary Key"
"EMPNO","NUMBER(4,0)","No","","1"
"ENAME","VARCHAR2(10)","Yes","",""
"JOB","VARCHAR2(9)","Yes","",""
"MGR","NUMBER(4,0)","Yes","",""
"HIREDATE","DATE","Yes","",""
"SAL","NUMBER(7,2)","Yes","",""
"COMM","NUMBER(7,2)","Yes","",""
"DEPTNO","NUMBER(2,0)","Yes","",""

```

### employee table data
```csv
"E_ID","E_NAME","E_AGE","E_DOB","SALARY","E_JOINING_DATE","E_DESIGNATION","DEPT_NO"
"1","Jitendra","23","03/24/1999","123456.78","02/09/2020","Developer","10"
"2","John","23","06/01/1999","123456.78","01/01/2021","Professor","10"
"3","Shubham","25","01/01/1998","50000","01/01/2020","Manager","1"
"4","Nilesh","30","05/05/1993","60000","06/01/2015","Analyst","2"
"5","Jane","25","08/12/1997","234567.89","02/02/2020","Assistant Professor","3"
"6","Pooja","40","03/15/1983","80000","04/01/2005","Manager","4"
"7","Ravi","35","10/10/1988","70000","11/01/2010","Developer","3"
"8","Bob","22","03/15/2001","345678.9","03/03/2019","Associate Professor","6"
"9","David","26","12/31/1995","567890.12","05/05/2022","Professor","7"
"11","Tom","26","12/31/1995","7890.12","05/05/2022","Peon","4"
"12","Alice","24","11/30/1999","456789.01","04/04/2018","Assistant Professor","3"
"13","Chaitanya","45","08/20/1978","90000","09/01/2000","Analyst","6"
```

### Department table
```csv

"Column Name","Data Type","Nullable","Default","Primary Key"
"DEPTNO","NUMBER(5,0)","Yes","",""
"DEPTNAME","VARCHAR2(12)","Yes","",""
"DEPT_PHONRNO","NUMBER(10,0)","Yes","",""
"HOD","VARCHAR2(12)","Yes","",""

```

### department table data
```
insert into departments values(101,'CSIT',9346674367,'Jitendra Sahu')
insert into departments values(103,'PHYSICS',6574386547,'Mukesh')
insert into departments values(104,'EDUCATION',6287564325,'Ravi')
insert into departments values(105,'CHEMISTRY',8764536782,'Yashvant')
insert into departments values(106,'HISTORY',9876543765,'Nilesh')
insert into departments values(107,'CSIT',6574893087,'Lokesh')
```




