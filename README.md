# Book Recommender System

## Overview
The Book Recommender System is a web application that recommends books to users based on their preferences. It leverages machine learning techniques to analyze user data and suggest books that they might like.

## Features
- User-friendly web interface built with Flask
- Machine learning model to recommend books based on user input
- Data persistence using Pickle to save and load the trained model

## Tech Stack
- Python
- Flask
- Scikit-learn
- Pickle

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Prabhnoor2002/Book-Recommender-System.git
   cd book-recommender-system
2. Create a virtual environment:

        python -m venv venv
3. Activate the virtual environment:
         On Windows:
            venv\Scripts\activate
         On macOS/Linux:
            source venv/bin/activate
4. Install the required packages:
       pip install -r requirements.txt
5. Run the application:

      flask run
Project Structure
       book-recommender-system/
    ├── app.py              # Main application file
    ├── templates/
    │   └── index.html      # HTML template for the web interface
    ├── static/
    │   ├── css/
    │   │   └── styles.css  # CSS styles for the web interface
    ├── model/
    │   ├── train.py        # Script to train the machine learning model
    │   └── recommender.pkl # Serialized model file
    ├── data/
    │   └── books.csv       # Dataset of books
    └── requirements.txt    # List of required packages
Train the model:
   Run the train.py script to train the machine learning model:
       python model/train.py

   
       
    
      





   


