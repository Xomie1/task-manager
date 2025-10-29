Task Manager App

A clean full-stack task management application built with React, Node.js, MongoDB, and Docker.

Features

Create tasks with a title and description

View all tasks in a simple, responsive interface

Mark tasks as done or undone

Delete tasks instantly

Fully containerized for easy deployment

Tech Stack

Frontend: React 18

Backend: Node.js + Express

Database: MongoDB

Containerization: Docker & Docker Compose

Setup Instructions
Prerequisites

Docker and Docker Compose installed

Node.js 18+ (only required for local development)

Option 1: Run with Docker (Recommended)

Clone the repository:

git clone https://github.com/<your-username>/task-manager.git
cd task-manager


Start all services:

docker-compose up --build


Access the application:

Frontend: http://localhost:3000

Backend API: http://localhost:5001

MongoDB: localhost:27017

To stop all services:

docker-compose down

Development Notes

Used Docker to simplify environment setup

Implemented essential CRUD operations (no authentication)

Focused on functionality over design polish

Added lightweight error handling for stability

Time Spent

Total: ~1 hour 30 minutes

Backend API: 30 minutes

Frontend integration: 30 minutes

Docker setup and testing: 30 minutes