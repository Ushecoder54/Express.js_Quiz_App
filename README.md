# Quiz App Backend (Express.js)

Welcome to the Quiz App Backend! This is a simple Express.js application that serves as the backend for a quiz game. It provides an API to fetch random quiz questions.

## Features

- Retrieve a random quiz question via API.
- Store and retrieve questions from a SQLite database.
- Serve static files (if applicable).

## Getting Started

Follow these instructions to set up and run the Express.js quiz app backend on your local machine.

### Prerequisites

- Node.js (version x.x.x)
- npm (Node Package Manager)
- SQLite (for database)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd quiz-app-backend
   ```

2. Install dependencies:
   npm install

3. Create a SQLite database (quiz.db) with appropriate schema and questions data.

4. Start the server:
   node app.js
   The server will be accessible at http://localhost:3000.

5. Use the API endpoint to fetch quiz questions. For example:
   Get a random question:
   GET http://localhost:3000/get_question
