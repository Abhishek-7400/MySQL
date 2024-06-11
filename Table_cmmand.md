# Table (Collection of raws and columns where we can store relation data)
## During the creation of table in particular database we need Table Name, Column Name And Datatype(String,Numric,Boolean,etc)
### Syntax
```
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
   
);
```
### Example
```
CREATE TABLE Student_Details (
    Id INT,
    Name VARCHAR(20),
    Birth_Date DATE,
    Phone_Number VARCHAR(20),
    Gender VARCHAR(1),
);
```

## three Different datatypes used to strore data is table
1. String
2. Numeric
3. Date & Time

# 1. Numeric Types
. INT: A normal-sized integer that can be signed or unsigned. It typically ranges from -2147483648 to 2147483647.
. BIGINT: A large integer that can be signed or unsigned. It typically ranges from -9223372036854775808 to 9223372036854775807.
