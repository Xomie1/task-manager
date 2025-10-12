# Task Manager App

A clean full-stack task management application built with **React**, **Node.js**, **MongoDB**, and **Docker**.

## Features

- Create tasks with a title and description  
- View all tasks in a simple, responsive interface  
- Mark tasks as done or undone  
- Delete tasks instantly  
- Fully containerized for easy deployment  

## Tech Stack

- **Frontend:** React 18  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  
- **Containerization:** Docker & Docker Compose  

## Setup Instructions

### Prerequisites
- Docker and Docker Compose installed  
- Node.js 18+ (only required for local development)

### Option 1: Run with Docker (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/<xomie1>/task-manager.git
   cd task-manager

2. Start all services:
   docker-compose up --build

3. Access the application:
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5001
   - MongoDB: localhost:27017

4. Stop all services:
   ```bash
   docker-compose down
## Development Notes
   - Used Docker for a consistent, isolated environment
   - Implemented basic CRUD operations without authentication
   - Focused on core functionality over design polish
   - Added simple error handling for stability

## Time Spent
Total: ~1 hour 30 minutes
   - Backend API: 30 minutes
   - Frontend integration: 30 minutes
   - Docker setup and testing: 30 minutes


