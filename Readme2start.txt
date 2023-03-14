
1- $ mkdir openai_api_srv
2- $ npm init -y
3- $ npm install dotenv express openai

4- creat .env file in root directory

5- For Testing:
    Start the server: 
$ node index.js

and write cmd:

$ curl -X POST \
    http://localhost:5000/ask \
    -H 'Content-Type: application/json' \
    -d '{ "prompt": "Question?" }'
  
Remplace Question with what you want.
