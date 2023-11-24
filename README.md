# NodeJS Project Structure

When starting a new project in JavaScript/NodeJS, one of the biggest challenges can be structuring it based on best practices. Given the multitude of approaches available, I created this repository to encapsulate these practices, aiming to provide a starting point for anyone embarking on a NodeJS project.

## Overview

This repository doesn't claim to offer an optimal solution, as every project has its unique requirements. Instead, it serves as a reference point for individuals struggling to kickstart their NodeJS projects.

### Implemented Best Practices

This repository incorporates several best practices, including:

- `async` & `await` support
- WinstonJS logger implementation
- Error Handling
- Sequelize Support
- Basic Joi Validation
- Open API specification through swagger-jsdocs and swagger-ui
- JWT implementation
- Configuration management using environment variables in a `.env` file
- Object-Oriented Programming (OOP)
- Following [airbnb JavaScript style guide](https://github.com/airbnb/javascript) with eslint

### How to Start the Project

To begin using this project:

1. Clone the repository: `git clone https://github.com/zahidhasann88/NodeJs-backend-structure.git`
2. Ensure you have Node version 8.11.0 installed or use nvm to manage your Node versions.
3. Delete the existing `package.lock.json` and run `npm install`.
4. Create a PostgreSQL database named `iLrn` with the following credentials:
   ```bash
   username: postgres
   password: password
