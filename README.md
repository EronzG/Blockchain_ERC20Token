Setup Instructions
To download this project:

$ git clone https://github.com/EronzG/Blockchain_19242794.git

To install the dependencies (web3, express, etc):

$npm install

To run the code as a web server:

$node handlers.js

To curl (see-url) your webserver and get it to interact with Ethereum

GET Total Token Supply:

curl -XGET http://localhost:8082/totalsupply

GET Token Balance:

curl -XGET http://localhost:8082/balance/0x16261dF3d8eF130417755bF1Ab3da93D35cc4997

Distribute Tokens:

curl -XPOST http://localhost:8082/transfer


Or using an API testing tool such as POSTMAN

create new requests for the calls

GET - http://localhost:8082/totalsupply

GET - http://localhost:8082/balance/0x16261dF3d8eF130417755bF1Ab3da93D35cc4997

POST - http://localhost:8082/transfer
