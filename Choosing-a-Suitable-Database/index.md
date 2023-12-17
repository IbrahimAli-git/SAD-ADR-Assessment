# Title
Implementation of data storage use a Non-Relational NoSQL Database

## Status
Accepted

## Context
During the planning stage of the project choosing a suitable database was imperative. I needed a database for storing and retrieving data efficiently. I also needed to be able to set up the databse in a short period of time. My options were split between non-relational databases and relational. My choice for a non-relational database was MongoDB, and for a relational was MySQL.

## Decision
I decided to use a non-relational database for implementing my backend and specifically MongoDB.

## Rationale
My decision to design using a MongoDB, a non-relational database, was based on many reasons. From them:

1. MongoDB allows for quickly setting up a database and collections. This is because MongoDB creates a database collection based on the schema given and does not require the collection to be defined by the user.
2. MongoDB integrates well with JavaScript frameworks including React.js and Express.js.
3. MongoDB is free to use and download.

## Consequences
The use of a non-relational database will require the user to have knowledge of NoSQL and the know-how to work with MongoDB. This may require some training beforehand. On the other hand this will speed up the development process.
