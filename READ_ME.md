To run this project, one should:

1. npm init
2. install the necessary modules such as: express, cors, mongoose, jsonwebtoken, graphql, express-graphql, dotenv, and bcryptjs for the backend
3. install the necessary modules such as: axios, bootstrap, react, react-router-dom
4. make sure package.json file(s) correctly define the "start" script (should be "nodemon server.js" for the backend)
5. In terminal, cd into backend and npm start. If this returns an error saying that port 8000 is in use, run the command "npx kill-port 8000" and re-run npm start.
6. In a new terminal, cd into frontend/react-jwt-auth and npm start. If this returns an error saying that port 3000 is in use, run the command "npx kill-port 3000" and re-run npm start.
7. The application will now open in broweser on localhost:3000. For admin use, please login with credentials:
    username: admin
    password: key
8. When adding a new car under the Admin Board section, please input at least make and model. Adding cars works in real time, and to see it update in an open browser window, please select a make and then when going to select a different make, the new car will be there at the bottom. This is because the details page updates the dropdowns on change for each dropdown.