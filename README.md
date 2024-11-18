# mutant-nodejs-api

Steps for API test.
1 - Install rest client in vs code.
2 - npm i express.
3 - npm i nodemon -D.
4 - Open new terminal en vs code and execute npm run dev.
5 - Open requests.http file in the Project.
6 - Execute: 
POST http://localhost:3000/mutant HTTP/1.1
Content-Type: application/json

[
  "ATGCGA",
  "CAGTGA",
  "CCAGGA",
  "ATGAGA",
  "CAGTGC",
  "CCCCTA"
]