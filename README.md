

1  
Make an express server 
- npm init
to create package.json
we can change main in it and scripts in it


2 install dependencies 
    npm i 
    bcryptjs
    cloudinary
    cookie parser 
    cors 
    dotenvexpress 
    jsonwebtoken 
    mongoose 
    multer
    nodemon

3 package.json contains all dependencies so 
    we make a git.ignore to not push node_ modules file on git

4 Making a server entry point 
    server.js
    and change main name in package.json to server.js

5 Make a db mongo 
    Make a cluster 
    name it 
    add username pass
    mongodb+srv://swagblower:qwerty123@clustershoebox.r5mgjbb.mongodb.net/

6 Connect Mongo DB to the server
    import express , mongoose , cookie-parser , cors

    Make an App using express
    Make a port : 5000



7 Make the front end folder using
    npm create vite@latest
    choose React 
    Choose js
    Name the project 
    Go to folder created 
    npm i install all the required dependencies
    run it then 

8 Come to Server file (28 min )
    in package.json add a dev with nodemone and file name 
    then run it using 
            node run dev
            also remove exit file if it donot works
    if it runns properly it will show all the logs and also the dB connection 


we created an express server configured cors and connect mongo db to express server

9 Now install clinet side packages
    npm i @reduxjs/toolkit react-redux axios react-router-dom 
    
    go to shadcn ui .com in vite
    install tailwind from there
    add import to css of tailwind 
    add tailwind plugin to vite config

10  npm install tailwindcss @tailwindcss/vite
    add in vit.json 
        import tailwindcss from '@tailwindcss/vite'
        import path from "path"   and more
    add in index.css @import "tailwindcss";
    make a jsconfig.json 
    npm install -D @types/node
    npx shadcn@latest init
    npx shadcn@latest add button

    install tawilwind 
    install shadcnui tailwind

11 AT 44.50 in vedio
Client > src > component > auth > layout.jx
From here we can change the auth layout function.

app.jx for dashbaord editing




