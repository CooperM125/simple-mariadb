# simple-mariadb

This is a simple docker that creates a mysql server and starts with a simple table with optional data to see if the server is working. To see if the server is working please download and run mysql workbench found in helpful links.

## How to run

The commands to run this simple mysql database are as follows.

```
docker build -t maria-test .
docker run -p 127.0.0.1:3306:3306 -e MARIADB_ROOT_PASSWORD=root maria-test
```
### Helpful links
- Mariadb Docshttps://hub.docker.com/_/mariadb
- mysql Workbench - https://www.mysql.com/products/workbench/