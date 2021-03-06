Novogen Database Web Application Generator
==================

A database web application generator that scaffolds a fully functioning application with CRUD pages and JSON API end points.
This is a database first development approach. The generator should figure out the database objects and create all the necessary user interface for it plus a rich set of JSON APIs.

Tools used:

- Java 8
- [Apache MetaModel](http://metamodel.apache.org/ "http://metamodel.apache.org/")
- [Pebble Template Engine](http://www.mitchellbosecke.com/pebble/home "http://www.mitchellbosecke.com/pebble/home") 
- Apache Maven


Goals
------------------
- To be able to generate a full fledge web application the following frameworks: 
    - Go (net/http)
    - ExpressJS
    - Laravel
    - SparkJava

- Support the following persistent store:
    - Mysql
    - Postgresql
    - Microsost SQL Server
    - MongoDB

- Generic enough to allow generation for more frameworks in other languages in the future.

Usage
------------------
- The Maven project will generate a novogen.jar file in the target directory
- The novogen.jar needs to be fed with a JSON file describing the project
- Example Usage: java -jar novogen.jar project.json


Generated Files
------------------
- The project will be generated in the path specified in project JSON file.
