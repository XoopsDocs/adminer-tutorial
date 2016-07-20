# 1.0 Install\/Uninstall

No special measures necessary, follow the standard installation process & extract the module folder into the

\/modules

directory in your XOOPS installation. Install the module through Admin -&gt; System Module -&gt; Modules.

Detailed instructions on installing modules are available in the [**Chapter 2.12 of our XOOPS Operations Manual**](https://www.gitbook.com/book/xoops/xoops-operations-guide/)

### Individual Features

#### Adminer

* Connect to a database server with username and password
* Select an existing database or create a new one
* List fields, indexes, foreign keys and triggers of table
* Change name, engine, collation, auto\_increment and comment of table
* Alter name, type, collation, comment and default values of columns
* Add and drop tables and columns
* Create, alter, drop and search by indexes including fulltext
* Create, alter, drop and link lists by foreign keys
* Create, alter, drop and select from views
* Create, alter, drop and call stored procedures and functions
* Create, alter and drop triggers
* List data in tables with search, aggregate, sort and limit results
* Insert new records, update and delete the existing ones
* Supports all data types, blobs through file transfer
* Execute any SQL command from a text field or a file
* Export table structure, data, views, routines, databases to SQL or CSV
* Print database schema connected by foreign keys
* Show processes and kill them
* Display users and rights and change them
* Display variables with links to documentation
* Manage events and table partitions \(MySQL 5.1\)
* Schemas, sequences, user types \(PostgreSQL\)
* Extensive customization options 

#### Adminer Editor

* Interface to select and edit data ready for your client
* Table and column comments are displayed instead of identifiers
* Separate set of login credentials different from the real database user and password
* Single database per one instance of Editor
* Links to referenced records
* Works with the name of a referenced record, not its ID
* Displays images stored in BLOB
* Displays checkbox and icons for BOOL
* Uses national format for DATE
* Allows sending messages to e-mails found in table
* No edit or display of SQL commands \(only in HTML comment\)

  #### BigDump


* Imports large and very large MySQL Dumps \(like [phpMyAdmin](http://www.phpmyadmin.net/) dumps\) 
* Does it even through the web servers with hard runtime limit and those in safe mode. 
* The script imports only a small part of the huge dump and restarts itself. The next session starts where the last was stopped. 

