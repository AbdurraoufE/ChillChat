===================================================
# Getting Started with Create React App
===================================================
# How to run the application

## Make sure you have these installed on your system:
- Yarn 
- Express
- Nodemon
- CORS
- Axios
- Jquery
- React
- React-dom
- React-router-dom

# You need 2 CMDs for this to run as needed, by following these steps:

- In the first CMD (FrontEnd):
    - cd into the client folder (cd Desktop/ChatApp/client/)
    
- On the second CMD (BackEnd):
    - cd into the server folder (cd Desktop/ChatApp/server/)
    
# On both CMDs (Ignore the quotes): 
    - Start the backend by typing 'yarn start', then;
    - Start the frontend by typing 'yarn start'

***If done correctly, __the server side should listen to port 5000 and connect to MySQL__ and creates 5 tables. And __the frontend should listen to port 3000 locally and compile successfully__. All the data should get stored as the user uses the application***

# Features: 

## Allow users to create personal chatrooms
    - Choose a unique channel name
    - Add a limit of members to join the channel
    - Either make it a public or private channel
    - Check the channel details by viewing which members are in it

## Allows users to search for channel
    - The search bar at the top allows you to search for a specific channel made

## Allows users to communicate to eachothers in chats
    - Just like any other messaging application, ChatRoom allows you to message with other accounts

## Allows users to reply to other people in group chats
    - Gives you the option to nest a conversation so it does not get messy

## Allows users to view which memeber has joined the channel, and who left
    - Displays on the screen who joined/left the channel

## Allows the creater of the channel to delete the channel
    - Gives an option to delete a channel (only to the creator)

## Allows users to log out the account 
    - Users can click the logout button at the top right to signout

## Displays the time a message has been sent
    - Shows the current time the message has been sent

## Resquest access to enter a private channel
    - If a channel is private, a user can request access to the owner to get permission to enter

## The admin account can join any channel (private or public)
    - The admin account has access to do anything
    - If a channel is either public or private, access is allowed

## Admin can delete any message/channel
    - If you are logged in the admin account: 
    - You have access to delete any message, on any group chat; or delete the full channel

# DataBase:

## This application uses MySQL which stores all of the information

    > Open MySQL WorkBench
        - Run simple MySQL commands to access the information, such as:
            show databases;
            use chatroom;
            show tables;
            SELECT * FROM channels;
    
            - This displays all the channels made in the system


# More information about the applicaton:

## Backend:
          
    axios
    bcryptjs
    body-parser
    cookie-parser
    cors
    crypto
    dotenv
    express
    http
    jsonwebtoken
    mysql
    nodemon
    socket.io
    util
    uuid


## Frontend:

    @emotion/react
    @emotion/styled
    @mui/icons-material
    @mui/material
    @testing-library/jest-dom
    @testing-library/react
    @testing-library/user-event
    axios
    jquery
    lodash
    material-ui-popup-state
    moment
    react
    react-dom
    react-notifications
    react-router-dom
    react-scripts
    socket.io-client
    web-vitals
