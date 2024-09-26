# get-shit-done

a Todo webapp with frontend/backend separation.

# Setup

Clone the repository.

## Backend

1. Go to backend folder: `cd <get-shit-done-project-dir>/backend`
2. Create a virtual environment and activate it.
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations to create the database:
    ```
    python manage.py makemigrations
    python manage.py migrate
    ```
5. Run the development server and keep it running: `python manage.py runserver`

## Frontend

1. Go to frontend folder: `cd <get-shit-done-project-dir>/frontend`
2. Install dependencies: `npm install`
3. Run the frontend: `npm start`
