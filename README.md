![alt text](https://github.com/adavidoaiei/Flask-Python/blob/main/img.png?raw=true)
# Student Management System

A simple student management system built with Flask and SQLAlchemy that allows you to perform CRUD (Create, Read, Update, Delete) operations on student records.

## Features

- View all student records
- Add new student records
- Edit existing student information
- Delete student records
- SQLite database integration
- Flash messages for operation feedback

## Prerequisites

- Python 3.x
- Flask
- Flask-SQLAlchemy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system
```

2. Install the required dependencies:
```bash
pip install flask flask-sqlalchemy
```

3. Run the application:
```bash
python app.py
```

The application will be available at `http://localhost:5000`

## Database Structure

The application uses SQLite database with the following student model:

- student_id (Primary Key)
- name (String)
- city (String)
- addr (Address - String)
- pin (String)

## API Endpoints

- `GET /` - Display all student records
- `GET /new` - Display the form to add a new student
- `POST /new` - Add a new student record
- `GET /edit/<id>` - Display the form to edit a student's information
- `POST /edit/<id>` - Update a student's information
- `GET /delete/<id>` - Delete a student record

## Usage

1. View all students by accessing the home page
2. Click "Add New Student" to create a new student record
3. Fill in all required fields (name, city, address, and pin)
4. Use the edit button to modify existing records
5. Use the delete button to remove student records

## Development

The application runs in debug mode by default, making it easier to develop and test new features. The SQLite database is automatically created in the `instance` folder when you first run the application.

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project.

## License

This project is open source and available under the [MIT License](LICENSE).
