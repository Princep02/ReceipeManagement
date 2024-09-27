Introduction:

This document details the development of a simple Recipe Management System. This system allows users to create, read, update, and delete recipes from a database. It utilizes Java for development and connects to a MySQL database for data persistence.

Features:

CRUD Operations: Supports Create, Read, Update, and Delete (CRUD) operations on recipes in a MySQL database.
Recipe Caching: Implements a cache using a HashMap to store frequently accessed recipes by ID, improving performance.
User Interaction: Provides a console-based menu for users to manage recipes interactively.
SQL Integration: Utilizes JDBC to connect and interact with a MySQL database for data persistence.
Multithreading: Implements multithreading using ExecutorServices to handle concurrent operations, ensuring efficient and scalable management of recipe-related tasks.

Technical Requirements:

Programming Language: The project is built using Java for its core functionality.
Database: Requires MySQL for storing recipe data. The database connection is managed using JDBC.
MySQL JDBC Driver: Ensure that the MySQL JDBC Connector is included in the classpath to interact with the MySQL database.
