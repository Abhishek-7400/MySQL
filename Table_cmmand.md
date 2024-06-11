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
## INT(size): A normal-sized integer that can be signed or unsigned. It typically ranges from -2147483648 to 2147483647.(Mostly Used)
## BIGINT: A large integer that can be signed or unsigned. It typically ranges from -9223372036854775808 to 9223372036854775807.
## FLOAT(size, d)	A floating point number. The total number of digits is specified in size. The number of digits after the decimal point is specified in the d parameter.
## BOOLEAN:	Equal to BOOL

# 2.String Types
## CHAR(size): A FIXED length string (can contain letters, numbers, and special characters). The size parameter specifies the column length in characters - can be from 0 to 255. Default is 1.
## VARCHAR(size): A VARIABLE length string (can contain letters, numbers, and special characters). The size parameter specifies the maximum column length in characters - can be from 0 to 65535.
## TEXT(size): Holds a string with a maximum length of 65,535 bytes.
## BINARY(size): Equal to CHAR(), but stores binary byte strings. The size parameter specifies the column length in bytes. Default is 1.
## VARBINARY(size): Equal to VARCHAR(), but stores binary byte strings. The size parameter specifies the maximum column length in bytes.

# Date Type
## DATE: A date. Format: YYYY-MM-DD.
## DATETIME(fsp): A date and time combination. Format: YYYY-MM-DD hh:mm:ss.
## TIME(fsp): A time. Format: hh:mm:ss.
## YEAR: A year in four-digit format. Values allowed in four-digit format: 1901 to 2155


