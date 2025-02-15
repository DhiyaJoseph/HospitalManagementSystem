# Hospital Management System

A web-based Hospital Management System built with Django that facilitates the management of hospital administration, doctors, and patients.

## Features

- Multi-user role system (Admin, Doctor, Patient)
- User authentication and authorization
- Responsive web interface
- Patient management
- Doctor management
- Appointment scheduling

## Technology Stack

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Django (Python)
- **Database:** SQLite (default Django database)

## Project Structure

```
HospitalManagement/
├── hospitalmanagement-master/
│   ├── templates/
│   │   └── hospital/
│   │       ├── aboutus.html
│   │       ├── navbar.html
│   │       └── footer.html
│   └── [other Django project files]
```

## Setup and Installation

1. Clone the repository
2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```
5. Create superuser:
   ```
   python manage.py createsuperuser
   ```
6. Run the development server:
   ```
   python manage.py runserver
   ```

## Usage

1. Access the admin panel at `http://localhost:8000/admin`
2. Login with superuser credentials
3. Create users and assign roles (Admin/Doctor/Patient)
4. Users can login through the main interface

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries, please open an issue in the repository.
