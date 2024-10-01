# ClassConnect

ClassConnect is a web application that facilitates online learning and collaboration. It allows users to create and join study rooms, participate in discussions, and share knowledge on various topics.

## Features

- User authentication (login, logout, registration)
- Create, update, and delete study rooms
- Join existing study rooms
- Real-time chat functionality within rooms
- User profiles
- Topic-based room categorization
- Search functionality for rooms and topics
- Recent activity feed

## Technologies Used

- Django 5.1.1
- Python 3.12
- HTML/CSS
- JavaScript
- SQLite (default database)

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/Johnnytash/ClassConnect.git
   cd classconnect
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```
   python manage.py migrate
   ```

5. Create a superuser (admin):
   ```
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```
   python manage.py runserver
   ```

7. Open your browser and navigate to `http://127.0.0.1:8000`

## Usage

- Register for an account or log in
- Browse existing rooms or create your own
- Join rooms and participate in discussions
- Update your profile  in the user settings

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please contact [Your Name] at [johnthiongo@protonmail.com].