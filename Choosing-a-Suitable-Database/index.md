# Lightweight ADR

# Title
Use a Relational Database

## Status
Accepted

## Context
I needed a database for storing and retrieving data efficiently. My options were split between non-relational databases and relational. My choice for a non-relational database was MongoDB, and for a relational was MySQL.

## Decision
I decided to use a relational database. This is because relational databases are structured, ordered, and store data in an efficient manner,that is based on ACID principles. 

## Consequences
Data will be stored in tables with relationships between each.
