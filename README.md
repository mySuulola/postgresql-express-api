# Postgres Express && Node


# To add to database from commandline
- curl --data "name=<NAME>&email=<EMAIL>" http://localhost:3000/users
-- e.g curl --data "name=Suulola&email=oluwaseyisuulola@gmail.com" http://localhost:3000/users



#To delete
- curl -X "DELETE" http://localhost:3000/users/<ID>
e.g curl -X "DELETE" http://localhost:3000/users/1

#To update 
- curl -X PUT -d "name=<NAME>" -d "<EMAIL>" http://localhost:3000/users/<ID>
e.g. curl -X PUT -d "name=Suulola" -d "email=oluwaseyisuulola@gmail.com" http://localhost:3000/users/1

#To delete
- curl -X "DELETE" http://localhost:3000/users/<ID>
e.g.  curl -X "DELETE" http://localhost:3000/users/1

#Thanks to Tania Rascia Tutorial
