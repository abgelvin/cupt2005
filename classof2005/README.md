# classof2005/classof2005/README.md

# Class of 2005 Blog Application

This is a simple blog application created using Django, designed for users to post comments, reply to comments, and edit their own comments. 

## Features

- User authentication for posting comments
- Ability to create, edit, and delete comments
- Nested comments for replies

## Project Structure

```
classof2005/
├── class_blog/                # Blog application
│   ├── migrations/            # Database migrations
│   ├── templates/             # HTML templates
│   └── ...                    # Other app files
├── classof2005/               # Project configuration
│   ├── settings.py            # Django settings
│   └── ...                    # Other project files
├── manage.py                  # Command-line utility for Django
└── requirements.txt           # Project dependencies
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/cupt2005.git
   cd cupt2005
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```
   python manage.py migrate
   ```

5. Create a superuser to access the admin panel:
   ```
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```
   python manage.py runserver
   ```

## Usage

- Access the blog at `http://127.0.0.1:8000/`
- Log in with your superuser credentials to manage posts and comments.

## License

This project is licensed under the MIT License.