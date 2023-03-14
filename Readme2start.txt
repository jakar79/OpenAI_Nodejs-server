
$ mkdir openai_api_srv
$ npm init -y
$ npm install dotenv express openai

For Testing:

Start the server: 
$ node index.js

and write:

$ curl -X POST \
    http://localhost:5000/ask \
    -H 'Content-Type: application/json' \
    -d '{ "prompt": "Question?" }'
  
Remplace Question with what you want.
