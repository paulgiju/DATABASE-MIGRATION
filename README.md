# DATABASE-MIGRATION

COMPANY NAME: CODTECH IT SOLUTIONS

NAME: PAUL GIJU THANNICKAL

INTERN ID : CT08JWE

DOMAIN: SQL

BATCH DURATION: JANUARY 20th to FEBRUARY 20th, 2024

MENTOR NAME: NEELA SANTHOSH

#DESCRIPTION
Database migration means moving data from one database system to another. In this task, we are transferring data from MySQL to PostgreSQL while ensuring everything stays accurate and functional. The process starts by exporting the MySQL database using the mysqldump command, which creates a backup file containing all the tables and data. However, because MySQL and PostgreSQL have different rules for handling data, we need to modify the backup file before importing it into PostgreSQL. Some key changes include converting AUTO_INCREMENT to SERIAL, removing MySQL-specific settings like ENGINE=InnoDB, and adjusting data types (e.g., changing TINYINT(1) to BOOLEAN).

To make this process easier, we can use a tool called pgloader, which automatically converts and imports the data. If this tool is unavailable, we can manually edit the SQL file to fix any differences. After importing the data into PostgreSQL using the psql command, we need to check if everything was transferred correctly. We do this by counting the number of rows in both databases and running some test queries to compare the results.

OUTPUT:
(https://github.com/user-attachments/assets/e6f7412d-b948-48e6-9338-823db70ed0c8)
