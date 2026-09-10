# Calorie Catcher

## What It Does

Calorie Catcher is a web app that helps users track food, calories, exercise, sleep, and wellness progress.

### Main Features

- Create an account and log in securely.
- Add meals and analyze food images with AI.
- Track daily calories, activities, and sleep.
- View meal history and calorie trends.
- Manage calorie debt and complete assigned penalties.
- Chat with an AI health assistant.

## Built With

- **Frontend:** React, Tailwind CSS, Recharts
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Services:** Google Gemini and Cloudinary

## Run the Project

### Requirements

- Node.js and npm
- MongoDB
- Google Gemini API key
- Cloudinary account

### 1. Install dependencies

```bash
cd Backend && npm install
cd ../frontend && npm install
```

### 2. Start the app

Run the backend and frontend in separate terminals:

```bash
cd Backend && node server.js
```

```bash
cd frontend && npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Project Folders

- `Backend/` - API, database models, authentication, and services.
- `frontend/` - React pages, components, and styles.
