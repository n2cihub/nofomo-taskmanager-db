# NoFomo Taskmanager DB

Welcome to the database setup for the NoFomo Task Manager. This guide will help you configure a MySQL database container for use with the NoFomo Task Manager app.

## Prerequisites

Ensure you have Docker installed on your machine to run the MySQL container. If Docker is not yet installed, download it from [Docker's official site](https://www.docker.com/get-started).

## Local Setup

Follow these steps to configure your MySQL database for NoFomo Task Manager:

1. **Set Environment Variables**

   Create a `.env` file in your project root, if it does not already exist, and add the following environment variables:

   ```
   MYSQL_ROOT_PASSWORD=<passwordForRootuser>
   ```

2. **Launch the Database**

   Open a terminal and execute the following command to start the MySQL container:

   ```bash
   docker compose up -d
   ```

   This will start the MySQL database in detached mode using the environment settings defined.


For any issues or contributions, please refer to the project's issues page on GitHub.
