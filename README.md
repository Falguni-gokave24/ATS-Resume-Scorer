Resume ATS Scorer
This project is a mini Resume ATS (Applicant Tracking System) Scorer created to demonstrate how resumes can be evaluated against job descriptions using machine learning and NLP techniques. The system calculates an ATS compatibility score and identifies missing skills required for a job role.
The project includes a Jupyter Notebook for backend logic and model processing and HTML files for frontend interaction and integration testing.

Files in the Repository
ATS_Resume_Scorer.ipynb-
This Jupyter Notebook contains the core machine learning and ATS logic.
Implements text comparison between resume and job description
Uses TF-IDF for text vectorization
Uses cosine similarity to calculate ATS score
Identifies missing skills from the resume
Includes Flask API code to allow frontend integration

index.html
This file is the main frontend interface.
Allows users to paste resume text and job description
Sends data to the backend using JavaScript fetch API
Displays ATS score and missing skills
Designed with a clean and attractive UI

Connection.html
This file is used to test and demonstrate the connection between frontend and backend.
Verifies API communication
Helps validate data flow between HTML and Flask backend

Flask Integration Cell
This file/document contains the Flask integration logic used to expose the machine learning model as an API endpoint. It helps in connecting the Jupyter Notebook backend with the frontend interface.

README.md
Project documentation explaining the structure, working, and integration.

Frontend and Backend Integration
The integration is achieved using a REST API approach.
User enters resume text and job description in the HTML frontend.
Frontend sends a POST request to the Flask API.
Flask API runs inside the Jupyter Notebook.
Machine learning logic processes the input data.
ATS score and missing skills are returned as a JSON response.
Frontend displays the result to the user.

Technologies Used
Python
Scikit-learn
Flask
Machine Learning & NLP
HTML, CSS, JavaScript

Output
ATS Score (0–100)
List of Missing Skills

Project Objective
The objective of this project is to understand how ATS systems work and to apply machine learning techniques to a real-world recruitment problem. It also demonstrates frontend-backend integration using Flask APIs.
