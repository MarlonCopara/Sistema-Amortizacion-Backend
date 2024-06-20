# Amortization API

This project is a Django-based API for managing amortization schedules.

## Setup Instructions

Follow these steps to set up and run the backend server.

1. **Clone the Repository**: Clone the repository to your local machine and navigate to the project directory.
    ```bash
    git clone <repository-url>
    cd amortizacion-api
    ```

2. **Create a Virtual Environment**: Create a virtual environment to isolate the project's dependencies.
    ```bash
    python -m virtualenv venv
    ```

3. **Activate the Virtual Environment**: Activate the virtual environment.
    
    For Linux/MacOS:
    ```bash
    source venv/bin/activate
    ```

    For Windows:
    ```bash
    venv\Scripts\activate
    ```

4. **Install Dependencies**: Install the required dependencies specified in the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

5. **Apply Migrations**: Apply the database migrations to set up the database schema.
    ```bash
    python manage.py migrate
    ```

6. **Run the Server**: Start the Django development server.
    ```bash
    python manage.py runserver
    ```

### Accessing the API

Once the server is running, you can access the API at `http://127.0.0.1:8000`.

## Additional Information

- Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
- If you encounter any issues, please check the Django documentation at [docs.djangoproject.com](https://docs.djangoproject.com/).
