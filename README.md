# Python File Upload Server with Docker

This is a Python web application for uploading files. It's designed to be containerized using Docker for easy deployment and scalability. Alongside the web server, this setup includes additional services such as MySQL, SonarQube, RabbitMQ, and Nexus, providing a comprehensive environment for development and testing.

## Features

- **File Upload Functionality**: Allows users to upload files through a web interface.
- **Docker Integration**: Ensures consistent and isolated environments for development, testing, and deployment.
- **Service Orchestration with Docker Compose**: Includes MySQL for database management, SonarQube for code quality analysis, RabbitMQ for message queuing, and Nexus for repository management.

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/zLefterov/Python-file-uploader.git
   cd Python-file-uploader
   ```

2. Build and run the application using Docker Compose:

   ```bash
   docker-compose up --build
   ```

### Usage

- Access the file upload interface at `http://localhost:8001`.
- Upload files using the provided form.
- The uploaded files will be saved in the specified directory.

## Components

1. **server.py**: A Python script for a simple HTTP server to handle file uploads.

2. **upload.html**: The frontend HTML file for the file upload interface.

3. **Dockerfile**: Defines the Docker image for the Python web server.

4. **docker-compose.yml**: Orchestrates multiple services including the web server, MySQL, SonarQube, RabbitMQ, and Nexus.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

feel free to contact me https://zlefterov.tech
