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
      
#Git
Git terminal
Kreiranje Git repozitorija iz postojećeg koda/projekta u lokalnom okruženju

$ cd /path/to/my/codebase
$ git init      (1)
$ git add .     (2)
$ git commit    (3)
Create a /path/to/my/codebase/.git directory.
Add all existing files to the index.
Record the pristine state as the first commit in the history.

Transfer/push  Git --> Github 

GitHub

Kreiranje repozitorija na Github
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
NPR. https://github.com/talebih/NodeReactTest.git

Upload repouzitorija na Github // Git Bash terminal
git remote add origin https://github.com/talebih/NodeReactTest.git
git branch -M main
git push -u origin main
        
        
