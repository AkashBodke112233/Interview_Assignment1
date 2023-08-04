# Interview_Assignment1
curl of first API:
curl --location 'http://localhost:9094/elevator/moveElevator' \
--header 'Content-Type: application/json' \
--data '{
    "destToFloor": "4",
    "direction":"up"
}'

curl of 2nd API:
curl --location 'http://localhost:9094/elevator/statusOfElevator' \
--data ''
