# Fitness Workout Tracker

This project involves creating a backend system for a workout tracker application where users can sign up, log in, create workout plans, and track their progress. The system will feature JWT authentication, CRUD operations for workouts, and generate reports on past workouts.

## Table of Contents

- [Project Name](#project-name)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
    - [Requirements](#requirements)
    - [Constraints](#constraints)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Running the Tests](#running-the-tests)
  - [Deployment](#deployment)
  - [Built With](#built-with)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## About

Project based on the [fitness-workout-tracker challenge](https://roadmap.sh/projects/fitness-workout-tracker) from roadmap.sh

Intented to be a learning intermediate project.

### Requirements
You are required to develop an API for a workout tracker application that allows users to manage their workouts and track their progress. Your first task is to think about the database schema and the API endpoints that will be needed to support the application’s functionality. Here are some of the key features you should consider:

#### Exercise Data
You should write a data seeder to populate the database with a list of exercises. Each exercise should have a name, description, and category (e.g., cardio, strength, flexibility) or muscle group (e.g., chest, back, legs). Exercises will be used to create workout plans.

#### User Authentication and Authorization
Users will be able to sign up, log in, and log out of the application. You should use JWTs for authentication and authorization. Only authenticated users should be able to create, update, and delete workout plans. Needless to say, users should only be able to access their own workout plans.

- Sign-Up: Allow users to create an account.
- Login: Allow users to log in to their account.
- JWT: Use JSON Web Tokens for authentication.

#### Workout Management
Users will be able to create their workout plans. Workout plans should consist of multiple exercises, each with a set number of repetitions, sets, and weights. Users should be able to update and delete their workout plans. Additionally, users should be able to schedule workouts for specific dates and times.

- Create Workout: Allow users to create workouts composed of multiple exercises.
- Update Workout: Allow users to update workouts and add comments.
- Delete Workout: Allow users to delete workouts.
- Schedule Workouts: Allow users to schedule workouts for specific dates and times.
- List Workouts: List active or pending workouts sorted by date and time.
- Generate Reports: Generate reports on past workouts and progress.

### Constraints
You are free to choose the programming language and database of your choice. Actual decisions for the database schema, API endpoints, and other implementation details are up to you. However, you should consider the following constraints:

- Database: Use a relational database to store user data, workout plans, and exercise data.
- API: Develop a RESTful API to interact with the database.
- Security: Implement JWT authentication to secure the API endpoints.
- Testing: Write unit tests to ensure the correctness of your code.
- Documentation: Learn about OpenAPI Specs. Document your API endpoints and provide examples of how to use them.

## Getting Started

Instructions on how to set up the project locally.

### Prerequisites

List of software and tools needed before installing the project.

```bash
# Example
node >= 22.14.0
npm >= 10.9.2
```

### Installation

Step-by-step guide on how to install the project.

```bash
# Clone the repository
git clone https://github.com/yourusername/fitness-workout-tracker.git

# Navigate to the project directory
cd fitness-workout-tracker

# Install dependencies
npm install
```

## Usage

Instructions on how to use the project.

```bash
# Start the development server
npm start
```

## Running the Tests

Instructions on how to run the tests for the project.

```bash
# Run all tests
npm test
```

## Deployment

Instructions on how to deploy the project to a live system.

## Built With

List of technologies used in the project.

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [SQLite](https://www.sqlite.org/)

## Contributing

Guidelines for contributing to the project.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request


## Authors

List of authors and contributors to the project.

- **Francisco Llamosas Baptista ** - *Initial work* - [chicobaptista](https://github.com/chicobaptista)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Credits and acknowledgments for third-party resources and inspirations.

- [roadmap.sh](https://roadmap.sh/)