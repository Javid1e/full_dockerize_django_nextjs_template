
# Full Dockerize Django Next.js Template

This repository serves as a template for dockerizing a full-stack web application with Django for the backend and Next.js for the frontend. It provides a foundation for building and deploying applications in a containerized environment.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Technologies Used](#technologies-used)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To set up the Docker environment and run the application, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone <repository-url>
   ```

2. Navigate into the project directory:

   ```
   cd full_dockerize_django_nextjs_template
   ```

3. Build and start the Docker containers:

   ```
   docker-compose up --build
   ```

## Usage

The application will be available at `http://localhost:3000` for the frontend and `http://localhost:8000` for the backend.

### Docker Commands

- To stop the containers:

  ```
  docker-compose down
  ```

- To rebuild the containers:

  ```
  docker-compose up --build
  ```

## Technologies Used

- Docker
- Docker Compose
- NGINX
- Django REST Framework
- Next.js

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes. Ensure to follow the existing code style and conventions.

## License

This project is licensed under the [MIT License](LICENSE).
