# Damn

curl -X POST http://localhost:3000 -H "Content-Type: application/json" -d '{"age": 1, "name": "Elon Musk", "acceptedTOS": true, "nums": [2]}'

curl -X POST http://localhost:3000 -H "Content-Type: application/json" -d '{"age": "1", "name": "Elon Musk", "acceptedTOS": true, "nums": [2]}'