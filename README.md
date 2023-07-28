# Challenge 9 - Employee SQL
Data contains 6 csv files with data on the employees of Pewlett Hackard. schema.sql as the database setup and analysis.sql contains the analysis. 

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Installing](#installing)
- [Usage](#usage)
- [Contributing](#contributing)

## About
The ERD for this database is located in EmployeeSQL/EmloyeeSQL ERD.png. It ecompasses Pewlett Hackard employee personal, salary, title and department information. The schema for this database was explorted from QuickDBD after constructing the ERD, with some minor changes. 

Analysis.sql contains queries which retrieve employee data under various conditions. 

## Getting Started
Download data and EmployeeSQL folders. In Postgres, run schema.sql. Then import the csv data in the following order:
- title
- departments
- employees
- dept_emp
- dept_manager
- salaries
This order in necessary to avoid missing foreign key dependencies.
Then run each query in analysis.sql at will. 

## Installing
Download folders data and EmployeeSQL.

## Usage
Creates a database of employee data from Pewlett Hackard, and includes some recommended queries. 

## Contributing
Evangeline Allan
