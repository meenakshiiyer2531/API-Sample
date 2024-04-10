# CRM API

## Overview
This project is an API built using TypeScript and Node.js with MongoDB as the database. It provides CRUD operations for managing customer data. 

## Drive Link : [CODE](https://drive.google.com/drive/folders/1EI8hBIC-W0krkzeRqgEYS1KLTXfowuTq?usp=sharing)

## Technologies Used
- TypeScript
- Node.js
- MongoDB
- Postman (for API testing)

## Installation
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Set up MongoDB and configure the connection in `src/config/db.ts`.
4. Run `npm run build` to compile TypeScript files into JavaScript.
5. Start the server using `npm start`.

## API Endpoints
- `GET /customers`: Get all customers.
- `GET /customers/:id`: Get a specific customer by ID.
- `POST /customers`: Create a new customer.
- `PUT /customers/:id`: Update a customer by ID.
- `DELETE /customers/:id`: Delete a customer by ID.

## Testing
Testing is done using Postman. You can use the following link to import the Postman collection and test the API endpoints: [Postman Collection](http://localhost:3000/customers)

## Deployment
The project is deployed on Microsoft Azure.

## Contributors
- V MEENAKSHI IYER

## License
This project is licensed under the [MIT License](LICENSE).
