# Movie_recommendation_system

Overview

This project is an end-to-end Movie Recommendation System, developed as part of a guided project from the CampusX website. The system provides personalized movie recommendations based on user input using machine learning techniques.

Features:

Content-based filtering

Collaborative filtering

Hybrid recommendation approach

Web interface for easy interaction

Deployment-ready

Tech Stack:

Python (for backend and ML model)

Pandas, NumPy, Scikit-learn (for data processing and ML modeling)

Flask (for API and web deployment)

HTML, CSS, JavaScript (for frontend)

Streamlit (optional alternative for web app UI)

Dataset:

The dataset used in this project includes movie details such as:

Movie titles

Genre

Ratings

User reviews

Cast and crew details

Installation & Setup

Clone the Repository : git clone https://github.com/yourusername/Movie_recommendation_system.git
cd Movie_recommendation_system

Create a Virtual Environment : python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install Dependencies : pip install -r requirements.txt

Run the Application

For Flask-based web app : python app.py

For Streamlit-based web app : streamlit run app.py

Usage:

Enter the name of a movie.

Get recommendations based on content similarity or collaborative filtering.

Click on suggested movies for more details.

Deployment:

You can deploy this app using Heroku, Render, or AWS Lambda by following their deployment guides.

Future Improvements:

Enhance the recommendation engine with deep learning models.

Include real-time movie ratings and user reviews.

Deploy using cloud-based services for better scalability.

Credits:

Project guided by CampusX

Dataset sourced from MovieLens / TMDB

