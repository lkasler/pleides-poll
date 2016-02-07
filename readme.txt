Introduction to pleides-poll project

Root URL:
curl http://localhost:8080/people

Add a person:
curl -i -X POST -H "Content-Type:application/json" -d '{  "firstName" : "Frodo",  "lastName" : "Baggins" }' http://localhost:8080/people
