# Book Rating App

A simple and elegant Flask web application for tracking your personal library and rating books.

## Features
*   **Add Books:** Easily add books with their title, author, and a personal rating (0-10).
*   **View Library:** Browse your collection in a clean, dark-mode interface with card layouts.
*   **Star Ratings:** Visual rating badges for quick assessment.
*   **Persistent Storage:** Uses SQLite and SQLAlchemy to save your collection.
*   **Modern UI:** Responsive design with smooth hover effects, custom typography, and a polished aesthetic.

## Tech Stack
*   **Backend:** Python, Flask, SQLAlchemy
*   **Database:** SQLite
*   **Frontend:** HTML5, Vanilla CSS3 (Custom Design System)

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AbhijaySinghPanwar/Book_Rating.git
    cd Book_Rating
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv .venv
    # Windows
    .venv\Scripts\activate
    # Mac/Linux
    source .venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    python main.py
    ```

5.  **Access the app:**
    Open your web browser and go to `http://127.0.0.1:5000`

## Project Structure
*   `main.py`: Core application logic and database models.
*   `templates/`: HTML templates for the user interface.
*   `static/style.css`: Custom stylesheet for the dark-mode theme.
*   `instance/`: Stores the SQLite database file (`books-collection.db`).
*   `requirements.txt`: Python package dependencies.
