# BFF Pattern Example

This repository is a simple example of using the **BFF (Backend for Frontend)** pattern and **sharing TypeScript types** between the backend and frontend.

## Project Structure

- **shared/** - Contains shared TypeScript types used across the application
- **bff/** - Backend for Frontend layer that sits between the frontend and backend services
- **frontend/** - Frontend application that renders data received from the BFF layer

## Getting Started

Follow these steps to set up and run the project:

### Clone and Setup

```bash
# Clone the repository
git clone git@github.com:KaraniAbdellah/BFF-Pattern-Example.git

# Navigate to project directory
cd BFF-Pattern-Example

# Install BFF dependencies
cd bff
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### Running the Application

**Run the Frontend:**
```bash
cd frontend
npm run dev
```

**Run the BFF (Backend):**
```bash
cd bff
nodemon index.ts
```

## Built With

Connect with me on [LinkedIn](https://www.linkedin.com/in/abdellah-karani-965928294/)

---

**Note:** Make sure you have Node.js and npm installed on your machine before running the setup commands.
