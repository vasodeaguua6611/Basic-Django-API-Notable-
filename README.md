# Notable Django API

## This is a basic Python/Django API project for managing notes. It uses the Django framework and Tastypie for creating RESTful APIs. Basic project i did in like 30 mins.

### Features

- Create, read, update, and delete notes
- RESTful API endpoints
- Simple authorization

### Requirements

- Python 3+
- Django 3.x
- django-tastypie


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/notable-django-api.git
    cd notable-django-api
    ```

2. Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser:

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

### API Endpoints

- `/api/note/` - List and create notes
- `/api/note/<id>/` - Retrieve, update, and delete a note

### Usage

1. Access the admin panel at `http://127.0.0.1:8000/admin/` and log in with the superuser credentials.
2. Use the API endpoints to manage notes.

### Example Request

To create a new note, send a POST request to `/api/note/` with the following JSON payload:

```json
{
    "title": "Sample Note",
    "content": "This is a sample note."
}
```

## This is a very basic API without a lot of value. First attempt as well. Feel free to use/skid/fork/critique. It's all public open source code anyways. Cheers