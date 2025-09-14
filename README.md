# WordPress Docker Compose Project

This project allows you to deploy a fully functional WordPress blog with a MySQL database using Docker Compose.

## Prerequisites
- Docker
- Docker Compose

## Setup
1.  Clone this repository.
2.  Create a file named `.env` in the root of the project.
3.  Copy the contents of `.env.example` (or create your own) and fill in the values for the database.
    ```
    MYSQL_ROOT_PASSWORD=your_root_password
    MYSQL_DATABASE=wordpress
    MYSQL_USER=your_user
    MYSQL_PASSWORD=your_user_password
    ```

## How to Run
1.  Run the command: `docker-compose up -d`
2.  Open your browser and navigate to `http://localhost:8080` to complete the WordPress installation.
