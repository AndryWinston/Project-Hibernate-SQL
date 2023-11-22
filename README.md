# Project about: SQL, JDBC & Hibernate

Task:
There is a relational MySQL database with a schema (country-city, language by country). 
And there is a frequent request from the city, which slows down. 
The solution is to move all the data that is requested frequently to Redis (in memory storage of the key–value type).

Technology:
MySQL, Hibernate, Redis, Docker

To do:
1. Configure the Docker.
2. Run the MySQL server as a docker container.
3. Expand the dump.
4. Create a project in IntelliJ IDEA, add maven dependencies.
5. Make a domain layer.
6. Write a method for getting all the data from MySQL.
7. Write a data transformation method (only data that is requested frequently will be written in Redis).
8. Launch the Redis server as a Docker container.
9. Write data to Redis.
10. Write a method for getting data from Redis and MySQL.
11. Compare the speed of getting the same data from MySQL and Redis.

MySQL Connection: 
IP: 127.0.0.1:3306
username: root,
password: root;
