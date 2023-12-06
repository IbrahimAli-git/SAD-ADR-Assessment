# Title
Implementation of data storage use a Relational Database

## Status
Accepted

## Context
During the planning stage of the project choosing a suitable database was imperative. I needed a database for storing and retrieving data efficiently. I also needed to be able to set up the databse in a short period of time. My options were split between non-relational databases and relational. My choice for a non-relational database was MongoDB, and for a relational was MySQL.

## Decision
I decided to use a relational database for implementing my backend and specifically MySQL.

## Rationale
My decision to design using a relational database was based on many reasons. From them:

1. Relational Databases are ACID compliant which facilitates quick and efficient transactions.
2. Relational databases use constraints which ensures data is stored in a structured and ordered manner which prevents data corruption.
3. Relational databases such as MySQL are free to use and download.

## Consequences
The use of a relational database will require the user to have knowledge of SQL. This may require learning.
