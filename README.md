
## DATABASE🚀 
- A database is a collection of data that is organized in a manner that facilitates ease of access, as well as efficient management and updating.



##  Database Tables📑
- A table stores and displays data in a structured format consisting of columns and rows that are similar to those seen in Excel spreadsheets.

- Databases often contain multiple tables, each designed for a specific purpose. For example, imagine creating a database table of names and telephone numbers.

 


## Example

| Name             | Phone                                                                |
| ----------------- | -------------------- |
| vikash | 8893564829|
| piyush | 7893564829 |
| Bhui | 9893564829|
| Chootu | 9073564829 |

## Primary keys🔑
- A primary key is a field in the table that uniquely identifies the table records.
The primary key's main features:
- It must contain a unique value for each row.
- It cannot contain NULL values.

- For example, our table contains a record for each name in a phone book. The unique ID number would be a good choice for a primary key in the table, as there is always the chance for more than one person to have the same name.
|ID| Name | Phone |
| -: || :- | :-|
|1| vikash |  7693564829 |
|2| piyush | 7393564829 |
|3| piyush | 7993564829|
|4| Chootu | 7293564829 |






## SQL🚀 
- SQL stands for Structured Query Language.
- SQL is used to access and manipulate a database.
- MySQL is a program that understands SQL.
### SQL Can:
- insert, update, or delete records in a database.
- create new databases, tables, stored procedures and views.
- retrieve data from a database, etc.
## Basic SQL Commands
  #### - SHOW
- The SQL SHOW statement displays information contained in the database and its tables.
```bash
SHOW DATABASES
```
#### - COLUMNS
- SHOW COLUMNS displays information about the columns in a given table.
```bash
SHOW COLUMNS FROM customers
```
#### Example
 
 | Field | Type | Null |Key |
| :-- | :--: | ---: | ---: |
| Name   |  varchar(11)  |    NO|PRI
| City     |    varchar(60)   |    NO | |

#### - SELECT
- The SELECT statement is used to select data from a database.
- Syntax of the SQL SELECT Statement:
```bash
SELECT column_list
FROM table_name
```
- column_list includes one or more columns from which data is retrieved
- table-name is the name of the table from which the information is retrieved
### Example
```bash
SELECT Name FROM customers
```
| Name                                                                             |
| --- | 
| vikash | 
| piyush | 
| Bhui | 
| Chootu |



