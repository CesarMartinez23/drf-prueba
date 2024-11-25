# API CRUD

## License

This project is licensed under the MIT License.

## Prerequisites

- Python 3.x
- Django
- Django REST framework

## Installation

1. Create a virtual environment:
   ```sh
   python -m virtualenv virtualenv
   ```
2. Activate the virtual environment:
   - On Windows:
     ```sh
     .\env\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source env/bin/activate
     ```
3. Install the dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Create the migrations:

   ```sh
   python manage.py makemigrations
   ```

2. Apply the migrations:
   ```sh
   python manage.py migrate
   ```
3. Start the development server:
   ```sh
   python manage.py runserver
   ```
4. Open your browser and navigate to `http://localhost:8000`.

## Running Tests

1. Run project:
   ```sh
   python manage.py runserver
   ```
