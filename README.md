# INDIGO-Hack-to-Hire-2024

# Flight Status and Notifications System

## Description
A system to provide real-time flight status updates and notifications to passengers.

## Features
- Real-time flight status updates
- Push notifications via SMS, email, or app
- Integration with mock airport data

## Tech Stack
- Frontend: React.js
- Backend: Flask (Python)
- Database: MongoDB
- Notifications: Kafka, Firebase Cloud Messaging

## Setup
1. **Frontend**:
    ```bash
    cd flight-status-app
    npm install
    npm start
    ```

2. **Backend**:
    ```bash
    cd backend
    source venv/bin/activate
    pip install -r requirements.txt
    python app.py
    ```

## Usage
- Visit `http://localhost:3000` for the frontend.
- Backend API available at `http://localhost:5000/api/flights`.

## Additional Libraries Used
- `axios` for API requests in React.
- `pymongo` for MongoDB interaction in Flask.
- `kafka-python` for Kafka integration.
- `pyfcm` for Firebase Cloud Messaging.
