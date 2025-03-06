# smart-home-energy
This project, "smart-home-energy," provides a basic framework for monitoring and managing energy consumption in a smart home environment. It uses a FastAPI backend to handle data storage and retrieval, and a React frontend to visualize energy usage and set budgets.  
This repository contains a basic smart home energy monitoring system built with FastAPI and React. It provides a foundation for tracking and managing energy consumption in a smart home environment.

## Features

* **Backend (FastAPI):**
    * Stores and retrieves energy consumption data.
    * Provides API endpoints for data access and manipulation.
    * Uses SQLite for data storage.
* **Frontend (React):**
    * Visualizes energy consumption data using charts.
    * Allows users to set and view energy budgets.
    * Fetches data from the backend API.

## Project Structure

smart-home-energy/
├── backend/
│   ├── main.py       # FastAPI application
│   ├── database.py   # Database interactions
│   └── ...
└── frontend/
├── src/
│   ├── components/
│   │   ├── EnergyChart.js
│   │   └── Budget.js
│   ├── App.js
