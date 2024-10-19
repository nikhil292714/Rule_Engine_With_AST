# Rule_Engine_With_AST


Summary
This Rule Engine Application is designed to evaluate rules based on user-defined conditions. The application utilizes a simple user interface built with React for the frontend, while the backend is powered by Node.js , Express.js and MongoDB. The rules can be created, evaluated, and combined using a robust Abstract Syntax Tree (AST) parsing mechanism.

Features
Create rules using a flexible string-based syntax .
Store rules in a MongoDB database.
Evaluate one or more rules against user-provided data.
Combine multiple rules into a single logical expression.
User-friendly interface with real-time feedback.
Design Choices
Architecture
The application follows a 3-tier architecture:

Frontend (UI): Built with React, allowing users to create and evaluate rules dynamically.
API: A RESTful API developed using Express.js for handling requests related to rule creation, retrieval, evaluation, and combination.
Backend: MongoDB is used for data storage, allowing persistence of user-defined rules.
Rule Evaluation
The rule evaluation is handled through an Abstract Syntax Tree (AST) that represents the logical structure of the rules. The rules are parsed and evaluated using helper functions to ensure the logic is applied correctly.

User Input
User input is validated before being processed to ensure that rules are well-formed. The UI provides feedback in case of errors during rule creation or evaluation.

Build Instructions
Prerequisites
Make sure the following are installed:

Node.js (v14 or later)
npm (Node package manager)
MongoDB (running instance)
Dependencies
Backend
Express: Fast web framework for Node.js.
Mongoose: MongoDB object modeling for Node.js.
body-parser: Middleware to handle JSON request bodies.
cors: Middleware to enable CORS.
Frontend
React: JavaScript library for building user interfaces.
axios: Promise-based HTTP client for making requests.
There are package.json files in the frontend folder as well as in the backend folder .You can go the respective directories(frontend , backend) and type "npm install" in the terminal to install all the required dependencies.

Steps to run
1. Go to the backend directory in the terminal and type "npm install" to install the required dependencies for the backend.
2. In the same terminal , type "npm run dev" to start the server.
3. Open a new terminal,Go to the frontend directory in the terminal and type "npm install" to install the required dependencies for the frontend.
4. In the same terminal , type "npm start" to start the server.
5. Now the webpage opens.We can create , combine and evaluate rules using AST (Abstract Syntax Tree).
