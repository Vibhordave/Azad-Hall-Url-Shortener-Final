# Setup Environment

1. Create a Virtual Environment:

### `python -m venv venv`

2. Activate the Virtual Environment:
   On Windows:

### `.\venv\Scripts\activate`

    On Unix or MacOS:

### `source venv/bin/activate`

# Download Requirements

Install the required Python packages using the following command:

### `pip install -r requirements.txt`

# Set Environment Variables

Before running the Flask application, set the following environment variables:

### `export FLASK_APP=app.py`

### `export FLASK_ENV=development`

FLASK_APP: Specifies the entry point of the application.
FLASK_ENV: Sets the development environment for debugging.

# Run the flask application

### `flask run`
