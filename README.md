**Hava Havai Backend Assignment**
This project is a backend service that provides detailed information about airports based on their IATA code. The service uses SQLite as the database and Sequelize as the ORM (Object Relational Mapping) tool to interact with the database using JavaScript. The project is deployed on Render and can be accessed at the following URL:https://hava-havai-backend-assignment-36vs.onrender.com


#Features

-Retrieve airport details including related city and country information using a single query.

-Seamlessly handle cases where the country data might not be available.

-Provide a structured JSON response.

#Technologies Used
-Node.js: JavaScript runtime environment.

-Express: Web framework for Node.js.

-SQLite: Lightweight, disk-based database.

-Sequelize: Promise-based ORM for Node.js.

-Render: Cloud platform for deploying the application.

***API Endpoint***
-Get Airport Details
*** URL: /airport/:iata_code ***

(https://hava-havai-backend-assignment-36vs.onrender.com/airport/:iata_code)

-Method: GET
-URL Parameters:
*iata_code (string): The IATA code of the airport.

**Installation**
-Clone the repository:git clone https://github.com/SamratS10/hava-havai-backend.git

**Install dependencies**
-npm install

**Run Application** 
-npm start 

#Deployment
The project is deployed on Render. You can access the live service at the following URL:https://hava-havai-backend-assignment-36vs.onrender.com
