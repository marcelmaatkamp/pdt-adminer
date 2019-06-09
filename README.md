# pdt-adminer

 * https://www.adminer.org/
 * https://hub.docker.com/_/adminer/

# Usage
 
Goto http://adminer:8080

# Drivers

While Adminer supports a wide range of database drivers this image only supports the following out of the box:
 * MySQL
 * PostgreSQL
 * SQLite
 * SimpleDB
 * Elasticsearch

To add support for the other drivers you will need to install the following PHP extensions on top of this image:
 * pdo_dblib (MS SQL)
 * oci8 (Oracle)
 * interbase (Firebird)
 * mongodb (MongoDB)

