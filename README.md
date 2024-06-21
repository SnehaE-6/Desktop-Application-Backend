# Desktop-Application-Backend
## Backend Server Features:
### Express Server:
Built with TypeScript.
Stores submissions in a JSON file (db.json).

### Endpoints:
/ping: A GET request that returns True, ensuring the server is running.
/submit: A POST request that accepts parameters name, email, phone, github_link, and stopwatch_time to save a new submission.
/read: A GET request with a query parameter index to retrieve the (index+1)th form submission.

### Database Structure (db.json):
Structured to store an array of submission objects with fields for name, email, phone, GitHub link, and stopwatch time.

### Backend Server:
### Prerequisites:
Node.js and npm installed.
TypeScript installed globally (npm install -g typescript).

### Steps to Run:
Clone the repository from GitHub.
Navigate to the project directory.
Install dependencies using npm install.
Start the server using npm run start.
The server will be running locally, and you can test the endpoints using tools like Postman.

### GitHub Repositories:
Desktop Application: https://github.com/SnehaE-6/Desktop-Application.git
