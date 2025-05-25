
# BookStore

BookStore is an application that helps users buy books online. The system provides separate roles for users and administrators, making it suitable for both customers and store managers.

## Features

- User registration and login
- Browse and search for books
- Purchase books
- Admin panel for managing books and orders
- Role-based access (User and Admin)

## Technology Stack

- Java (Backend)
- TypeScript (Frontend)
- [Add frameworks/libraries if known, e.g., Spring Boot, React, etc.]

## Installation

### Prerequisites

- Java 11 or higher
- Node.js and npm (for the frontend)
- Git

### Clone the repository

```bash
git clone https://github.com/it2kvku/BookStore.git
cd BookStore
```

### Backend Setup

1. Navigate to the backend directory (e.g., `cd backend` if you have a specific folder).
2. Build the project:

   ```bash
   ./mvnw clean install
   ```

3. Run the backend server:

   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup

1. Navigate to the frontend directory (e.g., `cd frontend`).
2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the frontend development server:

   ```bash
   npm start
   ```

### Access the Application

- Open your browser and go to `http://localhost:3000` for the frontend.
- Backend API should be running on `http://localhost:8080` (adjust if needed).

## Usage

- Register as a new user or log in with your credentials.
- Browse available books and add them to your cart.
- Administrators can log in and manage books, orders, and users via the admin panel.

## Contributing

Feel free to fork this repository and submit pull requests.




