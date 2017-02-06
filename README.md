# PostgreSQL & SQLite

This repository is an attempt to imply some core concepts of SQL programming with Python 2.7 and bash. It is divided in three parts:

- The first part covers the basics of PostgreSQL programming with implementation of some trivial databases in order to practice the concepts. The notebook is inspired by zetcode.com's tutorial for the PostgreSQL database and postgresql's documentation. The popular psycopg2 library is used in this implementation and it is executed on a JN.

  <A href='http://nbviewer.jupyter.org/github/sametmarasli/PostgreSQL_SQLite/blob/master/psql%26python.ipynb'>psql&python</A><BR>


- The second part covers the fundamentals of SQLite programming again with the implementation of some trivial databases for practice purposes. The material is inspired by the Coursera's course Using Databases with Python by University of Michigan. sqlite3 library is used in this implementation and again it is executed on a JN.

  <A href='http://nbviewer.jupyter.org/github/sametmarasli/PostgreSQL_SQLite/blob/master/sqlite%26python.ipynb'>sqlite&python</A><BR>


- Finally, in addition to the notebooks above which are created as a memo for myself, this repo hosts several small projects about SQLite, PostgreSQL and their implementation with python.

In this small project, I build a PostgreSQL DB from the Itunes library which is an XML file. 
<A href='http://nbviewer.jupyter.org/github/sametmarasli/PostgreSQL_SQLite/blob/master/project/itunesDB/project_itunesdb.ipynb'>Project : itunesDB</A><BR>


This notebook creates a SQLite DB from a mailbox data (mbox.txt) 
<A href='http://nbviewer.jupyter.org/github/sametmarasli/PostgreSQL_SQLite/blob/master/project/emailDB/project_emaildb.ipynb'>Project : emailDB</A><BR>


This small project, I build a notebook which builds a SQLite DB from the roster data in JSON format
<A href='http://nbviewer.jupyter.org/github/sametmarasli/PostgreSQL_SQLite/blob/master/project/rosterDB/rosterDB.ipynb'>Project : rosterDB</A><BR>


## Topics Covered

- Basic Structured Query Language - Single Table Create, Read, Update and Delete
- Aggregation, Where, Comparison Operators, Limit/Offset, Order by, Group by, Having
- Reconstructing Data with JOIN
- Uniqueness and Keys
- Inserts in DB-API (namely psycopg2 and sqlite3)
- Representing a Data Model in Tables
- Inserting Relational Data
- Parsing XML, JSON and TXT files and create DB from them
- Connecting DB's to pandas DataFrames
- Many to Many Relationships in SQL
- Subqueries

Work in process...

