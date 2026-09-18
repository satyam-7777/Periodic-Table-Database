# Periodic Table Database

A PostgreSQL and Bash scripting project completed as part of the **freeCodeCamp Relational Database Certification**.

## Project Overview

This project involves creating a database containing information about chemical elements using **Bash** and **PostgreSQL**.

The program is designed to retrieve information about elements from a periodic table database. It allows users to provide an element identifier and retrieve the corresponding element information from the PostgreSQL database.

## Technologies Used

- PostgreSQL
- SQL
- Bash
- Git
- GitHub

## Database Structure

The database contains information related to chemical elements, including:

- Atomic numbers
- Element symbols
- Element names
- Atomic masses
- Melting points
- Boiling points
- Element types

The database uses related tables to organize information about the elements and their properties.

## Element Information

The `element.sh` Bash program provides an interactive way to retrieve information about chemical elements.

The program allows users to:

- Enter an element atomic number, symbol, or name
- Search for the corresponding element
- Retrieve element properties from the PostgreSQL database
- Display the element information in the terminal

The program uses PostgreSQL queries to retrieve the requested element information from the database.

## Project Requirements

The project was completed according to the freeCodeCamp requirements.

The project had to:

- Use PostgreSQL
- Create and modify the required database tables
- Include the required element information
- Store chemical element data
- Create a Bash script to retrieve element information
- Connect the Bash program with PostgreSQL
- Query the database using an element identifier
- Pass all project tests
- Export the completed database as `periodic_table.sql`
- Save the completed `element.sh` file
- Submit the project through a public GitHub repository

## Project Files

The main project files are:

```text
periodic_table.sql
element.sh
