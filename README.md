Description

This repository contains a Docker Compose configuration for setting up a PostgreSQL database and pgAdmin for database administration.

Prerequisites

Docker
Docker Compose

Installation

Clone this repository to your local machine.
Make sure you have Docker and Docker Compose installed.
Navigate to the directory where the docker-compose.yml file is located.

Starting Services

To start the PostgreSQL database and pgAdmin, run the following command:

$ docker-compose up -d

Connection

Server Name: Any name.
Host: "postgres", you can change it in docker-compose file.
Port: 5432.
Maintenance DB: "mydatabase".
Username: "cycler11".
Password: "Hu74n!kdm".
