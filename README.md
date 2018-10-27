This is a simple application to demonstrate the usability of in-memory H2 database. In order to test the application, clone the git 
repo into the local, setup the maven dependency and then spin up the Spring boot Application. 

We can test out the application with the following URL on our web browser,

http://localhost:8080/student

This should result in a successful JSON response as following,


[{"NAME":"Rakesh","ROLL":12,"GRADE":"A"},{"NAME":"Mukesh","ROLL":11,"GRADE":"A"},{"NAME":"Brajesh","ROLL":12,"GRADE":"B"}]
