# Student Data ETL Using Pentaho Data Integration

## Aim
To extract student data from a CSV file and load it into a MySQL database using Pentaho Data Integration (PDI).

## Tools Used
- Pentaho Data Integration (Spoon)
- MySQL
- Git and GitHub

## Dataset
The input CSV file contains the following attributes:
- Student ID
- Student Name
- Age
- Department
- Email

## Database Details
- Database: `college`
- Table: `students`

## Procedure
1. Create a CSV file containing student details.
2. Create a MySQL database named `college`.
3. Create a table named `students`.
4. Open Pentaho Data Integration (Spoon).
5. Add the CSV File Input step.
6. Add the Table Output step.
7. Connect CSV File Input to Table Output.
8. Configure the CSV input file and MySQL database connection.
9. Run the transformation.
10. Verify the inserted records using:

```sql
SELECT * FROM students;
```

## Result
Student data was successfully extracted from the CSV file and loaded into the MySQL database using Pentaho Data Integration.
