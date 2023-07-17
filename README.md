# chat-app
 Realtime chat application built using Nodejs, Sockets.io, React and HarperDB.

 #Running the application
 1. Client
    
    i. npm install
    
    ii. npm start
 3. Server
    
    i. npm install
    
    ii. npm run dev

#Setting up the DB
1. Create an account at HarperDB (https://studio.harperdb.io/)
2. Create a DB instance on AWS free tier

<img width="487" alt="Screenshot 2023-07-18 011152" src="https://github.com/Mahesh-11/chat-app/assets/60313321/c2ea52e0-2929-4b6f-9180-5c1783c6f631">

<img width="601" alt="Screenshot 2023-07-18 011323" src="https://github.com/Mahesh-11/chat-app/assets/60313321/1bea48cf-2605-42d4-9aac-1e212876c9df">

3. When the instance is ready click on it and create a Schema with name: "realtime_chat_app"
4. And then create a table in it with name: "messages"


#env file
1. create a file in server folder with name: ".env"
2. copy Instance URL and Instance API Auth from harperDB instance
   
<img width="817" alt="Screenshot 2023-07-18 011541" src="https://github.com/Mahesh-11/chat-app/assets/60313321/9334431a-c1a5-4222-90e1-4d2916991a01">

4. In ".env" file add following content:
   
   HARPERDB_URL="<your_instance_URL?"
   HARPERDB_PW="Basic <your_instance_API_Auth_Header>"
   
6. and save the file

That's it now the app is ready

