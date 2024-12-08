# POC OAuth 2.0 


## Prerequisites
1. Install python
2. Install [node.js](https://nodejs.org/en/download/prebuilt-installer)



## OAuth 2.0 config
1. Setup a Google Cloud Console account.
2. Follow [this tutorial](https://www.youtube.com/watch?v=HtJKUQXmtok) to configure an OAuth2.0 client for Google\
   a. Use redirect URI: http://localhost:3000/callback \
   b. Save client id & client secret
   
4. Update client id\
   a. In server/backend.py\
   b. in client/src/App.js
   
6. Update client secret\
a. In server/backend.py


## Install dependencies
1. React 
   >cd client\
   >npm install\
   >npm install axios\
   >npm install web-vitals
2. Flask
   >pip install flask requests flask-cors

## Start the project
1. Server
    >python ./server/backend.py
2. Client
    >cd client\
    >npm start
