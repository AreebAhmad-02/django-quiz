# Django Quiz

**Deployed At:** [https://areeb02.pythonanywhere.com/](https://areeb02.pythonanywhere.com/)

This is an online quiz website project, developed using Python and the Django web framework. The front-end is styled with Bootstrap 4.

The project is live and accessible at the link above.

## Features

### Site Access:

- User must be logged in to access the Quiz.
- For signup, a user provides a username, first name, last name, e-mail address, and password.
- For login, the user provides a username and password.

### Quiz Features:

- All questions are multiple choice.
- Questions are displayed randomly and only once per user.
- If the user navigates away from a question, it is marked as attempted.
- Instant feedback is provided after each question.

### Leaderboard:

- The leaderboard ranks users by their total score.
- In case of a tie, the user who signed up earlier is ranked higher.
- The leaderboard is publicly accessible without login.

### Admin Features:

- Only administrators can add and modify questions.
- Once a question is published, it cannot be modified.
- Admins can search and filter questions.

## Getting Started With Development

Follow these instructions to set up a local development environment.

### Dependencies:

- Python 3.10 or newer
- Django 4.2 or newer

### Setup Steps:

1.  **Clone the repository:**
    Replace `your-username` with your actual GitHub username.

    ```bash
    git clone https://github.com/your-username/django-quiz.git
    cd django-quiz
    ```

2.  **Create and activate a virtual environment:**

    ```powershell
    # On Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

    ```bash
    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Navigate to the project directory:**
    The `manage.py` script is located in the `django_quiz` sub-directory.

    ```bash
    cd django_quiz
    ```

5.  **Run database migrations:**
    This command sets up your local database schema.

    ```bash
    python manage.py migrate
    ```

6.  **Create a superuser:**
    This account will have admin privileges. Follow the prompts to set a username and password.

    ```bash
    python manage.py createsuperuser
    ```

7.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```
    Your local copy of the site will be available at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
