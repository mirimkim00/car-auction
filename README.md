# Car-Auction  

## Introduction
The Car Auction project is a microservices-based application developed using .NET and Docker. It provides an online auction service designed for both sellers and buyers, ensuring a secure and efficient environment.

## Features
-  **Microservices Architecture**: Designed and implemented using a microservices architecture with .NET Core, enabling service separation and scalability.
- **Containerization with Docker**: Utilized Docker to containerize microservices for seamless deployment.
-   **Secure User Authentication**: Integrated ASP.NET Identity for secure authentication with role-based access control.
-   **RESTful APIs**: Designed and implemented RESTful APIs to enable communication between microservices and the frontend.
-   **Database Management**: Managed data using PostgreSQL and MongoDB with Entity Framework Core, supporting migrations and efficient querying.

-   **Frontend Integration**: Implemented a responsive frontend with Next.js and React, ensuring smooth interaction with backend services.

## Installation and Usage

### Installation

1.  Clone the repository:

```bash

git clone git@github.com:mirimkim00/car-auction.git

```

2.  Navigate to the project directory:

```bash

cd car-auction

```

3. Docker Setup:

Ensure Docker is installed on your machine.

If Docker is not installed, please go to this [link](https://docs.docker.com/desktop/) and download the version suitable for your operating system

  

4. Build the Docker images for each service by running:

```bash

docker-compose build

```

5. Run the services:

```

docker compose up -d

```

  

### Running the Project

4.  Navigate to the web-app directory:

```bash

cd frontend/web-app

```

5.  Run the project:

```bash

npm run dev

```