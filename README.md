# Desktop-Application-Backend (Backend server.zip file is attached) 
## Backend Server Features:
### Express Server:
Built with TypeScript.

Stores submissions in a JSON file (db.json).

### Database Structure (db.json):
Structured to store an array of submission objects with fields for name, email, phone, GitHub link, and stopwatch time.

### Backend Server:
### Prerequisites:
Node.js and npm installed.

TypeScript installed globally (npm install -g typescript).

### Instructions to Create an Express App with TypeScript
Initialize a New Node.js Project:
Open Visual Studio Code.

Open the terminal in Visual Studio Code.

Navigate to your desired project directory.

Initialize a new Node.js project with npm init -y.

### Install Required Packages:
Install Express and Body-Parser with npm install express body-parser.

Install TypeScript and related types with npm install typescript ts-node @types/node @types/express --save-dev.

### Set Up TypeScript Configuration:
Create a tsconfig.json file in the root directory with the necessary TypeScript configuration.

### Create Project Structure:
Create a folder named src.

Inside src, create an index.ts file.

Create a db.json file in the root directory.

### Implement the Server:
Add code to src/index.ts to set up the Express server and define the endpoints /ping, /submit, /read, /search.

### Set Up the Database:
Initialize db.json with an empty array.

### Update package.json Scripts:
Add a start script to package.json to run the TypeScript server.

### Start the Server:
In the terminal, start the server with npm start.

### Endpoints:
Ensure /ping returns true on a GET request.

Ensure /submit saves a submission to db.json on a POST request.

Ensure /read retrieves a submission from db.json based on the index query parameter on a GET request.

### GitHub Repositories:
Desktop Application: https://github.com/SnehaE-6/Desktop-Application.git
