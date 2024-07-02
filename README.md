# Netflix Clone

A Netflix clone application built with Spring Boot for the backend and React for the frontend.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- User authentication and authorization
- Browse movies and TV shows
- Watch trailers
- Add movies to favorites
- Search functionality

## Tech Stack

- **Frontend**: React, Redux, CSS, HTML
- **Backend**: Spring Boot, Spring Security, JPA, Mongodb
- **Others**: Maven, npm, Docker

## Prerequisites

- Java 11 or higher
- Maven
- Docker (optional, for containerization)

## Installation


1. Clone the repository:
   ```bash
   git clone https://github.com/Sabarigirivasan10/project.git
   cd project/backend


## Backend Setup

1. Navigate to the backend directory:

    bash
    cd backend
    

2. Install backend dependencies:

    bash
    npm install
    

3. Create a .env file in the backend directory and add your MongoDB URI and other environment variables:

    env
    PORT=5000
    MONGO_URI=*****
    JWT_SECRET=*****
    

4. Start the backend server:

    bash
    npm start

## Frontend Setup

1. Navigate to the frontend directory:

    bash
    cd frontend
    

2. Install frontend dependencies:

    bash
    npm install
    

3. Create a .env file in the frontend directory and add any necessary environment variables:

    env
    REACT_APP_API_URL=http://localhost:5000/api
    

4. Start the frontend development server:

    bash
    npm start


## Usage

1. Ensure MongoDB is running.
2. Start the backend server.
3. Start the frontend development server.
4. Open your browser and navigate to http://localhost:3000.

