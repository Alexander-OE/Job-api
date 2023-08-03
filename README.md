# Recruitment API

<!--[![View Project](https://img.shields.io/badge/View-Project-blue)](https://github.com/yourusername/recruitment-api)-->

This is a Recruitment API developed using Node.js, Express.js, MongoDB, and Json web Token(JWT). It allows users to efficiently manage the entire recruitment process, from job listings to candidate applications.

## Features
- Register and Login user
- Create, update, and delete job listings.
- Accept and manage candidate applications.
- Limiting the spamming of the API.
- Secure Cross-Origin Requests with CORS support for enhanced data access and user experience.
- Enhanced security with XSS-Clean protection to sanitize user input and thwart potential Cross-Site Scripting (XSS) attacks.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose(For database modelling )
- Json web Token(JWT)
- Dotenv(For environment variable)
- XSS-Clean(prevents cross site scripting)
- CORS(Cross-Origin Resource Sharing)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Alexander-OE/Job-api.git
cd Job-api
```

1. Install dependencies: npm install

2. Set up environment variables:
Copy the .env.example file to .env and update the variables with your configurations.

## Usage

1. Start the server: `npm start`
2. Access the API at: `http://localhost:3000`

## API Endpoints

POST /auth/register - Register the user.

POST /auth/login - Register the user.

POST /jobs - Create a new job listing.

GET /jobs - Retrieve all job listings.

GET /jobs/:id - Retrieve a specific job listing by ID.

PATCH /jobs/:id - Update an existing job listing.

DELETE /jobs/:id - Delete a job listing.
