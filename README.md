# WordPress Docker Compose Setup

This repository provides a simple setup for running **WordPress** with **MySQL** using **Docker Compose**. By default, the WordPress site will be accessible at `http://localhost:8080`.

## Prerequisites

Before starting, ensure you have the following installed:

- **Docker**: [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Project Structure

The project contains a `docker-compose.yml` file that defines the services needed for WordPress and MySQL. The key components are:

- **WordPress** (uses the official WordPress Docker image)
- **MySQL** (uses the official MySQL 5.7 image)

Both services are configured to use persistent volumes, so your data remains intact even if containers are stopped or recreated.

## Steps to Set Up

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/wordpress-docker-compose.git
cd wordpress-docker-compose
