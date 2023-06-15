# NodeReactGitTest
React Node APP bez poveznice na bazu podataka
Lokalno okruženje 


BackEnd  server direktorij
Node + Express server as an API
-PORT : 1001
-Link : http://localhost:1001/api
      : http://192.168.0.200:1001/api
        -Pokretanje  : node server/index.js

POVEZNICA IZMEĐU Node I React // PROXY
"proxy": "http://localhost:1001",

FrontEnd client directorij
React + Bootstrap

Setup PORTA za aplikaciju
Create a .env file set port PORT=1000
-PORT : 1000
-Link : http://localhost:1000
      : http://localhost:1000/api
      : http://192.168.0.200:1000
      : http://192.168.0.200:1000/api
        - cd client && npm start
        
        
