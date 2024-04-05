Zoom Clone Application
# Plan of Action

Initialize our NodeJS Project - DONE
Initialize our first view - DONE
Create a room id - DONE
Add the ability to view our own video
Add styling
Add mute button
Add Stop video button


Steps:
Add .gitignore and mention node_modules in it
npm init
This will add package.json file
npm install express
The express module will be added to dependencies inside package.json
npm install nodemon -g
The nodemon module will be added to dependencies inside package.json
Create server.js 
Create a views folder and create room view - room.ejs
Render the view room from server.js
Install ejs - npm install ejs
Add view engine as ejs inside server.js
Rerun the project
Install uuid - npm install uuid (This will generate random ids)
Add uuidv4 in server.js
app.get(‘/’) is changed to generate a id with uuidv4() and redirected to it
app.get(‘/:room’) is for directing to that room id
Check if the room id is accessible inside the ejs file
