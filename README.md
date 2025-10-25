# Todo App

A task management application built with Next.js and PostgreSQL.

## 🚀 Technologies

- **Frontend**: Next.js 16, React 19, TypeScript
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL 15.3
- **Styling**: Tailwind CSS
- **Containers**: Docker & Docker Compose

## 📋 Prerequisites

Before starting, make sure you have installed:

- [Node.js](https://nodejs.org/) (version 18 or higher)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🛠️ Installation and Setup

### 1. Clone the repository

```bash
git clone <repository-url>
cd todo-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the database with Docker

Start the PostgreSQL database:

```bash
docker-compose up -d
```

This will start a PostgreSQL container with the following configuration:
- **Port**: 5432
- **User**: postgres
- **Password**: postgres
- **Database**: todo_app

# todo-mcp
