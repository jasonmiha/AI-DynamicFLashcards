AI Dynamic Flashcards
Overview
The DynamoCards project integrates frontend and backend technologies to efficiently parse and organize lengthy YouTube transcripts, revolutionizing study processes and enhancing digital learning experiences. This project leverages React for the frontend and FastAPI for the backend.

Features:
Google Cloud Integration: Utilizes various Google Cloud services for document processing and embedding.
YouTube Transcript Analysis: Processes YouTube video transcripts to generate study materials.
Dynamic Flashcards: Generates interactive flashcards from processed data.
Cross-Origin Requests: Seamless communication between frontend and backend using CORSMiddleware.
Logging and Verbosity: Configurable logging for enhanced debugging and verbosity control.
Cost Tracking: Calculates billable characters for better cost management.

Prerequisites:
Google Cloud Account: Set up Google Cloud for your projects.
GitHub Repository: Create a GitHub repository and initialize a React app in the frontend and a Python virtual environment in the backend.

Installation:
Clone the Repository:
    bash
    Copy code
    git clone https://github.com/your-repository-url.git
    cd your-repository

Setup Frontend:
    bash
    Copy code
    cd frontend
    npm install
    npm start

Setup Backend:
    bash
    Copy code
    cd backend
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    uvicorn main:app --reload

Project Structure:
frontend: Contains the React application.
App.jsx: Main application file.
components: Contains React components like Flashcard.
backend: Contains the FastAPI application.
main.py: Main application file.
genai.py: Contains the GeminiProcessor class for AI operations.
services: Contains service classes for YouTube processing and other functionalities.

Usage:
Google Cloud Setup: Follow the instructions to create a Google Cloud project and service account.
YouTube Transcript Analysis: Upload a YouTube video link to analyze and generate transcripts.
Dynamic Flashcards: Generate flashcards from the processed transcript data and interact with them via the frontend.