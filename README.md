# docker-ws-week2
This is a simple application that displays some records from mysql database.The application
consist of three containers as defined in docker-compose file. 
The data base service is mysql server with preloaded data from a sql file.
The Studentapi service is a springboot application that ineracts with databse service.
The student ng service is an angular application that fetches data thru rest end points defined in 
studentapi. The database service stores it's data in volume defined in docker compose file.
The application can be run by below docker-compose command:

docker-compose up -d
