# MySql

# Installation
Click on the URL It will redirect to MY SQL -> download page

[https://www.oracle.com/mysql/technologies/mysql-enterprise-edition-downloads.html#windows
](https://dev.mysql.com/downloads/file/?id=541636)

To install my sql we need to login to oracle account.

1. Provide all the required details.

2. create account.

3. Install My sql.


After installation:

type for MySql bench in search bar connect to the local database connection.

Ready to code!!

# Database

A database is an organized collection of data stored electronically. It allows users and applications to easily access, update, and manipulate information. This data contains text, numbers, images, videos and more. Databases are managed using specialized software known as a Database Management System (DBMS), which facilitates the storage, retrieval, and manipulation of data.

# Table



# Schema


# create database in SQL:

```sql
create database sql_class
```

# Datatypes
1.chr()
2.varChr()
3.float()
4.Double()
5.int()
6.BigInt()
7.Date()
8.DateTime()

# create a table in SQL:

```sql
CreaTe table Test(ID int(5),name char(5),height float(5,4));



```

# To show commands in a database

```sql
show tables;
```
# insert data in table:

```sql
Insert into test(ID,name) values(1,'sandy');
```

# display all data in table

```sql
select * from test;
```


# Where Cluase

# Arthematic operators

| Operator     | Description      | Example          |
| ------------ | ---------------- | ---------------- |
| `=`          | Equal to         | `salary = 50000` |
| `!=` or `<>` | Not equal to     | `name != 'John'` |
| `>`          | Greater than     | `age > 30`       |
| `<`          | Less than        | `stock < 100`    |
| `>=`         | Greater or equal | `score >= 60`    |
| `<=`         | Less or equal    | `rating <= 4.5`  |

```sql
--Filter by Columns
select age,name from drive;
--Filter by Rows using = operator/Equal To operator
select * from drive where(name="samiam");
--Filter by Rows using <> operator/ Not Equal to operator
select * from drive where(name<>"samiam");
--Filter by Rows using != operator/ Not Equal to operator
select * from drive where(name!="samiam");
--Filter by Rows using > operator/ Greater Than operator
select * from drive where(age>20);
--Filter by Rows using < operator/ Less than operator
select * from drive where(age<20);
--Filter by Rows using <= operator/Less than or equal to Operator
select * from drive where(age<=21)
--Filter by Rows using >= operator/ Greater than or equal to Operator
select * from drive where(age>=21)
```



# Logical Operator
| Operator | Description           | Example                              |
| -------- | --------------------- | ------------------------------------ |
| `AND`    | Both conditions true  | `age > 25 AND city = 'Delhi'`        |
| `OR`     | Either condition true | `role = 'Admin' OR role = 'Manager'` |
| `NOT`    | Negates condition     | `NOT (status = 'Inactive')`          |





