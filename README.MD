# Stellar Cart

This is a simple Django project with instructions on setting up a virtual environment and installing project dependencies using a `requirements.txt` file.

## Prerequisites
- Python 3.10.12
- pip (Python package installer)

## Setup Instructions

1. **Clone the Repository:**

    ```bash
   git clone https://github.com/your-username/your-django-project.git
   cd your-django-project
    ```
2. **Create and Activate Virtual Environment:**
    #### On Windows
    ```python
    python -m venv venv
    ```
    #### On macOS/Linux
    ```python
    python3 -m venv venv
    ```


3. **Activate the virtual environment**
    #### On Windows
    ```powershell
    venv\Scripts\activate
    ```

    #### On macOS/Linux
    ```bash
    source venv/bin/activate
    ```
4. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5. **Apply Migrations:**
    ```bash
    python manage.py migrate
    ```
6. **Create Superuser (Optional):**
    ```bash
    python manage.py createsuperuser
    ```
7. **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```
8. **Access the Django Admin Interface:**
    Open your browser and go to http://127.0.0.1:8000/admin/.
    Log in with the superuser credentials created earlier.

## Project Structure
- **stellarcart/**: Your Django project directory.
- **shop/**: Your Django app directory.
- **venv/**: Virtual environment directory (ignore in version control).
- **requirements.txt**: List of project dependencies.

## Additional Notes

If you have any questions or need assistance, feel free to contact the project maintainer:

- **Maintainer:** Anjo A. Tadena
- **Email:** tadena.anjo@gmail.com
