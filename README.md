# clg-sql-work
here all the my work is saved

### employee table sructure 

```sql
create table employee(
EMP_ID  VARCHAR(5),
EMP_NAME VARCHAR(20),
EMP_CITY VARCHAR(18),
EMP_DOB DATE,
EMP_AGE VARCHAR(2),
EMP_DOJ DATE,
DESIGNATION VARCHAR(10),
SALARY float(8,2),
DEPT_NO VARCHAR(5)
);
```

### employee table data
```sql
INSERT INTO `employee`(`EMP_ID`, `EMP_NAME`, `EMP_AGE`, `EMP_DOB`, `SALARY`, `EMP_DOJ`, `DESIGNATION`, `DEPT_NO`, `EMP_CITY`) 
VALUES 
('E001', 'Jitendra', 23, '1999-03-24', 123456.78, '2020-02-09', 'Developer', 0, 'Raipur'),
('E002', 'John', 23, '1999-06-01', 123456.78, '2021-01-01', 'Professor', 0, 'Bilaspur'),
('E003', 'Shubham', 25, '1998-01-01', 50000, '2020-01-01', 'Manager', 1, 'Bhilai'),
('E004', 'Nilesh', 30, '1993-05-05', 60000, '2015-06-01', 'Analyst', 2, 'Rajim'),
('E005', 'Jane', 25, '1997-08-12', 234567.89, '2020-02-02', 'Assistant Professor', 3, 'Durg'),
('E006', 'Pooja', 40, '1983-03-15', 80000, '2005-04-01', 'Manager', 4, 'Abhanpur'),
('E007', 'Ravi', 35, '1988-10-10', 70000, '2010-11-01', 'Developer', 3, 'Raipur'),
('E008', 'Bob', 22, '2001-03-15', 345678.9, '2019-03-03', 'Associate Professor', 6, 'Durg'),
('E009', 'David', 26, '1995-12-31', 567890.12, '2022-05-05', 'Professor', 7, 'Bhilai'),
('E011', 'Tom', 26, '1995-12-31', 7890.12, '2022-05-05', 'Peon', 4, 'Raipur'),
('E012', 'Alice', 24, '1999-11-30', 456789.01, '2018-04-04', 'Assistant Professor', 3, 'Rajim'),
('E013', 'Chaitanya', 45, '1978-08-20', 90000, '2000-09-01', 'Analyst', 6, 'Chennai');
```

### Department table
```sql

CREATE TABLE `department` (
  `DEPT_NO` int(3) DEFAULT NULL,
  `DEPT_NAME` varchar(12) DEFAULT NULL,
  `DEPT_PHONE` varchar(10) DEFAULT NULL,
  `HOD` varchar(15) DEFAULT NULL
) 
```

### department table data
```
INSERT INTO `department` (`DEPT_NO`, `DEPT_NAME`, `DEPT_PHONE`, `HOD`) VALUES
(0, 'Computer Sci', '1234567890', 'Dr. Anjali Shar'),
(1, 'Finance and ', '2345678901', 'Dr. Rajesh Verm'),
(2, 'Marketing an', '3456789012', 'Dr. Priya Singh'),
(3, 'Human Resour', '4567890123', 'Dr. Amit Kumar'),
(4, 'Natural Scie', '5678901234', 'Dr. Neha Kapoor'),
(6, 'Social Scien', '7890123456', 'Dr. Rahul Sharm'),
(7, 'Research and', '8901234567', 'Dr. Vikram Gupt');
```




