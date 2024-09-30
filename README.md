# Flask-App-Docker-Deployment

## Overview

This project is a **static web page** created using **Flask**, primarily for demonstration and deployment via **Docker**. The app doesn't involve any interactive functionality but serves as a basic example of how to deploy a Flask app using Docker.

## Technologies Used

- **Flask**: Python web framework.
- **Docker**: Containerization platform for easy deployment.

## Installation and Setup

To set up and run this static web page locally or in a Docker container, follow the steps below.

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/Flask-App-Docker-Deployment.git
```

### 2. Navigate to the project directory:

```bash
cd Flask-App-Docker-Deployment
```

### 3. Build and run the Docker container:

Make sure you have Docker installed on your system.

- Build the Docker image:

  ```bash
  docker build -t flask-app .
  ```

- Run the Docker container:

  ```bash
  docker run -p 5000:5000 flask-app
  ```

### 4. Access the web page:

After the container is running, open a web browser and navigate to:

```
http://localhost:5000
```

This will display the static page hosted by the Flask app.

## Project Structure

```
├── app.py                 # Main application file
├── Dockerfile             # Docker configuration file
├── requirements.txt       # Python dependencies
├── templates/             # HTML templates for the static page
└── README.md              # Project documentation
```

