# application
Created GET and POST operations for cutomerEntity with id, firstname and lastname.
GET and POST methods are tested using Postman by the respective url's.
customer-application is connected to pgAdmin through application.properties,Postgres should be running in docker desktop manually.

#command to create docker container for postgres image
docker run -d --name postgresdb -p 5432:5432 -e POSTGRES_USER=(giveanyname) -e POSTGRES_PASSWORD=(giveanypassword) -e POSTGRES_DB=mydb postgres
