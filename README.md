# RPF.banking.project
# Diploma project: Creation of Server, Website, and Design for a Bank

## Project Overview
The primary objective of this diploma project is to design and implement a bank server, website, and user interface that ensure optimal performance, security, and user experience. This project encapsulates both the back-end and front-end aspects, ensuring a cohesive integration of all components.

## Key Components
1. **Server Configuration**:
    - Setup of a secure and robust server architecture to handle banking operations.
    - Implementation of security protocols to safeguard sensitive data.

2. **Website Development**:
    - Development of a responsive and user-friendly website for bank customers.
    - Integration of essential features such as account management, transaction history, and customer support.

3. **Design and User Interface**:
    - Creation of an intuitive and aesthetically pleasing user interface.
    - Ensuring accessibility and ease of use for all users.

## Team Members
- **System Administrator**: Nikononok Dmytro
    - Responsible for server setup, security, and maintenance.
    - Tools used: Docker, Nginx, Certbot, AWS.

## Installation and Setup
1. **Clone the repository from Docker Hub**:
    ```Nginx
    docker pull ilunoi/rpf.banking.nginx:latest
    docker pull ilunoi/rpf.banking.certbot:latest
    ```

2. **Run the Dockerfiles**:
    ```Nginx
    docker run -d --name rpfbanking-nginx -p 80:80 -p 443:443 ilunoi/rpf.banking.nginx:latest
    docker run -d --name rpfbanking-certbot ilunoi/rpf.banking.certbot:latest
    ```

## Contact Information
For any questions or support, please contact:
- **System Administrator**: dnikonenok@gmail.com

## Acknowledgements
Special thanks to our mentors for their guidance and support throughout this project.
