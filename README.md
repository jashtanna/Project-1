here are cURl to perform actions ::
1: curl --location 'http://localhost:8080/users'

2: curl --location 'http://localhost:8080/users' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name": "Jash1",
    "email": "jash1@example.com"
}'

3:curl --location 'http://localhost:8080/users/1'

4:curl --location --request PUT 'http://localhost:8080/users/1' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name": "hjasscf",
    "email": "jksdf@example.com"
}'

5:  curl --location --request DELETE 'http://localhost:8080/users/1'

#   P r o j e c t - 1  
 