# MVC Architecture App

This repository demonstrates a basic implementation of the MVC architecture pattern in a Node.js application. The app separates concerns by structuring code into three main components: Models, Views, and Controllers, to facilitate scalability and maintainability.

## Features

- **Separation of Concerns**: The app organizes code into Models (data), Views (UI), and Controllers (logic) for a clean structure.
- **Dynamic Routing**: Uses Express.js to handle routing, separating logic from view rendering.
- **Data Persistence**: Interacts with a database to store and manage data.
  
## Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS for templating, HTML, CSS
- **Database**: Any SQL or NoSQL database (can be configured)

## Project Structure

```
- controllers/   # Handles app logic
- models/        # Database models
- routes/        # API endpoints
- views/         # EJS templates for rendering UI
- utils/         # Helper functions and middleware
- server.js      # Main entry point for the application
```

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/shaeebali/mvc-architecture.git
cd mvc-architecture
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
Create a `.env` file for database credentials and other configurations:
```bash
DB_URL=<your_database_url>
PORT=3000
SECRET_KEY=<your_secret_key>
```

### 4. Run the application
```bash
node server.js
```

Visit `http://localhost:3000` to access the app.

## License

This project is licensed under the MIT License.
